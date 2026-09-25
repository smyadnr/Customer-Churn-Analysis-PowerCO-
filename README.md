# Customer-Churn-Analysis-PowerCO-
This project is investigated why customers were switching energy providers, testing whether price sensitivity was the main driver of churn.

-Problem~ Question = Can we predict why customers are switching energy providers?

Data
-Source: provided by BCGX / Forage
Client_data.csv
Price_data.csv
-Size:14606 customer records with pricing and usage history

Methods\Tools
-Python(Pandas, numPy, scikit-learn, matplotlib, Seaborn)
-Models: Random Forest Classification

Approach
-Cleaned and explored the data
-Engineered features(creating monthly activities, creating dummies with categorical variables, transforming numerical data logarithm because data has +skewness, creating monthly prices)
- Builted the Random Forest Classification
- Evaluated Results 

Key Results
-Churn is nearly 10% 
-Random Forest Classification achieved 0.90 accuracy.
-Model is correct identifying 3282 staying customers. However, model is not correctly identify 346 churned customers. 

-Net and gross margin on electricity and consumption are the largest drivers of churn over the past 12 months
-Discount may not be the best solution to reduce churn. Customers are not leaving because they are overly priced. 
