## About the project
This project develops a Machine Learning model to predict whether a loan application should be approved or not, based on applicant details. The system helps financial institutions streamline the loan approval process by automating decision-making.

### Technologies Used
•	Python
•	Pandas
•	Matplotlib, Seaborn
•	Scikit-learn (Logistic Regression, Decision Tree)
•	Jupyter Notebook

### Project Workflow
1. Data Collection & Preprocessing
•	Loaded loan dataset
•	Handled missing values
•	Converted categorical variables into numerical (Label Encoding)
•	Feature scaling where required
2. Exploratory Data Analysis (EDA)
•	Analyzed distributions of applicants’ income, loan amount, and credit history
•	Visualized relationships between applicant features and loan status
•	Compared approval rates across gender, marital status, and employment status
3. Model Building
•	Trained multiple machine learning models (Logistic Regression, Decision Tree)
•	Applied train-test split for evaluation
•	Tuned hyperparameters for better accuracy
4. Model Evaluation
•	Compared models using accuracy, precision, recall, and F1-score
•	Selected the best-performing model for final prediction

### Key Insights
•	Credit history plays the most important role in loan approval.
•	Applicants with higher income and lower loan amounts have better chances of approval.
•	Logistic Regression outperformed Decision Tree in terms of accuracy, making it the preferred model for this dataset.

