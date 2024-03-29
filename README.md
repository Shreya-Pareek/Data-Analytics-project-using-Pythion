# Marketing Campaign Exploratory Data Analysis
### Problem Statment
The goal of this project is to group customers that share similar purchasing patterns to better understand our customers.
This information is helpful because we could use strategies such as targeted advertising to personalize our message to each group. We could also identify groups of customers that we may have not known about earlier.

### Description:
"This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years
- NumDealsPurchases: Number of purchases made with a discount
- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s website in the last month
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Z_CostContact: Final Cost Charge for the product
- Z_Revenue: Over all revenue generated for the particular product
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

### Summary and Conclusion
#### Insights:

- Customers age range is from 27 to 55
- 'Widow' is a very large group of alcohol users that we should exploit => SUGGESTION: THERE SHOULD BE ALCOHOL CESSATION PRODUCTS FOR TWO GROUPS !
- Non-children families enjoy buying MntWines. With the higher income, they buy MntWines and MntMeatProducts
- 'Single' and 'Widow' take a lead in consuming 'MntMeatProducts'
- A majority of families have high income with no kids. They prefer MntWines and MntMeatProducts
  - If alcohol is the mainstay of this store, they're doing a great job. => SUGGESTION: TURNING FISH TO SUPPLY IF MEAT IS NOT ENOUGH TO SUPPLY
- A minority of families have low income with 2 kids
- "Income" and "Alcohol" are related with 73% probability
- "Income" and "MntMeatProducts" are related with 70% probability
- High amount of purchases can bee seen in the Store Visits as compared to Web or Catalog Purchaces
