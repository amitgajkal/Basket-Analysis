# Basket-Analysis
It is a technique used to uncover the association between items. It uncovers the products commonly bought together.
It is often called Market Basket Analysis. 

Basket Analysis (for Grocery Store) can help in following:
  - Recommending adjustments to the physical layout of the store, including the strategic placement of selected items to optimize consumer engagement and enhance overall sales performance.
  - Refining online product recommendations based on post-purchase behavior.
  - Developing effective cross-selling strategies for retailers.
  - Formulating pricing, sales, and discount strategies for encouraging the simultaneous purchase of specific products.

For this analysis we need to understand following concepts:
## Support <img align="right" width="400" src="https://github.com/amitgajkal/Basket-Analysis/blob/main/Resources/Support.png" alt="amitgajkal" />
  - It indicates the % of transactions that include two specific products
  - Support indicates the frequency of the products being bought together
                             
	Support = (Number of transactions including both products) / (Total number of products)
	                             
	For example,
	For Berries and whipped cream
	
	Number of transactions including both products = 3
	
	Total number of transactions = 10
	
	Support for basket = 3/10 = **30%**

**High support means basket stats are reliable and makes the basket financially more interesting**

## Confidence <img align="right" width="400" src="https://github.com/amitgajkal/Basket-Analysis/blob/main/Resources/Confidence.png" alt="amitgajkal" />
  - % transactions that contains the two products together, out of the transactions containing one of the two products. 

	Confidence is calculated for each of the products from the basket separately 
								                          
	Confidence of product one = (Support of Basket) / (Support of product one)
	
	Confidence of product two = (Support of Basket) / (Support of product two)
	
	Support for basket = **30%**
	
	Support of berries = 4/10 = **40%**
	
	Confidence of berries = 30/40 = **75%**
	
	Support for whipped cream = 5/10 = **50%**
	
	Confidence of whipped cream = 30/50 = **60%**

Significance of confidence:
- This means there is a more chance of someone buying whipped cream, when they have already added 
berries to their basket
- Confidence is more for berries to influence the purchase of
whipped cream (75%)
- Confidence indicates the direction of cross selling. If someone buys berries there is more 
chance to buy whipped cream than other way around
- Confidence does not provide the strength of the relationship between the two products in 
basket so there lift comes in the picture

## Lift <img align="right" width="400" src="https://github.com/amitgajkal/Basket-Analysis/blob/main/Resources/Lift.png" alt="amitgajkal" />
 - Lift gives strength of the relationship for a basket of two products
 - Lift = (Support of basket) / [(Support of product one)*(Support of product two)]
 - Support for basket = 30%
 - Support of berries = 4/10 = 40%
 - Support for whipped cream = 5/10 = 50%
 - Lift = 30/(40*50) = **1.5**

Significance of lift:
 - lift ~ 1: no correlation between two purchases
 - lift >1: Two products bought together frequently
 - lift <1: Two products bought together less frequently 

----------------------------------------------------------------------------------------------------------

## The utility of basket analysis extends beyond the aforementioned applications and can be effectively leveraged in diverse scenarios, including:
 - Enhancing the analysis of website page visits to discern patterns and optimize user experience.
 - Analyzing questions raised in support tickets to identify correlations and improve support processes.
 - Optimizing menu offerings in restaurants by scrutinizing the patterns of dishes ordered, thereby informing strategic decisions in menu design and promotions.


Click [here](https://www.novypro.com/project/grocery-store-%7C-basket-analysis) for interactive report

# Report
<img align="left" width="400" src="https://github.com/amitgajkal/Basket-Analysis/blob/main/Resources/Basket.gif" alt="amitgajkal" />
