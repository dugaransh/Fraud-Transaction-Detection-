# Fraudulent Transaction Detection Model
This project will be split into the following parts:
<ul>
<li>Data Collection and Preparation</li>
<li>Feature Engineering</li>
<li>Model Training and Validation</li>
<li>Hyperparameter Tuning</li>
</ul>

<h3>Data Collection and Preparation</h3>
<ul>
  <li>Dataset includes information such as the transaction amount, the device used to make the transaction, and the country where the transaction was made.</li>
    <li>Goal of this dataset is to develop and evaluate machine learning models for detecting fraudulent transactions.</li>
<li>Analyzed patterns and anomalies in the transaction data to identify potentially fraudulent activity and alert businesses to potential fraud.</li>
<li>Cleaned the dataset using Python libraries</li> </ul>

<h3>Feature Engineering</h3>  <ul>
<li>Used a correlation matrix to identify variables that are linearly related to each other.</li>
<li>Visualized the value counts of the number of fraudulent transactions vs Non-Fraudulent Transactions.</li>
<li>Calculated the Variance Inflation Factor (VIF), a measure of multicollinearity, which occurs when two or more independent variables in a regression model are highly correlated with each other. 
<li>Data scaling (another key step in preparing data for machine learning models). </li>
</ul>

<h4>In this project, we will train and compare the performance of three models — Logistic Regression, Decision Trees, and Gradient Boost — on the preprocessed dataset.</h4>

<h3>Model training and validation process</h3>
<ul>
  <li>Confusion matrix </li>
  <li>Gradient Boost Classifier</li>
  <li>Classification Report</li>
</ul>
For all 3 models.
<h3>Hyperparameter Tuning</h3>
<ul>
  <li>Grid Search
   <ul> <li> Decision Tree</li>
  <li>Logistic Regression</li></ul>
  </li>
  
  <li>Random Search
  <ul>
    <li>Gradient Boost</li> </ul>
  </li>
  <li>Accuracy and F1 score</li>
</ul>


