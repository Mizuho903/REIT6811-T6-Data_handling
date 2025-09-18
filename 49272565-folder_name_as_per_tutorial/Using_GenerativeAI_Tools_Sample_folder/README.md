## 📂 Folder Structure

.
├── 01_manuscripts
│ ├── Conference_Paper_v1_20250918.docx
│ └── Conference_Paper_Submission_20250918.pdf
├── 02_drafts
│ └── Proposal_Draft_v1_20250918.docx
├── 03_images
│ ├── Diagram_Workflow_20250918.png
│ └── Screenshot_ToolUsage_20250918.png
├── 04_references
│ ├── Reference_List_v1_20250918.bib
│ └── Reference_9783031849671_20250918.pdf
├── 05_interviews
│ ├── Interview_C_Eric_20250917.docx
│ ├── Interview_C_Jason_20250918.docx
│ └── Interview_F_Final_Summary_20250918.docx
├── 06_unsorted_data
│ ├── 01_images/
│ ├── 02_raw_data/
│ ├── 03_processed_data/
│ └── 04_code/
├── 07_submissions
│ ├── Final_Paper_v1_20250918.docx
│ ├── Final_Paper_Submission_20250918.pdf
│ └── Proposal_Final_v1_20250918.docx
└── README.md

markdown
Copy code

---

## 📝 Naming Conventions

1. **Folders**

   - **Numbered** (`01_…`, `02_…`, etc.) to enforce logical order.
   - **Lowercase with underscores** for readability.

2. **Files**
   - **Prefix** with type/purpose (e.g. `Conference_Paper`, `Survey_Raw_Data`, `Proposal_Draft`).
   - **Suffix** with version (`v1`, `v2`, etc.) when relevant.
   - **Date** in `YYYYMMDD` format for all files.
   - **Extensions** reflect native format (`.docx`, `.pdf`, `.csv`, `.png`, `.py`, etc.).

Example:
Survey_Analysis_v2_20250918.csv

yaml
Copy code

---

## 🔒 Access Levels

- **Public**
  Final outputs and published materials (e.g., `07_submissions/Final_Paper_Submission_*.pdf`).

- **Internal**
  Work-in-progress data and drafts shared with the project team only (e.g., `02_drafts/`, `06_unsorted_data/03_processed_data/`).

- **Private**
  Sensitive materials like raw transcripts or consent forms stored in a locked folder within `05_interviews/` or `06_unsorted_data/02_raw_data/`.

---

## 🚀 Getting Started

1. **Clone** this repo:
   ```bash
   git clone https://github.com/your-user/Using_GenerativeAI_Tools.git
   ```
