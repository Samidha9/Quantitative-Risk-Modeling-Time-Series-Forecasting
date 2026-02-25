# JPMorgan Quantitative Research Simulation

## Overview

This repository contains work completed as part of the **JPMorgan Chase & Co. Quantitative Research Virtual Experience Program (Forage)**.

The project simulates core quantitative research tasks, including:

* Financial time-series modeling and forecasting
* Credit risk modeling and Probability of Default (PD) estimation
* Statistical evaluation and model performance analysis
* Algorithmic risk segmentation

The objective was to apply statistical and quantitative techniques to financial datasets within a structured research workflow.

---

## Project Structure

### Task 1 – Financial Time-Series Modeling

Modeled Natural Gas price behavior using deterministic regression techniques.

Key components:

* Trend modeling using deterministic processes
* Seasonal structure using Fourier-based terms
* Construction of design matrices
* In-sample fitting and out-of-sample forecasting

This task focused on capturing temporal structure and evaluating model generalization for price prediction.

---

### Task 2 – Credit Risk Modeling

Analyzed loan-level financial data to estimate **Probability of Default (PD)**.

Key steps:

* Data cleaning and preprocessing
* Logistic regression modeling
* Model performance evaluation using:

  * ROC-AUC
  * Confusion Matrix
  * Classification metrics

This task emphasized statistical classification techniques and interpretation of risk probabilities.

---

### Task 3 – Default Rate Analysis by Credit Score

Performed structured analysis of default behavior across credit score segments.

Key components:

* Cumulative default rate computation
* Risk segmentation analysis
* Statistical comparison across score ranges

This stage focused on understanding how default probability varies across borrower quality tiers.

---

### Task 4 – Algorithmic Credit Score Binning

Implemented an algorithmic approach to convert continuous credit scores into optimized categorical risk groups.

Key concepts:

* Dynamic programming logic for score partitioning
* Log-likelihood optimization
* Risk segmentation interpretability

This task demonstrated structured quantitative reasoning and optimization techniques.

---

## Tools & Techniques Used

* Python
* Pandas, NumPy
* Statistical Modeling
* Time-Series Analysis
* Classification Modeling
* Model Evaluation Metrics
* Data Validation & Preprocessing
