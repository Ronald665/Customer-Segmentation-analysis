# Customer Personality Analysis: Clustering for Segmentation & Insight

## Project Overview
Understanding customers and their behaviors is critical for any business that aims to improve marketing performance, strengthen loyalty, and drive sales growth. The purpose of this project was to analyze customer data and identify distinct groups based on shared demographic, behavioral, and financial characteristics.

Using PCA(Principal component analysis) and K-Means clustering algorithm, I segmented the customer base into four meaningful groups. Each cluster represents customers who exhibit similar purchasing patterns, income levels, and lifestyle traits. The insights derived from these clusters help the company better target its marketing campaigns, allocate resources efficiently, and tailor engagement strategies to different customer needs.

<img width="350" height="347" alt="clusters" src="https://github.com/user-attachments/assets/ff519d92-e78a-4c4b-807e-ca84538e9d91" />
<img width="400" height="348" alt="k plot" src="https://github.com/user-attachments/assets/2d3794c2-a97c-4cb4-9236-4f34ba351859" />


The dataset included information on income, age, marital and parental status, education, household size, product purchases (wine, meat, fruits, fish, sweets, and gold), and various shopping behaviors (online, in-store, catalog, and deal purchases) on more than 2000 customers
<p align="center">
  <img src="https://github.com/user-attachments/assets/ee4a9944-e7d8-451f-a2e2-f0f62d43840f" alt="distribution" width="356" height="356" />
</p>

## Key Findings

### A) Cluster Discovery and Interpretation
After analyzing the data, four customer clusters emerged, each representing a unique market segment. These clusters varied across income, family composition, education, loyalty, and spending patterns.

#### Cluster 0: Premium Loyalists (High Income, High Spending Customers)
Cluster 0 represents the company’s most financially powerful and valuable segment. With the highest median income (approximately $76,000), they display strong purchasing capacity and consistent engagement across multiple product categories. These customers prefer premium items such as wine, meat, and gold, indicating a taste for luxury and quality.
They are primarily well educated professionals, often single or living in small households without children. Despite not being the most long-term customers, they spend the most overall, suggesting strong engagement when active.

Cluster 0 members frequently make purchases in store and via catalog, with moderate online activity. They’re less price sensitive and more experience driven, making them ideal for exclusive loyalty programs, premium product launches, and personalized campaigns.

#### Cluster 1: Family Oriented Bargain Seekers (Large Families, Low Loyalty)
Cluster 1 primarily includes parents with large households the biggest family size across all clusters. They have a below average median income (~$44,000) and are the least loyal segment, often switching brands or services in search of better deals.
Their spending patterns show a clear price sensitivity. They spend very little on luxury products such as wine, meat, or gold and are much more responsive to discounts and promotions. This behavior suggests they are motivated by value for money, making them suitable targets for family discounts, bundle deals, and seasonal campaigns.

In terms of lifestyle, most customers in this cluster are married or in relationships, reinforcing the idea of a stable, family oriented demographic.

<img width="400" height="604" alt="Screenshot 2025-10-21 141752" src="https://github.com/user-attachments/assets/3474058e-8abf-4584-ac2e-24256567df23" />
<img width="400" height="604" alt="income vs spending" src="https://github.com/user-attachments/assets/30dd537b-e309-496c-b820-afd1d02a502c" />


#### Cluster 2: Stable and Loyal Mid-Tier Customers (Balanced and Reliable Segment)
Cluster 2 consists of middle income customers (median income ≈ $60,000) who exhibit the highest loyalty duration across all groups. They are dependable, moderate spenders who maintain long term relationships with the company.
This cluster represents customers who are both value conscious and brand loyal. They engage heavily with deals and online shopping, making them the most active digital buyers. They also show steady purchasing behavior across multiple product categories, particularly wine, meat, and gold though at slightly lower levels than Cluster 0.

They are typically parents or partnered individuals, suggesting a stable lifestyle with consistent consumption habits.

#### Cluster 3: Young Budget Conscious Customers (Early Career or Students)
Cluster 3 stands out as the youngest demographic, likely made up of early career professionals or university students. They have the lowest median income (~$30,000) and the smallest overall spending, reflecting limited disposable income.

This group shows little interest in premium categories like wine or gold and tends to make few catalog or in-store purchases. However, they are digitally inclined and open to online engagement. Their lower loyalty duration suggests they are new or casual customers, yet their youth represents long-term growth potential if the company nurtures their relationship early.

### B) Cross Cluster Patterns and Trends
Several broader trends became clear across all four clusters:

1) Income and education were strongly correlated with spending behavior. Higher education levels (graduates and postgraduates) consistently led to higher spending, particularly in Clusters 0 and 2.
<p align="center">
<img width="816" height="333" alt="education" src="https://github.com/user-attachments/assets/2f379833-1eed-41d9-b4e6-393c90a943f1" />
</p>

2) Family composition played a key role in purchasing habits. Larger families (Cluster 1) focused on affordability, while smaller households (Clusters 0 and 3) exhibited more diverse spending choices.

3) Loyalty patterns varied significantly. Cluster 2 customers were the most long term and consistent, while Cluster 1 customers showed shorter retention periods.

4) Channel preferences differed by segment. Cluster 2 led in online and deal based purchases, while Cluster 0 preferred catalog and in store shopping.

5) Marital status correlated with spending: partnered customers generally spent more than singles, though in Cluster 3 this trend reversed slightly suggesting more independent spending habits among younger customers.
<p align="center">
<img width="815" height="208" alt="Marital status" src="https://github.com/user-attachments/assets/48ef5972-1c9c-450e-a650-bf15ac9c66f5" />
</p>

## Business Suggestions
**Cluster 0 (Premium Loyalists)**: Target with premium experiences, loyalty clubs, and early product access. Personalization and exclusivity are key.

**Cluster 1 (Family Bargain Seekers)**: Focus on affordable bundles, promotions, and referral incentives to improve retention.

**Cluster 2 (Loyal Mid-Tier Customers)**: Strengthen relationships through customized loyalty programs, digital offers, and community engagement.

**Cluster 3 (Young Budget-Conscious Shoppers)**: Build brand awareness and trust using social media, gamified discounts, and student packages.
