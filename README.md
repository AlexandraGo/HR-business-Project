# HR-business-Project

**Employee retention prediction problem:**

Hiring and retaining employees are extremely complex task that require capital, time and skills:

- Companies spend around 15/20% of the employee's salary to recuirt a new canditate.
- Hiring an employee costs an average of $7652 (for a middle size company).
- It takes around 52 days to fill a position.


Therefore, we will try to develop a model that **will predict which employees are more likely to leave the company**. 
For this dataset, firstly we have explored the dataset with some visualization, then we created different models techinques:
 - Random Forest.
 - Logistic Regression.
 - SVM.
 
The main problem encountered in this data set was an **inmbalance** dataset (0:1233,1:237) for our minority class (the one we would like to predict). Working with imbalance dataset can lead to a poor performance.

To overcome this problem we used the techinique SMOTE **Synthetic Minority Oversampling Techinique**. However, at the end there there was not difference between using SMOTE technique. Logistic regression performed the best with the highest AUC, unlike SVM which performed the worst. SVM model has no class separation capacity whatsoever.

  - **Logistic regression AUC: 0.84%**
  - Random Forest AUC: 0.81%
  - SVM AUC: 0.5%

Since our data was imbalace, accuracy was not the best evaluation metric. Therefore, we preferred to used AUC curve for measuring the perfomance of our models. 

To see the whole process please go to: HR_business project.ipynb 

