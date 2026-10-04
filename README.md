# Ultrasound Retrieval-Augmented Report Generation

A research framework for automated ultrasound report generation using study-level visual representation learning, retrieval-augmented consensus, and clinical finding-based evaluation.

The project investigates automated ultrasound reporting under low-resource conditions using a small single-centre dataset of ultrasound studies paired with radiologist-written reports.

---

## 📌 Project Overview

This project implements an end-to-end research pipeline for:

- Ultrasound dataset construction
- Exploratory data analysis
- Image preprocessing
- Baseline model evaluation
- BiomedCLIP-based multimodal learning
- Study-level visual representation learning
- Retrieval-augmented report generation
- Explainability and statistical analysis
- Result visualization
- Manuscript table generation

The main reporting framework uses:

**Ultrasound Images → Frame-Level Visual Features → Study-Level Representation → FAISS Retrieval → Similarity-Weighted Finding Consensus → Phrasebook-Based Report Generation**

---

## 📂 Project Structure

```text
Ultrasound-RAG/
│
├── 00-dataset-build.ipynb
├── 01-eda.ipynb
├── 02-preprocessing-splits.ipynb
├── 03-baselines.ipynb
├── 04-biomedclip-multitask (1).ipynb
├── 05-rag-report-generation.ipynb
├── 06-explainability-stats.ipynb
├── 07-results-dashboard.ipynb
├── 08-manuscript-tables.ipynb
│
├── data/
│   ├── images/
│   ├── reports/
│   └── metadata/
│
├── models/
├── results/
├── figures/
├── tables/
└── README.md
