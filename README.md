# InstaCart-Product-and-Market-Basket-Insight

### Overview
Instacart, a U.S.-based technology firm, offers same-day grocery delivery and pickup services throughout the United States and Canada. Shoppers can browse and purchase groceries from various partner retailers via the Instacart app or website. Personal shoppers from Instacart then fulfill and deliver these orders.

### Goals:
Analyze anonymized data from 3 million grocery transactions, contributed by over 200,000 users, provided by Instacart.
Uncover product relationships to enhance strategies for cross-selling and upselling.
Apply customer segmentation techniques to support targeted marketing efforts and predict consumer behavior.
Develop a Machine Learning model to forecast which products a user is likely to reorder in their subsequent purchase.

### Data Overview
- **Aisles:** Contains 134 unique aisles.
- **Departments:** Includes 21 unique departments.
- **Orders:** Comprises 3,421,083 orders from 206,209 users.

### Key Insights
- Orders are categorized into Prior, Train, and Test sets, with Train and Test distributions being similar.
- Customers place between 0 to 100 orders, primarily during the day.
- Weekly shopping habits are evident, with spikes at 7, 14, 21, and 30 days between orders.
- Most orders occur on weekends, particularly Saturday afternoons and Sunday mornings.
- Products: Contains 49,688 products, along with their corresponding aisles and departments.
- Order Products Prior: Details the products ordered, their cart sequence, and whether they were reordered.
- The dataset includes 3,214,874 orders, involving 49,677 products.
- Most customers purchase 1-15 items per order, with a maximum of 145 items in a single order.
- Reordered items account for 58.97% of the total.
