# Student Engagement Churn (Data Analysis + Machine Learning)

## 📊 Project Overview 

This project focuses on analyzing student churn for the Excelerate company by leveraging data analytics techniques such as exploratory data analysis (EDA), data visualization, and hypothesis testing. It also incorporates AI models, including machine learning and deep learning, to provide actionable recommendations for reducing churn.


## 🗂 Repository Structure
```plaintext
├── Week 1 - Data Cleaning and Validation
│   ├── AI_internship_Week1.csv
│   ├── Week 1 Code.ipynb
│   ├── Week 1 Report.pdf
├── Week 2 - Exploratory Data Analysis
│   ├── Week 2 Code.ipynb
│   ├── Week 2 Report.pdf
├── Week 3 - Churn Analysis and Predictive Modeling
│   ├── Week 3 Code Module 1.ipynb
│   ├── Week 3 Code Module 2.ipynb
│   ├── Week 3 Dataset.csv
│   ├── Week 3 Report.pdf
├── Week 4 - Recommendations & Presentation
│   ├── Evaluation.docx
│   ├── Team Presentation Slides.pptx
│   ├── Week 4 Code.py
└── README.md
```

## 👥 Team Members
- Abdullah Imran - Technical Guide (main)
- Matthew Ojo
- Krishin Tharani - Technical Guide
- Emani Likhita
- Sangeeta Sahoo
- John Syllah
- Tracy Reson
- Afra Falakh

---

## 📈 Week 1: Data Cleaning and Feature Engineering
### Overview
In the first week, we focused on refining the raw dataset to make it analysis-ready. This involved handling missing values, removing duplicates, fixing formatting issues, and standardizing data types. We also applied feature engineering techniques to uncover valuable insights from the existing data, setting a strong foundation for the next steps.

### Key Steps
- **Data Cleaning**:
  - Addressed missing values using imputation techniques.
  - Removed unnecessary columns and standardized data types.
  - Validated entries for accuracy, including dates, numerical fields, and categorical data.
- **Feature Engineering**:
  - Created new features such as "Age of Learner," "Engagement Duration," and "Time Since Last Engagement."
  - Implemented one-hot encoding for categorical variables.
  - Normalized engagement-related metrics to prepare for modeling.

### Tools & Libraries
- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook

---

## 🔍 Week 2: Exploratory Data Analysis (EDA)
### Overview
In the second week, we delved into Exploratory Data Analysis (EDA) to uncover patterns and insights in the cleaned dataset. This step was crucial for generating hypotheses and identifying key features to use in predictive modeling.

### Key Analyses
- **Demographic Insights**:
  - Analyzed learner demographics like age, gender, and engagement patterns.
  - Identified high engagement among specific age groups (18-28 years).
- **Temporal Trends**:
  - Seasonal analysis of engagement scores, sign-up trends, and engagement duration.
  - Observed peak engagement in specific months (e.g., July) and days (e.g., Thursday).
- **Advanced Visualizations**:
  - Generated correlation heatmaps, PCA plots, and clustering (K-Means) to identify underlying data structures.
  - Conducted cohort analysis to track engagement over time.

### Tools & Libraries
- Python (NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn)


---

## 📊 Week 3: Churn Analysis & Predictive Modeling
### Overview
In week three, our focus was on building a robust predictive model to identify students at risk of churn. This involved analyzing key factors contributing to student drop-offs and developing a model designed to predict churn with a high level of accuracy.

### Key Steps
- **Data Preparation**:
  - Created new engagement metrics and defined churn indicators based on engagement duration, frequency, and inactivity.
  - Labeled students as "churned" or "non-churned" based on thresholds derived from EDA insights.
- **Model Training**:
  - Trained multiple models: Logistic Regression, Decision Tree, Random Forest, SVM, K-Nearest Neighbor, and Artificial Neural Networks (ANN), Recurrent Neural Networks (RNN), Autoencoder, and Multilayer perceptron.
  - In the trial method, before implementation, we achieved the best results with an ensemble Voting Classifier, yielding 98% accuracy.
- **Model Evaluation**:
  - Evaluated models using metrics such as Precision, Recall, F1 Score, and Confusion Matrix.
  - The ANN model demonstrated high predictive power for complex engagement patterns.

### Tools & Libraries
- Python (Scikit-learn, TensorFlow, Keras)
- Google Colab

---

## 📝 Week 4: Recommendations & Strategic Engagement

### Overview
In the final week of our analysis, we focused on crafting targeted strategies to enhance student engagement and minimize churn. Building on insights from earlier analyses, we developed a recommendation system that provides personalized re-engagement tactics, tailored course suggestions, and participation incentives. These strategies aim to improve user retention by delivering customized solutions that meet individual needs.

### Key Strategies Implemented

1. **Personalized Re-Engagement Alerts**
   - **Objective**: To re-engage inactive or low-engagement students.
   - **Approach**: Students with low engagement scores or more than 30 days of inactivity receive automated re-engagement notifications. These alerts are designed to remind them of the value of the platform and encourage them to resume their activities.
   - **Example Recommendation**: "Send re-engagement email"

2. **Targeted Course Suggestions**
   - **Objective**: To increase student engagement by suggesting relevant learning opportunities.
   - **Approach**: For students showing signs of churn or low participation in courses, we recommend popular courses tailored to their interests and past activities. This personalized approach helps in aligning course offerings with student preferences, thereby enhancing their engagement.
   - **Example Recommendation**: "Recommend popular courses based on interests"

3. **Incentivize Participation**
   - **Objective**: To encourage first-time or increased participation in learning opportunities.
   - **Approach**: Students with zero course participation receive incentives like reward points or badges to motivate them to join their first course or activity. This strategy is aimed at fostering initial engagement and encouraging continued participation.
   - **Example Recommendation**: "Offer incentives for first-time participation"


By implementing these personalized strategies, the platform can proactively address student churn, enhance engagement, and foster a more interactive learning environment. The recommendation system serves as a scalable approach to optimize student interactions based on real-time engagement data.

---

## 📊 Key Findings
1. **Top Factors for Churn**:
   - Low Engagement Score
   - Extended inactivity (Days Since Last Engagement > 126 days)
   - Limited Opportunity Participation (< 2 opportunities)
2. **Demographic Trends**:
   - Highest engagement among learners aged 18-28.
   - Significant interest from users in India, Nigeria, and the United States.
3. **Actionable Insights**:
   - Focus outreach on peak sign-up months to maximize engagement.
   - Address gaps in opportunity completion rates to reduce churn.
