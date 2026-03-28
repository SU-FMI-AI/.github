# Contributing to SU-FMI-AI

Welcome! This document outlines the standards for contributing to the SU-FMI-AI organization. Our goal is to maintain a professional, reproducible, and long-lasting research archive.

---

## 🏗 Repository Visibility & Naming

1.  **Privacy First:** By default, **all repositories** (theses and projects) must be created as **Private**. Public release is only permitted after official approval.
2.  **Naming Convention:**
    * **Theses:** `thesis-<topic>-<year>-<month>` (e.g., `thesis-asr-2025-06`)
    * **Projects:** `<project_name>-<module>` (e.g., `bnr-audio-clean`)
    * **Tools/Libs:** `tool-<name>` or `lib-<name>`

---

## 📜 Thesis Submission Guidelines (For Students)

A thesis repository is an **immutable archival record**. It must be initialized from `template-thesis` and include:

### 📁 Required Structure & Files
* **`documents/`**: All official PDFs (Proposal, Thesis, Summaries, Review, Presentation).
* **`metadata.yaml`**: Mandatory file containing structured information about the student and research (see template).
* **`src/`**: Implementation code with a `requirements.txt` or `environment.yml`.
* **Setup Instructions**: Your `README.md` must contain clear, step-by-step installation instructions. A short **video recording** demonstrating the setup and basic usage is highly encouraged.

### 🎥 Demo Videos
To ensure long-term availability, **do not** use personal links. 
1.  Upload your demo video and/or setup recording to a cloud drive.
2.  Send the links to the organization admins. 
3.  The admins will upload them to the official **SU-FMI-AI YouTube Brand Account**.
4.  Once uploaded, place the official YouTube link in your `README.md`.

---

## 🚀 Research & Project Workflow

* **Modular Architecture:** Large projects should be split into smaller, functional modules (e.g., `bnr-asr`, `bnr-ocr`).
* **Lineage:** If a project module builds upon previous thesis work, you **must** reference the original `thesis-` repository in the README.
* **Large Files:** Never commit files larger than 50MB to GitHub. Host models and datasets on our [Hugging Face Hub](https://huggingface.co/SU-FMI-AI).

---

## ⚖️ Licensing

Every repository must contain a `LICENSE` file.
1.  **Theses:** Use the default **FMI Academic License** (found in the template).
2.  **Collaborative Projects:** Use the specific partner license (e.g., **BNR-FMI Internal Research License**).
3.  **Open Source & Data:** We support **MIT/Apache-2.0** for code and **CC-BY-SA-4.0** for datasets and research assets. Consult your supervisor before choosing.

---

**Questions?** Contact your supervisor or the organization administrators.
