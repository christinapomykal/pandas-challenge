# Pandas project analyzing data

The project requires the analysis of purchasing data using Python Pandas. The series of summary tables forms a report of meaningful insights. 

## Heroes of Pymoli

The fantasy game Heroes of Pymoli encourages players to purchase optional items to augment their experience. To understand the purchasing behavior of the players, the data was analyzed by purchases, gender, age, popular and profitable items. 

## Analysis

The Python Pandas analyzes the purchasing data contained in [purchase_data.csv](HeroesOfPymoli/Resources/purchase_data.csv). The following shows the first 5 rows of purchasing data. 

![purchase_df_peek](Images/purchase_df_peek.png)

It was confirmed there were no missing values in the dataset prior to the analysis. 

![noMissingData](Images/noMissingData.png)

### Purchasing Analysis (Total)

* The total number of players who made purchases was determined. 

![totalPlayer](Images/totalPlayer.png)

* The number of unique items, average purchase price, total number of purchases, and total revenue provides a overall picture of the purchasing data. 

![purchaseAnalysisTotal](Images/purchaseAnalysisTotal.png)

**Observations**
Several trends were immediately observed. First, the vast majority of Heroes of PyMoli players are male (84.03%; n=484/576), with female (14.06%; n=81/576) and other/non-disclosed (1.91%; n=11/576) accounting for the rest of the total population of players. 

Secondly, 179 unique items were purchased over 780 transactions and generated $2,379.99 total revenue. The item price ranged from $1.00 (Item Stormfury Mace) to $4.99 (Whistling Mithril Warblade). The average price over 780 transactions was $3.05, which is slightly below the median price of $3.15. This indicates a longer tail on the curve and a tendency for transactions to be closer to the lower end of the price range. 

### Gender Demographics

* The gender of players were male, female, or other/non-disclosed. The number of players and percentage of total players was determined for each gender type. 

![genderDemoAnalysis](Images/genderDemoAnalysis.png)

### Analysis of Purchases by Gender

* The purchasing behavior of players by gender is analyzed by purchase count, average purchase price, total purchase value, and average total purchase per person. 

![purchaseAnalysisGender](Images/purchaseAnalysisGender.png)

**Observations**
Purchases were analyzed by gender group. The vast majority of purchases were by males, with 653 transactions of the 780 total. The volume of transactions directly contributes to the revenue of $1,967.64, representing 83.7% of total revenue. However, players identifying as female ($4.47) or other/non-disclosed ($4.56) spend more per person compared to male players ($4.07) as seen in `Avg Total Purchase per Person`. They also purchase more expensive items as seen in `Average Purchase Price`. Females may be a potential target demographic as the company considers how to expand its customer base. 

### Age Demographics and Purchase Analysis

* The ages of the youngest (7 years old) and oldest (45 years old) players were determined to form age groups. The players making purchases were grouped by age accordingly, and the number of individuals and percentage of total players calculated for each age group. 

![ageDemoAnalysis](Images/ageDemoAnalysis.png)

 The purchase count, average purchase price, total purchase value, and average total purchase per person was calculated by age group. 

![purchaseAnalysisAge](Images/purchaseAnalysisAge.png)

**Observations**
Most players are 20-24 years old (44.79%). The percentage increases to 76.74% When including the neighboring age groups of 15-19 and 25-29 year old players 

Similarly the same aged group of Heroes of PyMoli players (15-29 year olds) make most of the purchases (`Purchase Count`) and bring in the majority of the revenue (`Total Purchase Value`). Players between the ages of 20-24 account for 47% of all purchase transactions (`Purchase Count` 365 of 780) and total revenue (`Total Purchase Value` $1114.06 of $2379.77). This age demographic is the primary driver of revenue. 

Interestingly the 35-39 age group has the highest average total purchase per person. This age group may be a potential demographic group to target in the company's efforts to identify people who may have more disposable income to spend on Heroes of PyMoli. 

### Top Spenders

* The top spenders are ranked by total purchase value. Their purchase count and average purchase price are also calculated. 

![topSpenders5](Images/topSpenders5.png)

* Additional analysis was done to add the gender and ages to the Top Spenders dataframe. 

![topSpenders10GenderAge](Images/topSpenders10GenderAge.png)

**Observations**
Looking at the first 5 Top Spenders dataframe reveals that these 5 players conduct 3-4 purchase tranactions, and have total purchases valued from $13.10 to $18.96. As expected, their average purchase price is above the mean ($3.05) and median ($3.15) of the population. 

Interestingly the results of the additional analysis shows the 3rd top spender is female and has the highest average purchase price of the top 10 spenders. Females are 3 of the 10 top spenders. All 10 of the top spenders fall in the age range (15-29 year olds) making the most purchases. 

### Most Popular Items

* The most popular items are identified by highest purchase count, along with the item price and total purchase value. 

### Most Profitable Items

* The most profitable items are identified by highest total purchase value, along with purchase count and item price. 
