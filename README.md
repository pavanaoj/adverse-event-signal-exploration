# Adverse Event Signal Exploration

A beginner-friendly healthcare data analytics project that explores reporting patterns in a small synthetic adverse-event dataset.

## Objective

The project demonstrates how to:

- clean drug, reaction, severity, age-group, and outcome fields
- calculate reporting frequency
- calculate the proportion of reports flagged as serious for this exercise
- visualize drug/event reporting patterns
- communicate potential reporting signals cautiously

## Dataset

`adverse_drug_reactions_sample.csv` is the supplied synthetic sample used for this project.

**Important:** The data are synthetic/de-identified for learning. Reporting frequency is not the same as incidence, and a reporting signal does **not** prove causation.

## Project files

- `adverse_event_signal_exploration.ipynb` — reproducible analysis notebook
- `adverse_drug_reactions_sample.csv` — supplied input dataset
- `adverse_drug_reactions_cleaned.csv` — cleaned/derived analysis dataset
- `safety_signal_exploration_report.md` — short final report
- `charts/` — generated figures
- `requirements.txt` — Python dependencies

## Key results from the supplied sample

- Total reports: **8**
- Unique suspected drugs: **8**
- Unique adverse reactions: **8**
- Serious reports under the exercise definition: **3**
- Serious-report proportion: **37.5%**
- Repeated drug–event pairs: **0**

Because every observed drug–event combination occurs once, this sample does not contain a repeated high-frequency drug–event pair.

## How to run

Open the notebook in Google Colab or Jupyter Notebook and run all cells.

For Google Colab:
1. Upload the notebook and CSV.
2. Open `adverse_event_signal_exploration.ipynb`.
3. Upload `adverse_drug_reactions_sample.csv` when prompted, or keep both files in the same Colab working directory.
4. Run **Runtime → Run all**.

## Safety / governance note

This project is for descriptive learning only. It must not be used to make treatment decisions or claim that a drug caused an adverse event. Any real-world pharmacovigilance signal requires expert review and appropriate validated methods.
