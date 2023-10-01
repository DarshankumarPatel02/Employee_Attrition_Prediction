# Employee_Attrition_Prediction

1. Problem Statement
“Employee Attrition Prediction”
2. Dataset Description
The IBM HR Analytics Employee Attrition & Performance dataset is a fictional dataset consisting of employee records of a large corporation. The dataset includes 1,470 employee records and 35 attributes.

   ![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/1.png)

   ![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/2.png)

3. Dataset Analysis and Observations
Key Points:-
1.	JobLevel is highly related to Age as expected as aged employees will generally tend to occupy higher positions in the company.
2.	MonthlyIncome is very strongly related to joblevel as expected as senior employees will definately earn more.
3.	Also note that TotalWorkingYears is highly related to JobLevel which is expected as senior employees must have worked for a larger span of time.
4.	YearsWithCurrManager has a strong relationship with YearsAtCompany.
5.	YearsAtCompany is related to YearsInCurrentRole.
Key Note: - The number of observations in the 'No' category is far bigger than the number of observations in the 'Yes' category. As a result, we get skewed classes, which is a common example of the "Imbalanced Classification Problem." To deal with such difficulties, we must employ over-sampling or under-sampling strategies.

    ![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/3.png)
  	![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/4.png)
  	

    
4. Proposed Analytical/Prediction Model
•	we have trained Decision Tree because it is the most basic model for predicting data and then we used Random Forest Regression Model because it gives most accurate prediction and good accuracy through cross validation. Moreover, we have also used artificial neural network i.e., ANN to compare it with Random Forest.
5. Results and Discussions
   
  ![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/5.png)
  ![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/6.png) 
  ![](https://github.com/DarshankumarPatel02/Employee_Attrition_Prediction/blob/master/Photo/7.png)
