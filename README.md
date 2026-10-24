# Anomaly Detection (Isolation Forest & LOF)

Unsupervised anomaly detection in Jupyter — comparing **Isolation Forest** and **Local Outlier Factor** on tabular data, with visual inspection of the points each method flags.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

## Overview

## Origin

This project was originally developed inside the `Data-Science` notebook collection and now lives in its own repository for easier discovery and use.

The notebook (30 cells) loads a dataset (`cancer.csv`), prepares and scales the features, then applies two classic outlier-detection algorithms — Isolation Forest and Local Outlier Factor — and visualizes how their anomaly calls differ.

## What's Inside

- `anomaly_detection.ipynb` — data prep → Isolation Forest → Local Outlier Factor → comparison plots

## Getting Started

```bash
git clone https://github.com/datascientist970/anomaly-detection-ml.git
cd anomaly-detection-ml
pip install -r requirements.txt
jupyter notebook anomaly_detection.ipynb
```

Place the dataset CSV in the working directory before running (not included in this repository).

## Tech Stack

Python · scikit-learn · Pandas · NumPy · Matplotlib

## Author

**Muhammad Dawood** — AI & Data Science Engineer
GitHub: https://github.com/datascientist970 · LinkedIn: https://www.linkedin.com/in/dawood406/
Mardan, Khyber Pakhtunkhwa, Pakistan
