# Credit-Risk-Prediction
Credit risk prediction using Loan Prediction dataset. Includes data cleaning, visualization, and classification models (Logistic Regression, Decision Tree) with evaluation using accuracy and confusion matrix.

## Objective
The goal of this project is to predict whether a loan applicant is likely to default on a loan. This classification task helps financial institutions identify high‑risk applicants and make more informed lending decisions.

## Dataset
The project uses the **Loan Prediction Dataset**, which contains 614 rows and 13 columns.  
Key features include:
- Applicant Income  
- Loan Amount  
- Education & Marital Status  
- Credit History  
- Loan Status (Target variable)

## Approach
1. **Data Loading & Inspection**
   - Loaded the dataset using pandas
   - Inspected structure with `.head()`, `.shape`, and `.info()`

2. **Data Cleaning**
   - Handled missing values using the Forward Fill (`ffill`) method
   - Ensured the dataset was complete before modeling

3. **Exploratory Data Analysis (EDA)**
   - Count plots to examine how education impacts loan status
   - Scatter plots to analyze the relationship between applicant income and loan amount

4. **Model Training**
   - Split the dataset into training (80%) and testing (20%) sets
   - Implemented Logistic Regression, a standard algorithm for binary classification

5. **Model Evaluation**
   - Evaluated performance using Accuracy Score
   - Used a Confusion Matrix to assess prediction quality

## Results & Insights
- *Education Effect:* Graduate applicants show a higher frequency of loan approvals compared to Non‑Graduates.  
- *Correlation:* Applicant income is positively correlated with the requested loan amount.  
- *Model Performance:* Logistic Regression achieved an accuracy of *78%*
- **Education Effect:** Graduate applicants show a higher frequency of loan approvals compared to Non‑Graduates.  
- **Correlation:** Applicant income is positively correlated with the requested loan amount.  
- **Model Performance:** Logistic Regression achieved an accuracy of **78%**.
