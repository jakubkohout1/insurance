# US Medical Insurance Cost Analysis
#### *by Jakub Kohout & Kaileb O'Neil*


This [kaggle dataset]([url](https://www.kaggle.com/datasets/mirichoi0218/insurance/data)) records age, sex, BMI, number of children, smoker status and insurance charges and we are assuming all data is from the same insurance company. We decided to pursue two questions in our analysis:
1. What lifestyle choices would minimize our insurance costs?
2. Is there correlation between insurance cost and BMI?

For the first question, we filtered the data to match sex and non-smoking status. Then we calculated mean and median age and BMI by region and by number of children in order to identify any skews or trend in the remaining data that could affect our finding. 
We found no significant data skew and calculated that having zero children and moving to the southeast would optimize our insurance costs.

When investigating the relationship between BMI and insurance cost, we categorized data by their medical BMI category and determined the average insurance cost by BMI category. Then within each BMI category we calculated the percent difference in insurance cost each person pays compared to similar people of all BMI values. In both step of the analysis BMI positively correlated with insurance costs.
Since the value of BMIas as an accurate metric of a patients health is questionable, the strong trends of positive correlation between BMI could indicate poor pricing models and is cause for more investigation.

Let us know your thoughts on our analysis and if you decide to explore any of these questions further.
