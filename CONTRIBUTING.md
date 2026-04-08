# Contributing to SU-FMI-AI

Welcome! This document outlines the standards for contributing to the SU-FMI-AI organization. Our goal is to maintain a professional, reproducible, and long-lasting research archive.

---

## 🏗 Repository Visibility & Naming

1.  **Privacy First:** By default, **all repositories** (theses and projects) must be created as **Private**. Public release is only permitted after official approval.
2.  **Naming Convention:**
    - **Theses:** `thesis-<topic>-<year>-<month>` (e.g., `thesis-asr-2026-06`)
    - **Projects:** `<project_name>-<module>` (e.g., `bnr-audio-clean`)
    - **Tools/Libs:** `tool-<name>` or `lib-<name>`

---

## 🎓 Thesis Submission Guidelines (For Students)

A thesis repository is an **immutable archival record**. It must be initialized from `template-thesis` and include:

### 📁 Required Structure & Files
- **`documents/`**: Official PDFs (Proposal, Final Thesis, Summaries, Review) and any related research papers or publications.
- **`src/`**: Implementation source code and dependencies.
- **`data/`**: Sample datasets or references to Hugging Face.
- **`artifacts/`**: Defense materials (Presentation), figures, and logs.
- **`metadata.yaml`**: Mandatory file containing structured bilingual metadata.

### 🎥 Documentation & Media
- **Bilingual Readme:** Every repository must include both `README.md` (EN) and `README.bg.md` (BG).
- **Demo Videos:** To ensure long-term availability, **do not** use personal links. Submit your recordings (demo and/or setup) to the organization admins to be uploaded to the official **SU-FMI-AI YouTube Brand Account**.

---

## 🚀 Research & Project Workflow

- **Modular Architecture:** Large projects should be split into smaller, functional modules (e.g., `bnr-asr`, `bnr-ocr`).
- **Lineage:** If a project module builds upon previous thesis work, you **must** reference the original `thesis-` repository in the README.
- **Large Files:** Avoid committing files larger than 50MB to GitHub. Large datasets and trained models must be hosted on our [Hugging Face Hub](https://huggingface.co/SU-FMI-AI).

---

## ⚖️ Licensing

Every repository must contain a `LICENSE` file.
1.  **Default:** Use the **SU-FMI-AI Academic Research License** for all internal research and theses.
2.  **External Partnerships:** Specific licenses (e.g., partner-specific agreements) apply only when explicitly required by a project coordinator.
3.  **Open Source:** For approved public releases, we support **MIT/Apache-2.0** for code and **CC-BY-SA-4.0** for assets. Consult your supervisor before making any repository public.

---

**Questions?** Contact your supervisor or the organization administrators.
