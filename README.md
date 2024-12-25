# AI-Enabled-FinTech-B2B-Invoice-Management-Application
#Data
-- Understanding data is too important than building a great model, because with out having a great data we can not build a great model.

business code - Product/service code provided by the company
cust_number - Distinguishing teh customer based on the department
name_customer - name of the customer
clear_date - Date the payment was done
business_year - year which the business done
doc_id - id of the document created
posting_date - date of the posting transactions
document_create_date = billing date/ date on the bill
due_in_date - due data to pay the amount
invoice_currency - currency in which the payment was made
total_open_amount - Amount prepaid to the seller
baseline_create_date - date till the payment terms will apply
isOpen - If payment was done 1, else 0
#Data Preprocessing
Importing the data
Checking Null values
Creating the target Column
Removing the unwanted columns
Removing the rows with Null values
Setting the date columns
#EDA
-- Used Auto EDA libraries 1) AutoViz 2) Sweet Viz for visualizig the data and geting the insights from the data
-- Converted the columns into log normal distribution which are not normally distributed.

#Feature Engineering
--Created features required for the predictions

Year
Quarter
Month
Week
Day
Expected Delay
#Machine Learning Models
Linear algorithms(linear regression, Lasso, Ridge Regressions, Elastic Net)
Tree Algorithms(Decision Tree, Random Forest)
KNN
Artificial Neural Network
EvalML: An auto ML library
