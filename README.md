# HR-business-Project

**Employee retention prediction problem:**

Hiring and retaining employees are extremely complex task that require capital, time and skills:

- Companies spend around 15/20% of the employee's salary to recuirt a new canditate.
- Hiring an employee costs an average of $7652 (for a middle size company).
- It takes around 52 days to fill a position.


Therefore, we will try to develop a model that **could predict which employees are more likely to leave the company**. 
For this dataset, firstly we have explored the dataset with some visualization, then we created different models techinques:
 - Random Forest (This model has performed the best).
 - Logistic Regression.
 - SVM.
 
The main problem encountered in this data set was an **inmbalance** dataset. For this we used the techinique SMOTE. However, at the end there there was not difference between using SMOTE teqhnique. Logistic regression had the highest AUC, unlike SVM which performed the worst.
Since our data was imbalace, accuracy was not the best evaluation metric. Thefore, we preferred to used AUC curve for measuring the perfomance of our models. 

