# Pandas project analyzing data

The project requires the analysis of purchasing data using Python Pandas. The series of summary tables forms a report of meaningful insights. 

## Heroes of Pymoli

The Python Pandas analyzes the purchasing data contained in [purchase_data.csv](HeroesOfPymoli/Resources/purchase_data.csv). The following shows the first 5 rows of purchasing data. 
![purchase_df_peek](Images/purchase_df_peek.png)

## Analysis

The fantasy game Heroes of Pymoli encourages players to purchase optional items to augment their experience. To understand the purchasing behavior of the players, the data was analyzed by purchases, gender, age, popular and profitable items. 

### Purchasing Analysis (Total)

* The total number of players who made purchases was determined. 
![totalPlayer](Images/totalPlayer.png)

* The number of unique items, average purchase price, total number of purchases, and total revenue provides a overall picture of the purchasing data. 
![purchaseAnalysisTotal](Images/purchaseAnalysisTotal.png)

### Gender Demographics

* The gender of players were male, female, or other/non-disclosed. The number of players and percentage of total players was determined for each gender type. 
![totalPlayer](Images/totalPlayer.png)

* The number of unique items, average purchase price, total number of purchases, and total revenue provides a overall picture of the purchasing data. 
![genderDemoAnalysis](Images/genderDemoAnalysis.png)

From these first 2 analyses, the vast majority of players making purchases are male (84%) and the average price of items purchased is $3.05. 

### Analysis of Purchases by Gender

* The purchasing behavior of players by gender is analyzed by purchase count, average purchase price, total purchase value, and average total purchase per person. 
![purchaseAnalysisGender](Images/purchaseAnalysisGender.png)

An observation is players with female or other/non-disclosed gender spend more per person compared to male players as seen in `Avg Total Purchase per Person`. They also purchase more expensive items as seen in `Average Purchase Price`. 

### Age Demographics and Purchase Analysis

* The age range of players making purchases were grouped to look for trends by purchase count, average purchase price, total purchase value, and average total purchase per person.  
![purchaseAnalysisAge](Images/purchaseAnalysisAge.png)

Players between the ages of 20-24 account for 47% of all purchase transactions (`Purchase Count` 365 of 780) and total revenue (`Total Purchase Value` $1114.06 of $2379.77). This age demographic is the primary driver of revenue. 

### Top Spenders

* The top spenders are identified by total purchase value, along with their purchase count, and average purchase price. 

### Most Popular Items

* The most popular items are identified by highest purchase count, along with the item price and total purchase value. 

### Most Profitable Items

* The most profitable items are identified by highest total purchase value, along with purchase count and item price. 
