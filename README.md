# Optimal SMOTE Variant Selection for Imbalanced Datasets in Educational Data Mining
This is the Code repository for the core part of our research paper "Optimal SMOTE Variant Selection for Imbalanced Datasets in Educational Data Mining Using ML, Statistics, MCDM, and XAI" where we evaluates various SMOTE techniques and machine learning models to address class imbalance in an educational dataset, identifying the optimal SMOTE variant.
## Overview
 The code focuses on the core part of our experiment where we applied  various SMOTE variants, trained machine learning models, and evaluated their performance on an imbalanced AI course  dataset. We used 5-fold cross-validation to compute key performance metrics.

## Dataset
The dataset used in this study is a real-time primary dataset collected from an AI (Artificial Intelligence) course in 2023 at the Faculty of Computing, UTM. It contains results from 420 students with the following features:
- Student ID: Unique identifier for each student (excluded from analysis).
- Quiz Marks: Scores from quizzes.
- Midterm Marks: Midterm examination scores.
- Assignment Marks: Scores from three assignments.
- Project Marks: Scores from a project.
- Presentation Marks: Scores from a presentation.
- Final Exam Marks: Final exam scores.
- Total Marks: Aggregate of all scores.
- Grades: Final grades assigned.
- Categories: Target variable, where we categorised each students into these five categories based on their Grades groups students into five performance categories:
  - Excellent
  - Exceptional
  - Distinction
  - Pass
  - Fail

### Note:
The dataset does not include any personal information about the students.  

## Citation
If you find this experiment or code useful in your research, please cite our paper

## Contents
This repository includes:
1. **`main_experiment.py`**: Python script to preprocess data, apply SMOTE variants, train machine learning models, and compute performance metrics.
2. **`requirements.txt`**: where we listed all Python libraries required to run our provided experiment.

## Prerequisites
You need **Python 3.8 or later**. Install the dependencies we provided  in `requirements.txt` using:
```bash
pip install -r requirements.txt


