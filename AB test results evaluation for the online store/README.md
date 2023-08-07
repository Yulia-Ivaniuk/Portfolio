# A/B test results evaluation for the online store

<code>[Link ipynb](https://github.com/Yulia-Ivaniuk/Projects/blob/main/AB%20test%20results%20evaluation%20for%20the%20online%20store/AB%20test%20for%20online%20shop.ipynb)</code>

**Description:**  Analysis of the online store data to prioritize a list of 9 hypotheses developed to increase the revenue of the store, launching an A/B test and evaluating its results

The following steps were taken:
-	Prioritization of a list of 9 hypotheses using the ICE and RICE frameworks and choosing a most valuable one to test
-	Building graphs of cumulative revenue and average check by group, relative change in the average check of group B to group A, average number of orders per visitor, relative change in the average number of orders per visitor of group B to group A, scatter plot of the number of orders and order value
-	Using Mann-Whitney-U-Test to see if there is a statistical significance of the differences in average number of orders and order value between groups (for raw and cleaned data)

**Skills/Tools:**  data preprocessing, data visualization, RICE and ICE frameworks, A/B test, testing of statistical hypotheses (U-test), Pandas, Matplotlib, SciPy

**Conclusion:**  Based on the results of the analysis, it was decided to stop the test and recognize the victory of group B over group A. Despite the fact that we saw no significant difference in the order value between groups, there is a statistically significant difference in the number of orders and a rather high relative increase (17.9%) in the number of orders in group B compared to group A (according to cleaned data). An increase in the number of orders, even while maintaining the average check, will lead to an increase in the online store's revenue. Therefore it was recommended to apply the changes that were made for group B to all users.



