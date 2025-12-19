# Lecture 2: Machine Learning Fundamentals for Healthcare

## Learning Objectives
By the end of this lecture, students will be able to:
1. Understand core machine learning concepts and algorithms
2. Recognize different types of healthcare data used in ML
3. Explain the ML pipeline from data collection to deployment
4. Identify appropriate ML techniques for healthcare problems

## Topics Covered

### 1. Introduction to Machine Learning
- Difference between traditional programming and ML
- Types of learning: supervised, unsupervised, semi-supervised
- The bias-variance tradeoff
- Overfitting and underfitting

### 2. Supervised Learning Algorithms
- **Linear Regression**
  - Healthcare application: predicting hospital length of stay
  - Interpreting coefficients
  
- **Logistic Regression**
  - Healthcare application: disease diagnosis
  - Odds ratios and probability
  
- **Decision Trees and Random Forests**
  - Healthcare application: clinical decision support
  - Interpretability advantages
  
- **Support Vector Machines (SVM)**
  - Healthcare application: classification of medical images
  
- **Neural Networks**
  - Basic architecture
  - Healthcare application: complex pattern recognition

### 3. Unsupervised Learning Algorithms
- **Clustering (K-means, Hierarchical)**
  - Patient stratification
  - Disease subtype identification
  
- **Dimensionality Reduction (PCA)**
  - Feature extraction from high-dimensional data
  - Genomic data analysis
  
- **Anomaly Detection**
  - Detecting unusual patient conditions
  - Fraud detection in healthcare billing

### 4. Healthcare Data Types
- **Structured Data**
  - Electronic health records (EHR)
  - Laboratory results
  - Vital signs
  - Claims data
  
- **Unstructured Data**
  - Clinical notes
  - Medical images (X-ray, CT, MRI)
  - Pathology slides
  - Genomic sequences
  
- **Time-Series Data**
  - Continuous monitoring data
  - ICU patient data
  - Wearable device data

### 5. The ML Pipeline for Healthcare
1. **Problem Definition**
   - Define clinical question
   - Identify success metrics
   
2. **Data Collection and Preprocessing**
   - Data gathering from multiple sources
   - Handling missing data
   - Data normalization and standardization
   - Dealing with imbalanced datasets
   
3. **Feature Engineering**
   - Selecting relevant features
   - Creating derived features
   - Domain knowledge integration
   
4. **Model Selection and Training**
   - Choosing appropriate algorithm
   - Cross-validation
   - Hyperparameter tuning
   
5. **Model Evaluation**
   - Accuracy, precision, recall, F1-score
   - ROC curves and AUC
   - Confusion matrices
   - Clinical validation
   
6. **Deployment and Monitoring**
   - Integration into clinical workflows
   - Continuous monitoring
   - Model updating and maintenance

### 6. Special Considerations for Healthcare ML
- **Class Imbalance**
  - Rare disease detection
  - Techniques: SMOTE, class weighting
  
- **Interpretability Requirements**
  - Why black-box models are problematic in healthcare
  - SHAP values and LIME
  
- **Temporal Aspects**
  - Longitudinal patient data
  - Time-to-event prediction
  
- **Multi-modal Data Integration**
  - Combining different data types
  - Late fusion vs. early fusion

### 7. Practical Example: Diabetes Risk Prediction
Step-by-step walkthrough of building a diabetes risk prediction model:
1. Dataset overview
2. Exploratory data analysis
3. Feature selection
4. Model training
5. Evaluation and interpretation

## Hands-On Exercise
Using the provided synthetic patient dataset, students will:
1. Perform exploratory data analysis
2. Build a simple logistic regression model to predict diabetes
3. Evaluate model performance
4. Interpret results

## Required Readings
1. Rajkomar, A., Dean, J., & Kohane, I. (2019). Machine learning in medicine. New England Journal of Medicine, 380(14), 1347-1358.
2. Beam, A. L., & Kohane, I. S. (2018). Big data and machine learning in health care. JAMA, 319(13), 1317-1318.

## Discussion Questions
1. What makes healthcare data unique compared to other domains?
2. Why is interpretability more important in healthcare ML than in other applications?
3. How should we handle missing data in clinical datasets?
4. What are the risks of deploying an ML model that performs well on test data but poorly in clinical practice?

## Assignment
**Programming Assignment**: Diabetes Prediction Model
Using the provided `patients_diabetes.json` dataset:
1. Load and explore the data
2. Preprocess the data (handle missing values, encode categorical variables)
3. Split data into training and testing sets
4. Train a logistic regression model to predict diabetic complications
5. Evaluate your model using appropriate metrics
6. Write a short report (1-2 pages) discussing your findings and model limitations

**Submission**: Python notebook (.ipynb) and written report
**Due**: One week from lecture date
