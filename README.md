# NLP

This repository contains Python code developed for an NLP project that classifies pre-operative radiology reports to predict surgical outcomes using language models like BERT and GatorTron. The project was developed in a secure offline environment (SHAIP) as part of a Health Data Science placement at NHS Grampian and the University of Aberdeen.

---

##  Repository Structure

| Folder | Description |
|--------|-------------|
| `LLM/` | Secure-environment code for fine-tuning BERT on radiology reports (`operated_on` classification) |
| `Class_Imbalance/` | Code for model evaluation, threshold tuning using ROC curve and G-Mean |
| `LICENSE` | Optional license file if you plan to publicly share the code |

---

## Models Used
- `bert-base-uncased` (fine-tuned within SHAIP)
- (Optionally) `uflorida/gatortron-base` for clinical-domain benchmarking

---

## Data Disclaimer

**No sensitive patient data is included** in this repository. All notebooks are designed to run on secure, non-public datasets within the SHAIP environment and cannot be executed outside without data access.

---

##  How to Run

All code is developed in Jupyter Notebooks within the SHAIP desktop. To run:
1. Place your `.csv` file in the secure workspace.
2. Update paths in the code (e.g. `csv_file_path`, `local_model_path`).
3. Run each cell top-to-bottom. No internet access or pip installation is required.

---

##  Acknowledgements

This work was supervised by [Dr. Luke Farrow](https://github.com/lukefarrow) and conducted under the ARCHERY project.

