# Evaluation of Synthetic Tabular Data

Data Science Lab I project

## Project overview

Synthetic data generators create artificial tables that aim to preserve the characteristics of real data. This project investigates how the quality of synthetic tabular data can be evaluated, comparing several generation methods across three dimensions:

- **Fidelity**: how closely the synthetic data resembles the real data (feature distributions, relationships between variables)
- **Utility**: how useful the synthetic data is for downstream machine learning, e.g. Train-on-Synthetic, Test-on-Real (TSTR)
- **Privacy**: how much information about the original records may be exposed

## Repository structure

```
├── data/          # Download scripts or small datasets (large data is not committed)
├── notebooks/     # Exploratory data analysis and experiments
├── src/           # Reusable code: preprocessing, generators, evaluation
├── results/       # Metric tables and experiment outputs (CSV)
├── figures/       # Plots used in the report
├── requirements.txt
└── README.md
```

## Setup

The project runs locally or in Google Colab.

```bash
git clone https://github.com/sharonjepngetichsaina/dslab1_synthetic_data.git
cd dslab1_synthetic_data
pip install -r requirements.txt
```

## Reproducing the results

Instructions will be added as experiments are developed.

## Project status

- [ ] M1: Literature review, dataset selection & project setup (due 20 Oct 2026)
- [ ] M2: Baselines & methodology (due 15 Nov 2026)
- [ ] M3: Implementation & experiments (due 10 Jan 2027)
- [ ] Final submission (due 20 Jan 2027)
