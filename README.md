# automobile_customer_segmentaion
predicting the cluster of automobile customers



## OVERVIEW
Customer segmentation is the practice of dividing a customer base into groups of individuals that are similar in specific ways relevant to marketing, such as age, gender, interests and spending habits.

Companies employing customer segmentation operate under the fact that every customer is different and that their marketing efforts would be better served if they target specific, smaller groups with messages that those consumers would find relevant and lead them to buy something. Companies also hope to gain a deeper understanding of their customers' preferences and needs with the idea of discovering what each segment finds most valuable to more accurately tailor marketing materials toward that segment.

## DATA
An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4 and P5). After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market.

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy on new markets and have identified 2627 new potential customers.

the goal is to predict the right group of the new customers.

### source:
https://www.kaggle.com/abisheksudarshan/customer-segmentation

### Description 

| col | Description | Type |
| --- | --- | --- |
| ID | Customer ID | string 
| Gender| Customer gender | string 
| Ever_Married | Marital status  | string
| Age| customer age | int
| Graduated | yes/no, gradtuation from college | string
| Profession | customer's profession| string
| Work_Experience | customer work experience in years | float
| Spending_Score | a score of customer spending habbits (Low, Average, High) | string
| Family_Size | number of family members| float
| Var_1 | anonymization feauter| string
| Segmentation (target) | segment to which the customer belongs | string



## TOOLS  
- **Modeling:** scikit-learn 
