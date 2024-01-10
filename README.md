# Welcome to the Personal Project - [EffiDirect: Boosting Direct Marketing Efficiency for Sustainable Investments](https://ayumu0622.github.io/EffiDirect_Boosting_Direct_Marketing_Efficiency_for_Sustainable_Investments/)

## Access this project from [here](https://ayumu0622.github.io/EffiDirect_Boosting_Direct_Marketing_Efficiency_for_Sustainable_Investments/)
Hello! I'm Ayumu Justin Ueda, a Data Science student at UC Berkeley. You can find my profile on (https://www.linkedin.com/in/ayumu-ueda-ab1879224/).

In this project, I'm serving as a data scientist at an investment company, tasked with enhancing the effectiveness of our direct marketing for our new sustainable energy fund. Before joining the company, they attempted to promote a different type of fund to customers. I have been provided with data records detailing each customer's age, job, education, etc., along with whether they purchased those fund through our direct marketing efforts.

## Objective:

The primary objective is to enhance the KPI, specifically the purchasing rate of the sustainable energy fund.

## Project Overview:
### 1. Identifying Customer Attributes Influencing Marketing Engagement (Regression Analysis):

**Skills Applied:**
- Data Analysis
- Logistic Regression Analysis
- Statistical Inference (Z-test)

**Conclusion for this section:**
- Individuals with higher levels of education show a stronger inclination towards investment banking and are more likely to purchase our fund.
- Jobless or retired individuals tend to consider investing for the future, making them a valuable target demographic.
- Singles display a higher interest in investing compared to divorced individuals.
- Participants from previous marketing efforts are likely to engage in future campaigns.
- It's advisable to limit the number of phone calls to 4 to 5 times, as beyond this point, the likelihood of making a purchase significantly decreases.

**Suggestions:**

Target individuals with higher education, retirees, and singles for phone calls. Prioritize those who engaged in previous marketing. Exercise caution, ensuring the number of contacts remains below 5, unless specific reasons dictate otherwise. This is crucial, as 95% of customer decided to purchase within 4 attempts.


### 2. Predicting the Likelihood of Marketing Engagement (Machine Learning Modeling):

**Skills Applied:**
- Data preprocessing
- Machine learning modeling for binary classification
- Hyperparameter tuning with Optuna
- Model interpretation

**Conclusion for this section:**

- In the test dataset, our initial approach involved making phone calls to 1569 people, resulting in 367 purchases. With the integration of this model for predictive analysis prior to calling, we only needed to reach out to 288 individuals, and 194 of them made a purchase. This led to a remarkable 80% reduction in our efforts.

- The LightGBM classifier, when applied to the test data, successfully pinpointed 53% of individuals who purchased. Following this identification, a 67% purchase rate was observed.

- Recognize the potential for a 47% loss in sales opportunities.


**Suggestions:**
- If minimizing the risk of losing potential customers is a top priority, reconsider using this model. However, if our marketing strategy involves multiple channels, and phone direct marketing is just one component, integrating this model can help trim down inefficiencies in phone calls. The resources saved can then be redirected to other channels, optimizing our overall marketing strategy.
