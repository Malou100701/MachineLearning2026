# Delta Air Lines – Flight Delay Prediction

## Project Overview

This project is part of the _Applied Machine Learning_ course at Copenhagen Business School (Fall 2026).

The objective is to investigate whether machine learning can predict arrival delays for Delta Air Lines flights using information available before departure.

## Dataset

The project uses the **Bureau of Transportation Statistics (BTS) Reporting Carrier On-Time Performance** dataset, covering Delta-operated flights from January to December 2025.

The target variable is `ARR_DEL15`, indicating whether a flight arrives at least 15 minutes late.

## Methodology

The analysis includes data cleaning, exploratory data analysis, feature selection, model training, and evaluation.

## Repository Structure

- `flight_delay_analysis.ipynb` – Main Jupyter notebook containing the analysis.
- `data/` – Monthly BTS datasets (`01-2025.csv` … `12-2025.csv`).
- `random_forest_*.csv` – Saved model outputs (feature importance, predictions, and test results).
- `README.md` – Project description.

## Group Members

- Josephine Holst-Christensen
- Malou Amalie Bjørnholt Lüthcke
- Thomas Studstrup Sejr
- Mads Pedersen
