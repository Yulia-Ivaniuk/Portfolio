# Mobile application user’s data and A/A/B test results analysis

<code>[Link ipynb](https://github.com/Yulia-Ivaniuk/Projects/blob/main/Mobile%20application%20user%E2%80%99s%20data%20and%20AAB%20test%20results%20analysis/AB%20test%20for%20mobile%20application.ipynb)</code>

**Description:**  Analysis of a mobile application user’s behavior to build a sales funnel. Evaluation of the A/A/B test results to understand whether changing the font in the application affects user behavior and how.

The following steps were taken:
-	Building and analyzing a sales funnel based on user’s behavior, calculating conversion rates for each event
-	Evaluating  the results of A/A test to make sure that the test was carried out correctly 
-	Using Z-test to see if there is a statistical significance of the differences in conversion rates by event between groups. As we were dealing with a multiple test, Bonferroni correction was used.

**Skills/Tools:** data preprocessing, data visualization, Sales Funnel, A/A/B test, testing of statistical hypotheses (Z-test), Pandas, Matplotlib, SciPy, Plotly

**Conclusion:**  No statistically significant difference was found in the conversion rates between the control groups A and A1, which means that we can be sure of the accuracy of the testing.  Moreover, we saw no statistically significant difference in conversion rates between the control groups A, A1 and test group B.  According to the results of the A/A/B test, we can conclude that changing the font didn’t affect the conversion rates, so changing the font for the whole  application will not lead to either negative or positive results for customer behavior in terms of conversion.


