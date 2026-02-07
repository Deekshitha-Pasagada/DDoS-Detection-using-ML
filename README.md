# DDoS-Detection-using-ML
Machine Learning-based system for detecting and classifying DDoS attacks in IoT networks using Random Forest, SVM, Naive Bayes, XGBoost, AdaBoost, and KNN.

# Overview
This project implements an end-to-end machine learning pipeline to detect and classify DDoS attacks in IoT network traffic. Multiple classical ML models are trained, evaluated, and compared to understand how preprocessing, feature handling, and model choice impact detection performance in real-world scenarios.

# Domain Lens (AI/ML + SDE + Data)

### AI / ML
- Implemented and benchmarked multiple ML classifiers for DDoS detection.
- Evaluated models using Accuracy, Precision, Recall, and F1-score.
- Identified Random Forest as the best-performing model based on experimental results.

### Software Engineering
- Structured the project as a runnable application with a GUI for testing and demonstration.
- Designed repeatable workflows for training, evaluation, and comparison of models.
- Focused on reproducibility and consistency across experiments.

### Data
- Performed data preprocessing and feature preparation before model training.
- Validated input consistency and ensured fair comparison across models.
- Used structured result summaries to support model selection decisions.

# Features
Detection and classification of different DDoS attacks.
- Implementation of multiple ML models:
  - Random Forest
  - Naive Bayes
  - Support Vector Machine (SVM)
  - XGBoost
  - AdaBoost
  - K-Nearest Neighbors (KNN)
- Performance comparison across models using **Accuracy, Precision, Recall, and F1-Score**.
- GUI-based application built with **Tkinter**.
- Visual outputs such as confusion matrices and performance graphs.

# Results
The following table summarizes the performance of each model on the prepared dataset using standard classification metrics.


| Algorithm        | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Naive Bayes      | 40.14%   | 47.97%    | 45.10% | 37.58%   |
| Random Forest    | **96.37%** | **96.78%** | **96.56%** | **96.65%** |
| SVM              | 67.60%   | 75.25%    | 69.08% | 69.81%   |
| XGBoost          | 92.97%   | 94.19%    | 93.80% | 93.73%   |
| AdaBoost         | 56.23%   | 60.31%    | 53.51% | 53.99%   |
| KNN              | 84.89%   | 88.18%    | 86.04% | 86.01%   |

**Random Forest achieved the best performance**

# Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Deekshitha-Pasagada/DDoS-Detection-using-ML.git 
   cd DDoS-Detection-using-ML

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the project:
   ```bash
   python src/Main.py

# Repository Structure
- **src/** → Python source code (`Main.py`)
- **docs/** → Documentation
- **results/** → Accuracy/Performance comparison table
- **requirements.txt** → Required Python libraries
- **run.bat** → Script to run the project

# Future Improvements
- Add automated scripts for training and evaluation.
- Save model artifacts and evaluation metrics for reproducibility.
- Package the workflow as a CLI or API for easier reuse.
- Extend evaluation to additional datasets or traffic patterns.


# Authors
- Deekshitha Pasagada
- Kenneth Gadhari
- Rohan Adithya  

**Guided by**: Dr. Thota. Siva Ratna Sai
