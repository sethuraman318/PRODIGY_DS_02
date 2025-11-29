PRODIGY_DS_02 – Task 2: Titanic Survival Analysis (EDA)


📌 Objective
The goal of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors influencing passenger survival.
The dataset contains demographic, travel, and survival information for passengers aboard the RMS Titanic.

This analysis focuses on uncovering survival patterns based on:

Gender

Passenger class

Age

Fare

Family size

Embarkation port

Missing value distribution

Correlations between numerical features


📊 Visualizations Created
1️⃣ Survival Count Plot

Shows the overall distribution of passengers who survived vs those who did not.
Helps understand class imbalance in survival outcomes.
📁 File: survival_counts.png

2️⃣ Missing Values Heatmap

Highlights missing data in columns such as Age and Cabin.
Useful for understanding data quality and planning preprocessing.
📁 File: missing_values_heatmap.png

3️⃣ Survival Rate by Gender

Reveals that female passengers had significantly higher survival rates than males.
Gender is one of the strongest predictors of survival.
📁 File: survival_by_gender.png

4️⃣ Survival Rate by Passenger Class

Shows that 1st class passengers survived more, followed by 2nd and then 3rd class.
Indicates strong impact of socio-economic status.
📁 File: survival_by_class.png

5️⃣ Correlation Heatmap (Numerical Features)

Displays correlations between numerical variables such as Age, Fare, SibSp, and Parch.
Useful for understanding feature relationships.
📁 File: correlation_heatmap.png

Additional Visualizations (Optional)

(If included in your repo, they are also valid EDA visuals.)

6️⃣ Distribution of Age

Shows age distribution of passengers and highlights younger groups.
📁 age_distribution.png (if included)

7️⃣ Distribution of Fare

Shows skewness in fare pricing.
📁 fare_distribution.png (if included)

8️⃣ Distribution of Family Size

Shows how many passengers traveled alone vs in families.
📁 family_size_distribution.png (if included)



📂 Files Included
File Name	Description
Task2_Titanic_EDA.ipynb	Full EDA code for data analysis & visualizations
survival_counts.png	Survivors vs non-survivors chart
missing_values_heatmap.png	Visual representation of missing data
survival_by_gender.png	Gender-wise survival comparison
survival_by_class.png	Survival rate based on class
correlation_heatmap.png	Heatmap of numerical correlations
(Optional additional plots)	Age, Fare, Family Size distributions


📝 Conclusion

From the Titanic EDA:

Females had a much higher survival rate than males

1st class passengers survived the most, highlighting socio-economic impact

Age and Fare show useful patterns, with younger passengers having slightly better survival rates

Cabin data contains heavy missing values, reducing its analytical value

Survival distribution is imbalanced, with more people not surviving

Family size and embarkation port also influence survival trends

This task demonstrates how Exploratory Data Analysis helps uncover meaningful patterns and relationships within real-world datasets.


👨‍💻 Author

Sethuraman Shanmugasundaram
Data Science Intern – Prodigy InfoTech
