🧠 Autism Spectrum Disorder (ASD) Screening Data Analysis
📊 Project Overview
This project analyzes a behavioral dataset designed to screen for Autism Spectrum Disorder (ASD) in toddlers. It explores the features derived from the Q-Chat-10 questionnaire and other individual attributes, applying data analysis techniques to uncover meaningful patterns and insights that may assist in early ASD detection.

📁 Dataset Description
Source: ASDTests.com

Author: Dr. Fadi Thabtah, Manukau Institute of Technology, New Zealand

Type: Predictive and Descriptive

Instances: 1054

Attributes: 18 (including the class label)

Data Format: Non-matrix (CSV)

🔍 Features
Feature Code	Description
A1 - A10	Q-Chat-10 questions (binary features: 1 = potential ASD trait)
age	Age of the toddler
sex	Gender (Male/Female)
ethnicity	Ethnic background
jaundice	Whether the child had jaundice at birth (yes/no)
family_mem_with_ASD	Family history of ASD (yes/no)
who_completed_the_test	Person who completed the test (self/parent/etc.)
class	Final diagnosis label (YES = ASD traits, NO = no ASD traits)
📝 The dataset contains no missing values. The Score variable is discarded as it was used to assign the class label and would cause data leakage if used in model training.

🧪 Project Objectives
Explore the dataset for patterns related to ASD tendencies.

Investigate relationships between demographic attributes and ASD presence.

Clean and preprocess data (handle duplicates, irrelevant features).

Provide insight on how factors like ethnicity, gender, or jaundice correlate with ASD likelihood.

🔍 Key Analyses
Structure & Quality Investigation:

Identified data types (categorical vs numerical).

Removed duplicates to maintain dataset integrity.

Demographic Analysis:

Ethnicity: White Europeans showed the highest number of ASD cases, followed by Asians. Pacifica ethnicity showed the highest percentage of ASD cases relative to its sample.

Gender: Males had a significantly higher percentage of ASD diagnosis.

Jaundice: A slight correlation between jaundice at birth and ASD was observed.

Family History: Toddlers with a family member diagnosed with ASD had a noticeably higher chance of ASD.

Visualization:

Plots and charts were used to represent:

Distribution by gender and class

Ethnicity vs ASD count

Jaundice/family history vs ASD diagnosis

📌 Insights
The Q-Chat-10 features play a pivotal role in the screening process.

Demographic features like gender, ethnicity, and family history of ASD show strong correlation with ASD classification.

Early behavioral markers can serve as effective screening indicators even before formal diagnosis.

📈 Future Scope
Extend the project by training machine learning classifiers (Random Forest, Logistic Regression, SVM) on the processed data.

Add performance evaluation metrics (accuracy, recall, precision, F1-score).

Implement model interpretability techniques like SHAP or LIME for deeper feature importance insights.
