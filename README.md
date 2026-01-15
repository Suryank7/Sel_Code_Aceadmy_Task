# Heart Disease Prediction: Machine Learning Tutorial

This repository contains a complete, end-to-end Machine Learning pipeline for heart disease prediction, designed for educational purposes.

## Overview

The project demonstrates the construction of an Artificial Intelligence system capable of predicting the presence of heart disease in patients. It utilizes the **UCI Heart Disease Dataset**, a standard benchmark in the machine learning community.

**Key Objectives:**
- Demonstrate the complete Machine Learning workflow: Data Loading, Preprocessing, Training, and Evaluation.
- Utilize a real-world medical dataset to simulate practical application.
- Implement and explain an interpretable **Logistic Regression** model.
- Visualize model performance metrics and feature importance.

## Features

- **Real-World Data Utilized**: Leverages the clinically relevant UCI Heart Disease dataset obtained via Kaggle.
- **Comprehensive Pipeline**: Includes robust data cleaning (handling missing values), feature scaling (StandardScaler), model training, and performance evaluation.
- **Interpretable AI Model**: Focuses on explainability by analyzing feature importance (e.g., impact of Chest Pain, Maximum Heart Rate) on predictions.
- **Analytical Visualizations**: Generates professional-grade charts for Confusion Matrix and Feature Importance analysis.
- **Inference Capability**: Includes a demonstration of risk prediction for new, unseen patient data.

## Project Structure

| File | Description |
|------|-------------|
| `heart_disease_demo.py` | The main executable Python script containing the full Machine Learning pipeline. |
| `ML_Teaching_Video_Script.md` | A detailed step-by-step educational script and demonstration flow. |
| `heart_disease_analysis.png` | The generated visualization output showing model analysis metrics. |

## Requirements

To execute this project, Python is required along with the following dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage Instructions

1.  **Clone the repository** or download the source files.
2.  **Install dependencies** using the command provided in the Requirements section.
3.  **Execute the main script**:

```bash
python heart_disease_demo.py
```

The script performs the following operations:
1.  Loads the dataset (automatically fetching from the UCI repository or using a local fallback).
2.  Trains the Logistic Regression model.
3.  Outputs evaluation metrics and model explanations to the console.
4.  Generates and saves the `heart_disease_analysis.png` file.

## Acknowledgments

- **Dataset**: [UCI Heart Disease Data](https://archive.ics.uci.edu/ml/datasets/heart+disease)
- **Author**: SelfCode Academy
