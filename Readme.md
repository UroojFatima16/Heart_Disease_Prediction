Heart Disease Prediction using Deep Learning, Explainable AI, LLMs, and RAG

## Overview

This repository presents a comprehensive framework for **heart disease prediction** by comparing three deep learning architectures:

* **Long Short-Term Memory (LSTM)**
* **Convolutional Neural Network (CNN)**
* **Hybrid CNN-LSTM**

Beyond prediction accuracy, the framework emphasizes **model interpretability** through Explainable AI (XAI) and **natural language clinical explanations** using Large Language Models (LLMs) integrated with Retrieval-Augmented Generation (RAG).

The objective is to develop an accurate, transparent, and clinically meaningful decision-support system for cardiovascular disease prediction.

## Research Objectives

* Predict heart disease using deep learning models.
* Compare CNN, LSTM, and Hybrid CNN-LSTM architectures.
* Evaluate model performance using standard classification metrics.
* Explain model predictions using Explainable AI.
* Generate clinician-friendly explanations with LLMs.
* Improve explanation reliability using Retrieval-Augmented Generation (RAG).
## Novelty of the Research

Unlike traditional heart disease prediction systems that focus only on prediction accuracy, this framework combines:

* Comparative evaluation of CNN, LSTM, and Hybrid CNN-LSTM models.
* Explainable AI for transparent decision-making.
* LLM-generated natural language explanations.
* Retrieval-Augmented Generation (RAG) grounded in trusted medical knowledge.
* End-to-end interpretable AI pipeline suitable for healthcare applications.

The integration of predictive modeling, explainability, and knowledge-grounded language generation provides a more trustworthy AI-assisted diagnostic framework.

---

## System Architecture

```text
                    Heart Disease Dataset
                             │
                    Data Preprocessing
                             │
          Feature Engineering & Normalization
                             │
        ┌──────────────┬──────────────┬──────────────┐
        │              │              │
      CNN            LSTM        Hybrid CNN-LSTM
        │              │              │
        └──────────────┴──────────────┘
                     Performance Comparison
                             │
                Best Performing Model
                             │
               Explainable AI (SHAP / LIME)
                             │
             Structured Feature Importance
                             │
                 Retrieval-Augmented Generation
                             │
             Medical Knowledge Base Retrieval
                             │
                    Large Language Model
                             │
      Clinically Understandable Prediction Report
```

---

## Features

* Heart disease prediction
* CNN implementation
* LSTM implementation
* Hybrid CNN-LSTM implementation
* Hyperparameter tuning
* Performance comparison
* Explainable AI
* SHAP explanations
* LIME explanations
* Feature importance visualization
* LLM-based explanation generation
* Retrieval-Augmented Generation (RAG)
* Medical knowledge retrieval
* Clinical report generation

---

## Dataset

Recommended datasets include:

* UCI Heart Disease Dataset
* Cleveland Heart Disease Dataset
* Kaggle Heart Disease Dataset

Example features:

* Age
* Gender
* Chest Pain Type
* Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* ECG Results
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Number of Major Vessels
* Thalassemia

---

## Data Preprocessing

* Missing value handling
* Outlier detection
* Feature scaling
* Label encoding
* One-hot encoding
* Feature normalization
* Train-test split
* Cross-validation

---

## Models

### 1. CNN

Convolutional Neural Network adapted for structured tabular healthcare data to learn local feature interactions.

---

### 2. LSTM

Long Short-Term Memory network capable of learning long-range feature dependencies and complex nonlinear relationships.

---

### 3. Hybrid CNN-LSTM

Combines CNN feature extraction with LSTM sequential learning to leverage the strengths of both architectures.

---

## Explainable AI (XAI)

This project integrates Explainable AI techniques to improve transparency.

### SHAP

* Global feature importance
* Local prediction explanations
* Force plots
* Summary plots
* Dependence plots

### LIME

* Local explanation for individual patients
* Feature contribution analysis
* Model behavior interpretation

---

## LLM Integration

The project converts XAI outputs into structured prompts that are processed by a Large Language Model.


## Retrieval-Augmented Generation (RAG)

Instead of relying solely on the LLM's internal knowledge, the system retrieves relevant clinical information from trusted medical sources before generating explanations.

Knowledge sources may include:

* American Heart Association (AHA)
* World Health Organization (WHO)
* PubMed publications
* Clinical guidelines
* Medical textbooks

Benefits:

* Reduced hallucinations
* Evidence-grounded explanations
* Improved factual consistency
* Better clinical reliability

---

## Evaluation Metrics

Classification Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* PR-AUC
* Specificity
* Sensitivity

