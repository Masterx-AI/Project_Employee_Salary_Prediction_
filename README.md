# AI/ML Project: Employee Salary Prediction 💰
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/142728318-56642c69-2780-4b9d-9a84-618007198a9f.jpg" style="width: 1000px;"/></p>

### Description:

The data consists of Salaries of Employees, including their gender, age & phD degree. The dataset is downloaded from UCI Machine Learning Repository.

**Properties of the Dataset:** \
Number of Instances: 100\
Number of Attributes: 4 including the class attribute

The dataset is simple yet challenging as it is has very limited features & samples. Can you build regression model to catpture all the patterns in the dataset, also maitaining the generalisability of the model?


### Objective:
- Understand the Dataset & perform the necessary cleanup.
- Build Regression models & fine-tune the hyperparamters to predict the emplyee salaries.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### Strategis Plan of Action:
We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/142728573-42c6ca90-a4ce-43b6-9064-35cffa98dc58.png" /></p>

**2. Categorical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141452423-0e224fe0-5a77-47f0-a520-1c0f309c5bd2.png)
![image](https://user-images.githubusercontent.com/54996245/141452437-439ae079-c205-426a-8ce1-817903a0e4ed.png)

**2. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141452518-c6b8c924-7f7e-4559-9746-9032730beb1e.png)
![image](https://user-images.githubusercontent.com/54996245/141452527-8d38e9d7-a43d-4211-b6ad-0748bcad18f3.png)


**3. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/141452553-e0943047-6571-4424-85e9-71e37f2517b0.png)

**4. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/141452578-d128bca3-a189-48f5-985b-95c1a1363985.png)

**5. Correlation Plot**

![image](https://user-images.githubusercontent.com/54996245/141452606-6b0cd1db-9006-45ca-9661-498817c9c025.png)

**7. Multiple Linear Regression Prediction & Residual Normality Check**

![image](https://user-images.githubusercontent.com/54996245/141452683-7a0a0f1f-ad61-42d2-8431-4e814740ae63.png)

**8. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/141452789-9216bc4b-c590-4bdc-8590-85bf8e0cf6d7.png)

**9. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/141452832-ce98cc99-f3bc-48d6-b6d2-387d484e323c.png)
![image](https://user-images.githubusercontent.com/54996245/141452866-26fe2f8c-0a95-4b15-9774-102786357dde.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 100 samples & after preprocessing 1% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had some multicollinearity, but since we had only 4 features, we did not perform any feature selection/extraction.
- Testing multiple algorithms with hyperparamter-tuning gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-2) gave the best overall scores for the current dataset, yet it wise to also consider simpler models like MLR & ENR as they are more generalisable.
