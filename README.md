# -Mentorness-Intern-Customer-Churn-Prediction
To predict customer churn. We will follow these key steps:
1. Exploratory Data Analysis (EDA): Dive into the dataset, conduct comprehensive EDA, and unveil
valuable insights about customer behaviors. EDA will involve data visualization, summary
statistics, and identifying patterns in the data.
2. Feature Engineering: If requires create new features or transform existing ones that can provide
additional insights or improve model performance. Feature engineering might involve
aggregating information, creating interaction terms, or applying domain-specific knowledge.
3. Data Preprocessing: Prepare the data for model training. This includes handling missing values,
encoding categorical variables, and scaling or normalizing features as needed.
4. Machine Learning Model Development: Train various machine learning models for
classification, such as logistic regression, decision trees, random forests, Boosting Algorithms.
Experiment with different algorithms to find the best-performing model.
5. Model Evaluation: Assess the performance of your models using appropriate evaluation metrics
like accuracy, precision, recall, F1-score, confusion matrix and ROC AUC. Identify the model that
provides the most accurate predictions of customer churn.
6. Predicting Churn: Once you've built and validated your model, use it to predict customer churn.
Understand the importance of feature importance scores in interpreting the model's
predictions.
7. Recommendations: Based on your findings, provide actionable recommendations to the
business. These recommendations should help reduce churn and improve customer retention
strategies.

Dataset Overview:
The dataset contains the following columns:
 `customerID`: Customer ID
 `gender`: Customer's gender
 `SeniorCitizen`: Whether the customer is a senior citizen (1 for yes, 0 for no)
 `Partner`: Whether the customer has a partner
 `Dependents`: Whether the customer has dependents
 `tenure`: Number of months the customer has stayed with the company
 `PhoneService`: Whether the customer has phone service
 `MultipleLines`: Whether the customer has multiple phone lines
 `InternetService`: Type of internet service
 `OnlineSecurity`: Whether the customer has online security
 `OnlineBackup`: Whether the customer has online backup
 `DeviceProtection`: Whether the customer has device protection
 `TechSupport`: Whether the customer has tech support
 `StreamingTV`: Whether the customer streams TV
 `StreamingMovies`: Whether the customer streams movies
 `Contract`: Type of contract (e.g., month-to-month, one year, two years)
 `PaperlessBilling`: Whether the customer uses paperless billing
 `PaymentMethod`: Payment method (e.g., electronic check, mailed check)
 `MonthlyCharges`: Monthly charges
 `TotalCharges`: Total charges
 `Churn`: Target variable, indicating whether the customer churned (1 for yes, 0 for no)
