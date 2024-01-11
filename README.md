![image](https://github.com/amitgajkal/Basket-Analysis/assets/19805627/61c6bd1e-11e8-4d3e-9944-09c9bce3142d)# Basket-Analysis
It is a technique used to uncover the association between items. It uncovers the products commonly bought together.
It is often called Market Basket Analysis. 

Basket Analysis (for Grocery Store) can help in following:
  - Recommending adjustments to the physical layout of the store, including the strategic placement of selected items to optimize consumer engagement and enhance overall sales performance.
  - Refining online product recommendations based on post-purchase behavior.
  - Developing effective cross-selling strategies for retailers.
  - Formulating pricing, sales, and discount strategies for encouraging the simultaneous purchase of specific products.

For this analysis we need to understand following concepts:
## Support
  - It indicates the % of transactions that include two specific products
  - Support indicates the frequency of the products being bought together
                             Number of transactions including both products
	Support = ------------------------------------------------------------------------------------
	                             Total number of products

For example,
For Berries and whipped cream

Number of transactions including both products = 3

Total number of transactions = 10

Support for basket = 3/10 = 30%

**High support means basket stats are reliable and makes the basket financially more interesting**

## Confidence
  - % transactions that contains the two products together, out of the transactions containing one of the two products. 

	Confidence is calculated for each of the products from the basket separately 
	
							                          Support of Basket
	Confidence of product one = ----------------------------------------- 
						                         Support of product one
	
	
							                            Support of Basket
	Confidence of product two = ----------------------------------------- 
				                             Support of product two

	Support for basket = 30%
	
	Support of berries = 4/10 = **40%**
	
	Confidence of berries = 30/40 = **75%**
	
	
	
	Support for whipped cream = 5/10 = **50%**
	
 Confidence of whipped cream = 30/50 = **60%**  

