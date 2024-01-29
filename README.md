# Text-Classification-ML-Workflow
Multi-Class Text Classification Workflow using ML and NLP (end-to-end) 

## Overview

This notebook demonstrates the implementation of a multi-class text classification model using machine learning techniques. The goal is to classify textual data into different predefined categories, such as business, entertainment, politics, sports, and technology. The model is trained on a dataset containing text samples from various categories.

## Table of Contents

1. **Hypothesis Generation**
   - Overview of the project.
   - Purpose and objectives.

2. **Import Libraries**
   - Import all essential libraries for data processing and model building. 

3. **Import Dataset**
   - Description of the dataset used for training and evaluation.
   - https://www.kaggle.com/competitions/learn-ai-bbc/data

4. **Exploratory Data Analysis (EDA - 1)**
   - Visualization of data distribution.
   - Label frequency analysis.
  
5. **Data Preprocessing**
   - Remove Unnecessary Columns
   - Tokenization
   - Handle Missing Values
   - Handle Errors/Noise
   - Remove Duplicates
   - Check Data Distribution and Skewness (Feature Scaling) 

6. **Exploratory Data Analysis (EDA - 2)**
   - Visualization of data distribution.
   - Word frequency analysis.
   - Word cloud visualizations for each category.
  
7. **Dataset Splitting**
   - Split the data into training and validation sets.

8. **Data Transformation (for NLP)**
   - Embedding and Encoding 

9. **Model Selection and Fine-Tuning**
   - Choice of machine learning algorithms.
   - Hyperparameter tuning.
   - Training process and evaluation metrics.

10. **Model Finalization and Dumping**
   - Train the selected best model architecture on entire training data without splitting.
   - Save the model to local.

11. **Load Dumped Model for Real-time Testing**
   - Code snippets for real-time testing of the model on new text samples.



## Requirements

- Python 3.11.7
- Libraries (install using `pip install -r requirements.txt` or `conda env create -f environment.yml`).
