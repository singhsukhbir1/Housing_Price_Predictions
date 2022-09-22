# Square: Sukhbir Singh (Managing GitHub Repository)

---
---

# Circle: Jagbir Singh (incharge of the mockup database)


---
---
# X: Chenglu Yang(Deciding the technologies)
---
---

---
---
# Triangle:  Nishan Manoharan ( Building Machine Learning Models )
---
---

## Building Machine Learning Models: 
	
## Shallow Learning: 
- It would be a good idea to start the Machine Learning component by examining a simpler rule-based algorithm 
  
-    We can predict our response variable, by using the following regressors: Linear Regressor, DecisionTreeRegressor & RandomForest Regressor 

-	Based off of our understanding, my belief is that Random Forest will produce the best results as it is the ensemble of Decision Trees. Ensemble models in general produce better results than singular models 

---

### Linear Regression: 
---
#### Advantages: 

(1) Simple to Implement: 

- it is less complex in comparison to other algorithms when you are knowing the relationship between the dependent and independent variable 

(2) Performance on linearly seperable datasets: 

(3) We can reduce overfitting 

- Using Dimensionality Reduction Techniques
- Regularization Techniques
- Cross-Validation 


#### Disadvantages: 

(1) Prone to Underfitting:

- has difficulty with complex datasets and poor-quality data 
- must have proper pre-processing performed on the data prior to analyzing 


(2) Sensitive to outliers:

- if there are more than a few outliers in comparison to non-outliers it can skew the true relationship

(3) Assumes Linearity:

- linear relationship between dependent and independent variables is considered to be a straight-line relationship 
- assumes independence between attributes


---
### Multiple Regression: (more than one independent variable) 
---

#### Advantages: 


(1) the ability to determine the relative influence of one or more predictor variables to the target variable

- example: the size of home and number of bedrooms have a strong correlation to the price of the home, while proximity to school has no correlation at all 

(2) Ability to find Outliers: 

(3) Broader Type of Regression: 

- it can handle straight line and non-linear regression with multiple explanatory variables 


#### Disadvantages: 

(1) Sensitive to the Data being used 

- Incomplete/Minimal/Error data can lead to the conclusion that a correlation is a causation 

![LRvsMLR](https://i.ibb.co/55vj4ym/SLR-vs-MLR.png)


---
### Decision Trees
---
 
#### Advantages: 

(1) Easy to Interpret: 

- the hierarchical decision-making process allows for the reader to understand which attributes are most important

(2) We barely require data, as it can handle a variety of data types:

- Discrete 
- Continuous 
- Continuous variables converted into Categorical values

(3) Flexible:

- can be used for classification and regression tasks. 
- even if attributes are or are not closely related, as the algorithm will make one of two choices. 

#### Disadvantages:

(1) Prone to Overfitting:

- The more complex the decision tree is the more likely it will overfit 

(2) High Variance Estimators:

- small variations within our attributes can lead to a completely different tree 

(3) Costly:

- they can be more costly to train in comparison to other algorithms 

---
### Random Forest Regressor: 
---

#### Advantages:

(1) Minimalizes the Overfitting: 
- in decision trees overfitting was a disadvantage, however by  reducing this we can help improve the accuracy 

(2) Data Cleaning is reduced
- we can automate missing values in the dataset we have 
- we do not need to normalize our as it follows a rule-based approach 

#### Disadvantages: 

(1) Power and Resources:
- we need strong computational power, as it builds numerous trees and combines their outputs 

(2) Time Consuming:
- due to combining a lot of decision trees we would need a more time for training 

![SDTvsRF](https://i.ibb.co/0mZJkTW/DT-vs-RF.png)

---
---


---
---

X: 

---
---
