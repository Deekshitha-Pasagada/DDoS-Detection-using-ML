# DDoS-Detection-using-ML
Machine Learning-based system for detecting and classifying DDoS attacks in IoT networks using Random Forest, SVM, Naive Bayes, XGBoost, AdaBoost, and KNN.

# A Novel Method to Detect the DDoS Attack in Network using Machine Learning
In this project, **Machine Learning algorithms** are used to detect and categorize Distributed Denial of Service (DDoS) threats in IoT network environments. By flooding network resources with malicious traffic, DDoS assaults block services from being accessed by authorized users. Using machine learning models, our method reliably and securely detects a wide range of attack types.

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
Performance of models (from experiments):

| Algorithm        | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Naive Bayes      | 40.14%   | 47.97%    | 45.10% | 37.58%   |
| Random Forest    | **96.37%** | **96.78%** | **96.56%** | **96.65%** |
| SVM              | 67.60%   | 75.25%    | 69.08% | 69.81%   |
| XGBoost          | 92.97%   | 94.19%    | 93.80% | 93.73%   |
| AdaBoost         | 56.23%   | 60.31%    | 53.51% | 53.99%   |
| KNN              | 84.89%   | 88.18%    | 86.04% | 86.01%   |

*(Random Forest achieved the best performance):contentReference[oaicite:0]{index=0}*

# Installation & Usage
1. Clone the repository:
   git clone [https://github.com/YOUR-USERNAME/DDoS-Detection-ML.git](https://github.com/Deekshitha-Pasagada/DDoS-Detection-using-ML.git)
   cd DDoS-Detection-ML

2. Install Dependencies:
   pip install -r requirements.txt

3. Run the project:
   python src/Main.py

# Repository Structure
- **src/** → Python source code (`Main.py`)
- **docs/** → Abstract, SRS, Documentation, and PPT
- **results/** → Accuracy/Performance comparison table
- **requirements.txt** → Required Python libraries
- **run.bat** → Script to run the project

# Authors
- Deekshitha Pasagada
- Kenneth Gadhari
- Rohan Adithya  

**Guided by**: Dr. Thota. Siva Ratna Sai
