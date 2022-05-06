# Car-Customer-Segmentation
**OVERVIEW**

Classification Model for Car buying Customer Segmentation.Predicting the category of customer based on Demographics,spending score,etc.

**DATASET**

The dataset contains information about the customers who have bought the car and the organisation has divided in 4 categories A,B,C and D.The data contains columns as 

ID                 
Gender             
Ever_Married       
Age                
Graduated          
Profession         
Work_Experience   
Spending_Score    
Family_Size        
Var_1              

**TECHNICAL ASPECT**

1)Cleaning the data by deleting rows that has wrong values,Nan values,deleting the columns which are not essential to segment the customers

2)Visualizing the data using various modules such as Matplotlib and Seaborn.

3)Built models such as Logistic Regression,K-Nearest Neighbor,Naive Bayes,Decision Tree,Random Forest,Gradient Boosting and XG Boost.Also evaluated each model using AUROC score, to choose among them the best model.

Finally,done the feature importance of the best model.

**RESULT**

Age,Graduated,Work Experience and Var 1 are the most important feature to divide the customers in various segments.

**TECHNOLOGIES USED**

Pandas

Google Colab Notebook

Matplotlib

Seaborn

Sckit-Learn
