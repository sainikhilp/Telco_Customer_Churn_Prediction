# Telco_Customer_Churn_Prediction

This project aims at predicting whetehr a customer will continue eith the Telco Service group or not. To classify the customers, the analysis is divided into three stages:
  * Exploratory Data Analysis
  * Cohort Data Analysis
  * Prediction Model (Decision Trees & Random Forests)

# Exploratory Data Analysis

Churn Countplot:
<p align="center">
  <img src="figures/churn_countplot.jpg" >
</p>


Distrubution of TotalCharges between Churn categories:
<p align="center">
  <img src="figures/churn_distrubution.jpg"  >
</p>


Total Charges Vs Contract Type
<p align="center">
  <img src="figures/TotalCharges_VS_Contract_perCategory.jpg" >
</p>


# Churn Analysis:
Tenure Countplot:
<p align="center">
  <img src="figures/tenure_histplot.jpg" >
</p>




Total Charges vs Monthly Charges
<p align="center">
  <img src="figures/TotalCharges_VS_MonthlyCharges.jpg" >
</p>


Churn Percentage vs Tenure
<p align="center">
  <img src="figures/ChurnPercentage_VS_tenure.jpg" >
</p>


Creating Tenure Cohort based on the below conditions:
   * '0-12 Months'
   * '12-24 Months'
   * '24-48 Months'
   * 'Over 48 Months' 

Tenure Cohort
<p align="center">
  <img src="figures/Tenure Cohort.jpg" >
</p>


Tenure Cohort Countplot
<p align="center">
  <img src="figures/Tenure Cohort Countplot.jpg" >
</p>


# Prediction Model

Decision Trees: 
* Confusion Matrix
<p align="center">
  <img src="figures/decisionTree_matrix.jpg" >
</p>


Random Forests:
* Confusion Matrix
<p align="center">
  <img src="figures/rfcmatrix.jpg" >
</p>



# Final Thoughts:
The accuracy of both the models was 80%.
The precision and recall for churn yes and churn no were 53%,42% and 85%,90% respectively.
The imbalance in the churn class could be the main reason for the difference in the precision and recall values for the churn classes.
The performance can be improved by training the model on an improved well balanced data set. 

