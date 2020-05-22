# LendingClub
1.Introduction:
 the most important issue for lending company will decide who can be clients as borrowers with lower risk of default. Finding a way to decrease default rate is important. For this, we need to identify which factors or traits will be the potential risk. Therefore, analysis of income, credit rating, the purpose of lending money, etc. of current customers will be useful for selecting good potential customers. Because we can adapt that current customers’ traits to people who want to be borrowers. It means we can predict potential customers who would be fully paid or defaulted. Based on this, lending company can get insight to decrease risk and hold more profit.
To predict who will be the good customers, we use the data from Sourceone. 

2.Business Questions:
To recognize what kinds of people and group will pay back well, we need to distinct the traits of them. For this, we will make some business question based on 3 keywords; 1) credit rate 2) default 3) income. Firstly, for getting good customers in the future we need to figure out what factors that affect the credit rating greatly. 
Next, analysis of gap between a group who are fully paid and the other group who are defaulted will be helpful question to avoid risk of delinquency. Besides, it will be helpful to make a standard which can judge whether new customers’ ability and conditions are qualified or not.
Lastly, loan status will be highly linked with income so check that the amount of income and the income frequency will be meaningful.

3.Analysis

Data preprocessing:

1.	 Data Cleaning: Refine the data through such processes as filling missing values, mitigating noise, detecting abnormalities, removing, and resolving discrepancies.
2.	Data Integration : organize data through relational data modeling. Integrate schemas and respond to objects.
3.	Data Reduction :  Increase data density by eliminating low-relational or redundant data attributes and eliminating Multicollinearity.
4.	Data Transformation: To maximize the efficiency of algorithms, data is manipulated to give arbitrary deformation. Normalize and encode as needed.

Modeling:

1.	exploratory data analysis (EDA): Develop a model after fully understanding the data through exploratory data analysis
2.	Modeling/validate: Develop and validate models for troubleshooting.
3.	Deploy: deploy the model and Evaluate


4.discuss(problem):
For a better analysis, first we need more data to predict the loan status. Considering that the cycle of car loans is over a decade, data from the current three years or so is absolutely lacking in data to predict whether go default or not. Therefore, in order to achieve significant accuracy, a history of lending behavior, at least more than one loan cycle, is needed.

