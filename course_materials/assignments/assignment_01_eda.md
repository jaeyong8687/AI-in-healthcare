# Assignment 1: Exploratory Data Analysis of Healthcare Data

## Objective
Perform comprehensive exploratory data analysis (EDA) on synthetic patient datasets to understand patterns, relationships, and potential issues in healthcare data.

## Learning Outcomes
- Practice data loading and manipulation in Python/R
- Create meaningful visualizations of healthcare data
- Identify data quality issues
- Generate hypotheses about patient outcomes
- Communicate findings effectively

## Dataset
Use the provided synthetic patient datasets:
- `patients_basic.csv` - Basic demographics and vitals
- `patients_diabetes.json` - Detailed diabetes patient records
- `lab_results.csv` - Laboratory test results

## Requirements

### Part 1: Data Loading and Initial Exploration (20 points)
1. Load all three datasets
2. Display basic statistics (mean, median, std, etc.)
3. Check for missing values
4. Identify data types of each column
5. Document the number of patients and observations

### Part 2: Univariate Analysis (20 points)
Create visualizations and analyze:
1. Age distribution of patients
2. Gender distribution
3. BMI distribution and categories (underweight, normal, overweight, obese)
4. Blood pressure distribution
5. Distribution of primary diagnoses

### Part 3: Bivariate Analysis (25 points)
Explore relationships between variables:
1. Age vs. BMI
2. Age vs. Blood Pressure
3. BMI vs. Diabetes diagnosis
4. Gender differences in key health metrics
5. Correlation heatmap of continuous variables

### Part 4: Lab Results Analysis (20 points)
1. Analyze abnormal lab result patterns
2. Compare lab values between different patient groups
3. Identify patients with multiple abnormal results
4. Visualize trends in key lab markers

### Part 5: Insights and Recommendations (15 points)
Write a summary including:
1. Key findings from your analysis
2. Potential risk factors identified
3. Data quality issues observed
4. Recommendations for further analysis or data collection
5. Limitations of the current dataset

## Deliverables
1. Jupyter notebook or R Markdown file with:
   - Well-commented code
   - Clear visualizations
   - Interpretations of findings
2. PDF report (3-4 pages) summarizing key insights

## Grading Rubric
- Code quality and documentation: 20%
- Visualization quality and appropriateness: 25%
- Statistical analysis correctness: 25%
- Insights and interpretation: 20%
- Report clarity and presentation: 10%

## Tips
- Use appropriate chart types for different data types
- Include proper labels, titles, and legends
- Choose color schemes carefully (consider colorblind-friendly palettes)
- Document any assumptions you make
- Consider the clinical relevance of your findings

## Submission
- Submit via course learning management system
- File naming: `LastName_FirstName_Assignment1`
- Due date: Two weeks from assignment date

## Resources
- Pandas documentation: https://pandas.pydata.org/docs/
- Matplotlib/Seaborn for visualization
- Lecture 2 materials on healthcare data types
