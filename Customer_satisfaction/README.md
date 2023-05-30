## Determine the customer satisfaction level using Gaussian Mixture Model (GMM)

The dataset is based on customer data at a Supermarket. The dataset and its description are as follows:
•	ID - Unique identifier of each customer 
•	Sex – 0:male, 1:female
•	Marital status - 0: single, 1: non-single
•	Age – Age in years
•	Education - 0: other/unknown, 1: high school, 2: university, 3: graduate school
•	Income - annual income in USD
•	Occupation - 0: unemployed/unskilled, 1: skilled employee/official, 2: management/self-employed/highly qualified employed/officer
•	Settlement size - 0: small city, 1: mid-sized city, 2: big city

Here, our goal is to determine the customer satisfaction based on the details provided and accordingly provide the target customers to the marketing team to devise a strategy further. Since our aim is to assign similar customers to a cluster, we will apply the Gaussian Mixture Model which is a type of unsupervised learning and hence we do not have a target variable in this case. 
