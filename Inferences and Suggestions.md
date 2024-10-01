Objectives:
1. EDA to find out customer behaviour
2. Clustering to find out different customer segments
3. Suggesting strategies to improve customer experience bases on these segments

EDA Key Insights:
1. Large proportion of customers have low balances and low purchasing activities. However, a small subset of customers shows higher engagement, either through purchases or cash advances.
2. Credit limits and payment behaviors are skewed towards smaller values, with a few customers having high limits and making large payments.
3. Many customers are frequent in maintaining balance and don’t frequently make one-off purchases or installment purchases, though a few high-frequency users are present.
4. Purchases frequency are widespread and peak around 0 and 1, which means many customers are frequent and about similar number are not.
5. Most customers are associated with bank for a longer time (12 periods).
6. Customers who make purchases tend to make more one-off purchases (0.88), followed by installment purchses (0.68).
7. Balance is somewhat correlated to cash advances (0.55), credit limit (0.52) and minimum payments (0.58). However, cash advances, credit limit and minimum payments have weak correlation with each other.
8. Most customers maintain low balances and have low cash advances, low credit limits and low minimum payments and also make low purchases.

CLUSTERING:
K-means Insights:
PCA applied data gives better clustering with key insights as:
1. Customers who refrain from making much purchases, prefer cash advances, have decent balance values and moderate credit limit.
2. Customers with highest purchases, credit limit and decent balance values.
3. Customers with moderate values of balance, purchases, credit limit and payments.
4. Customers with highest balance and cash advances, high credit limit but less purchases.
5. Customers with low values everywhere.
Overall:
1. High Category (Rich): Cluster 2, Cluster 4
2. Moderate Category (Upper Middle Class): Cluster 1, Cluster 3
3. Low Category (Middle Class): Cluster 5


Hierarichal Clustering Insights:
1. Customers having high credit limits, high balance values, heavily do cash advances but make little purchases.
2. Customers having highest credit limits and make purchases heavily.
3. Customers having low values of balance, purchases and credit limit.
4. Customers who purchase decently, have decent credit limit but do not prefer cash advances.
Overall:
1. High Category (Rich): Cluster 1, Cluster 2
2. Moderate Category (Upper Middle Class): Cluster 4
3. Low Category (Middle Class): Cluster 3


CONSIDERING K-MEANS CLUSTERING IS MOST PRACTICAL AMONG THE THREE, HERE ARE SUGGESTIONS FOR DIFFERENT CUSTOMER SEGMENTS:
1. Educate customers to get closer touch with the credit card by providing budgeting and using cash advances resources. Use promotions that allow them to earn rewards for regular purchases, so they do not look at the card as just an availability of taking cash advances.
2. For heavy users-the efforts of the firm need to be directed at intensifying their experience and involvement through loyalty programs such that they would ask for more purchases. Premium services and promotion will help maintain motivation and satisfaction levels.
3. To the middle transactional customers, it is proposing bespoke financial management tools that will assist in tracking their expenditure and setting savings goals. Gradually increasing credit limits coupled with targeted promotions encourage the customer to use more frequently while still being supported to become a mainstream spender.
4. Promote the solution of cash management along with a knowledge bank emphasizing the use of their credit facility for high-value transactions, not cash advances. Offers for large purchases encourage them to utilize this available high credit to a much greater extent while retaining their flexibility.
5. Educate through workshops on personal finance and streamlined credit products with moderate limits. Keep frequent usage by giving a rewards program that recognizes even minor purchases for their effort to grow in using credit.
