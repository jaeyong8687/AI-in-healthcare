# Assignment 2: Predictive Modeling for Disease Risk

## Objective
Build and evaluate machine learning models to predict disease risk using patient data, focusing on proper methodology, evaluation, and interpretation.

## Learning Outcomes
- Apply supervised learning algorithms to healthcare data
- Implement proper train-test splitting and cross-validation
- Evaluate models using appropriate healthcare metrics
- Interpret model results in a clinical context
- Address class imbalance in medical datasets

## Dataset
Use the provided datasets:
- `patients_basic.csv` for demographics and vitals
- `lab_results.csv` for laboratory values
- Combine datasets as appropriate for your analysis

## Task
Develop a predictive model for one of the following outcomes:
1. **Diabetes risk prediction** (based on demographics, BMI, lab values)
2. **Hypertension diagnosis** (based on patient characteristics)
3. **Abnormal HbA1c prediction** (HbA1c > 6.5%)

Choose ONE task and build multiple models to compare performance.

## Requirements

### Part 1: Data Preparation (20 points)
1. **Data Integration**
   - Merge relevant datasets
   - Handle missing values (document your strategy)
   - Create derived features if appropriate
   
2. **Feature Engineering**
   - Select relevant features for your prediction task
   - Create new features based on domain knowledge
   - Normalize/standardize features as needed
   
3. **Train-Test Split**
   - Split data into training (70%), validation (15%), and test (15%) sets
   - Ensure no data leakage
   - Document data distribution across splits

### Part 2: Model Development (30 points)
Build and train at least THREE different models:
1. Logistic Regression (baseline)
2. Random Forest
3. Your choice (SVM, Gradient Boosting, Neural Network, etc.)

For each model:
- Document hyperparameters
- Use cross-validation on training set
- Optimize hyperparameters systematically
- Explain your modeling choices

### Part 3: Model Evaluation (25 points)
Evaluate all models using:
1. **Classification Metrics**
   - Accuracy
   - Precision, Recall, F1-score
   - ROC curve and AUC
   - Confusion matrix
   
2. **Clinical Relevance**
   - Discuss false positives vs. false negatives
   - Which metric is most important for your task and why?
   - What threshold would you choose for deployment?
   
3. **Model Comparison**
   - Compare all three models
   - Statistical significance testing (if applicable)
   - Select the best model with justification

### Part 4: Model Interpretation (15 points)
For your best model:
1. Feature importance analysis
2. Identify most predictive features
3. Explain results in clinical terms (not just statistical terms)
4. Discuss any surprising findings

### Part 5: Discussion and Limitations (10 points)
Address the following:
1. Model limitations and potential biases
2. Generalizability to real-world clinical settings
3. Ethical considerations for deployment
4. Recommendations for model improvement
5. Next steps for clinical validation

## Deliverables
1. **Code** (Jupyter notebook or Python script)
   - Clean, well-documented code
   - Reproducible results (set random seeds)
   
2. **Report** (5-7 pages) including:
   - Introduction and problem statement
   - Methodology
   - Results with visualizations
   - Discussion and conclusions
   - References

## Grading Rubric
- Data preparation and feature engineering: 20%
- Model implementation and training: 25%
- Evaluation methodology: 25%
- Interpretation and clinical relevance: 20%
- Report quality and presentation: 10%

## Advanced Options (Bonus Points)
Choose ONE for up to 10 bonus points:
1. **Address Class Imbalance**: Implement SMOTE or other techniques to handle imbalanced classes
2. **Ensemble Methods**: Create a stacked or voting ensemble of your models
3. **Explainable AI**: Use SHAP or LIME to explain individual predictions
4. **External Validation**: Simulate external validation by holding out a hospital/clinic subset

## Common Pitfalls to Avoid
- Data leakage (using test data for preprocessing decisions)
- Ignoring class imbalance
- Overfitting due to small sample size
- Not considering clinical context in metric selection
- Treating missing data inappropriately

## Submission Guidelines
- Submit via course learning management system
- File naming: `LastName_FirstName_Assignment2`
- Include all code, report, and any supplementary materials
- Due date: Three weeks from assignment date

## Resources
- Scikit-learn documentation
- Lecture 2: Machine Learning Fundamentals
- Recommended reading: Rajkomar et al. (2019) on ML in medicine
- Class imbalance tutorial: https://imbalanced-learn.org/

## Academic Integrity
- You may discuss approaches with classmates
- All code and writing must be your own
- Properly cite any external resources or code snippets used
