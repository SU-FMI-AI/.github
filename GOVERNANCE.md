# SU-FMI-AI Organization Governance

This document outlines the access control policy and team structures within the SU-FMI-AI GitHub organization.


## 🛡️ Access Control Policy
By default, the organization operates on a **Zero Trust** basis. Base permissions are set to **No Permission**. Access is granted strictly through team membership.

### 📊 Access Matrix (Overview)

| Repository Type          | Admins | Maintainers | Leads     | Project Leads | Project Devs | Students  |
| :----------------------- | :----: | :---------: | :-------: | :-----------: | :----------: | :-------: |
| **`template-*`**         | Admin  | Maintain    | Read      | Read          | No Access    | Read      |
| **`thesis-*` (Active)**  | Admin  | Maintain    | No Access | No Access     | No Access    | No Access |
| **`thesis-*` (Done)**    | Admin  | Maintain    | Read      | Read          | Read         | Read      |
| **`prj-*` (Active)**     | Admin  | No Access   | No Access | Maintain      | Write        | No Access |
| **`tool-*` (Released)**  | Admin  | Maintain    | Read      | Read          | Read         | Read      |

<details>
<summary>🔍 Click here for the Detailed Access Matrix & Role Definitions</summary>

#### Detailed Access Matrix

| **Repository Type**           | **Admins** | **Maintainers** | **Leads**     | **PRJ_01 (Lead)** | **PRJ_01 (Dev)** | **PRJ_02 (Lead)** | **PRJ_02 (Dev)** | **Team X (Lead)** | **Team X (Dev)** | **Author (Student)** | **Students** |
| ----------------------------- | ---------- | --------------- | ------------- | ----------------- | ---------------- | ----------------- | ---------------- | ----------------- | ---------------- | -------------------- | ------------ |
| **`template-*`**              | Admin      | **Maintain**    | Read\*        | Read\*            | No Access        | Read\*            | No Access        | Read\*            | No Access        | Read\*               | Read\*       |
| **`template-project`**        | Admin      | **Maintain**    | No Access     | Read              | No Access        | Read              | No Access        | No Access         | No Access        | No Access            | No Access    |
| **`template-project-module`** | Admin      | **Maintain**    | No Access     | Read              | No Access        | Read              | No Access        | No Access         | No Access        | No Access            | No Access    |
| **`template-general`**        | Admin      | **Maintain**    | Read          | No Access         | No Access        | No Access         | No Access        | Read              | No Access        | No Access            | No Access    |
| **`template-thesis`**         | Admin      | **Maintain**    | Read          | No Access         | No Access        | No Access         | No Access        | No Access         | No Access        | Read                 | Read         |
| **`thesis-*` (Active)**       | Admin      | **Maintain**    | No Access\*\* | No Access         | No Access        | No Access         | No Access        | No Access         | No Access        | **Write**            | No Access    |
| **`thesis-*` (Done)**         | Admin      | **Maintain**    | Read          | Read              | Read             | Read              | Read             | Read              | Read             | Read                 | Read         |
| **`prj01-*` (Project)**       | Admin      | No Access       | No Access     | **Maintain**      | **Write**        | No Access         | No Access        | No Access         | No Access        | No Access            | No Access    |
| **`prj02-*` (Project)**       | Admin      | No Access       | No Access     | No Access         | No Access        | **Maintain**      | **Write**        | No Access         | No Access        | No Access            | No Access    |
| **`tool-x-*` (Private)**      | Admin      | No Access       | No Access     | No Access         | No Access        | No Access         | No Access        | **Maintain**      | **Write**        | No Access            | No Access    |
| **`tool-x-*` (Released)**     | Admin      | **Maintain**    | Read          | Read              | Read             | Read              | Read             | **Maintain**      | **Write**        | Read                 | Read         |

*\* Partially True*  
*\*\* The access is individual - only for student's consultants.*

#### Role Eligibility
- **Maintainers**: PhD and PhD Candidates at SU, FMI.
- **Leads**: PhD Candidates and Alumni MSs Students at SU, FMI.
- **Project Team Lead**: PhD Candidates and Researchers (at least Alumni MSs Students).
- **Project Team Dev**: Researchers and Students at SU, FMI.
- **Students**: Alumni and Active Students at SU, FMI.

</details>


## 👥 Team Definitions

### 🛠️ Maintainers
Core PhD team responsible for global infrastructure, template management, and repository archiving.

### 🎓 Leads
PhD Candidates and researchers who require read access to the research archive and general-purpose templates.

### 🏗️ Project Teams (Nested)
Each project (e.g., `BNR`) has two sub-teams using the `[PROJECT]-[ROLE]` naming convention:
- **Lead**: Technical management and maintenance of project repos.
- **Dev**: Write access for active implementation.

### 🧑‍🎓 Students
All active and alumni students. Granted read access only to public templates and finalized (Done) theses.

---
*Last Updated: April 2026*