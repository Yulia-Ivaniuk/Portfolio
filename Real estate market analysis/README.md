# Real estate market analysis

<code>[Link ipynb](https://github.com/Yulia-Ivaniuk/Projects/blob/main/Real%20estate%20market%20analysis/Real%20Estate%20market%20analysis.ipynb)</code>

**Description:**  Analysis of Real Estate market data (Saint-Petersburg and nearby towns) to identify  patterns, which exist in the market, and to find out which factors affect the most the property price

**Skills/Tools:**  data preprocessing (duplicates, missing data, anomalies, data categorization), data visualization (histogram, boxplot, scatterplot, bar plot, line plot), Pandas, Matplotlib

**Conclusion:**  Despite a large scatter of data,  it was determined that most of the real estate ads fall under standard property characteristics in Russia: one-, two- or three-room apartments with a total area of 25 to 70 m2, with a kitchen area of 6 to 9 m2, a ceiling height of 2.6-2.7 m, a cost of 3 to 7 million RUB , in five- or nine-story buildings and located at a distance of 10-16 km from the center. 

The following market patterns were discovered: 
-	Real estate ads are most often published on weekdays, the most active seasons are spring and autumn.
-	The sale usually takes from 44 to 228 days. A quick sale is a sale that takes less than 44 days, while an unusually long sale is a sale that takes more than 504 days.
-	Most of all, the price depends on the total area of the object (correlation coefficient - 0.84).
-	 Apartments on the first and last floors are cheaper than apartments on other floors. 
-	Seasonal trends were identified: there is a higher user activity and therefore an increased price for real estate during spring and autumn seasons. The lowest user activity and price of real estate appears to be in June. When analyzing prices by years, we’ve seen a decline in prices that starts in 2014 and goes until 2016-2017, which can be explained by the 2014 economic crisis in Russia.
-	The highest price per m2 is in St. Petersburg, Pushkin and Kudrovo, while the lowest price per m2 is in Vyborg, Vsevolozhsk and Gatchina.
-	The price of an object decreases while the distance from the center increases. However, we identified the price peaks in the areas of 5-6km and 20-25km from the city center – most likely it’s caused by the presence of expensive luxury real estate on Petrogradsky and Krestovsky Islands as well as in Sestroretsk and Pushkin.

