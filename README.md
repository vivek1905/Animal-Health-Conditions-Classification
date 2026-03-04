# AI-Driven Animal Health Conditions Classification (SVM)

## Overview
This repository contains the code and resources for an **AI-Driven Animal Health Conditions Classification** project. The goal of the project is to classify animal health risk levels (e.g., high-risk vs normal) using structured symptom/feature inputs. The model uses a **Support Vector Machine (SVM)** pipeline with preprocessing, feature encoding, and hyperparameter tuning to achieve strong classification performance.

---

## Project Highlights
- Predicts **animal health condition/risk category** from symptom patterns
- Built using an **SVM classifier** with preprocessing and model tuning
- Includes evaluation using standard metrics (accuracy, precision, recall, F1-score, confusion matrix)

---

## Repository Contents
- **Animal_Health_Conditions_Classification.ipynb**  
  End-to-end notebook for preprocessing, SVM training, evaluation, and prediction.

---

## Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Google Colab / Jupyter Notebook  

---

## Getting Started (Google Colab)

1. Open the notebook in **Google Colab** (upload it or open from GitHub).
2. If the notebook reads a dataset file (CSV/XLSX), upload it into Colab using the file uploader, or ensure the dataset file is present in the repo.
3. Update the dataset file path in the notebook if needed.
4. Run the notebook cells in order:
   - Data loading + preprocessing (encoding/scaling)  
   - Model training (SVM) + hyperparameter tuning  
   - Evaluation (confusion matrix, precision/recall, etc.)  
   - Predictions on sample inputs  


## Output Example

A typical output includes - Model Accuracy / Precision / Recall / F1

Confusion Matrix showing performance on each class

Example:
Accuracy: ~95% (based on the evaluation split used in the notebook)
