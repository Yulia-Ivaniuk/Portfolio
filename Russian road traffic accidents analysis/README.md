# Russian road traffic accidents analysis

<code>[Link ipynb](https://github.com/Yulia-Ivaniuk/Portfolio/blob/main/Russian%20road%20traffic%20accidents%20analysis/Road_accidents_Russia.ipynb)</code>

**Description:** This project involves a research analysis of road traffic accident (RTA) data provided by the "Karta DTP" platform (https://dtp-stat.ru/). "Karta DTP" is a non-profit initiative dedicated to addressing the issue of road accidents in Russia. It serves as a data collection platform for RTAs and offers a free, open-access accident analytics service. The project's goal is to assess road safety in Russia and develop recommendations for reducing the number of RTAs. The analysis utilizes geojson-formatted data available from https://dtp-stat.ru/opendata.

**Skills/Tools:** data parsing (Beautiful Soup), JSON data normalization, dealing with large datasets, hypothesis testing, GeoPands, Requests, Matplotlib, SciPy

**Conclusion:** The analysis of road traffic accident (RTA) data from "Karta DTP" has revealed key findings and recommendations:
1. *Trends in RTA Numbers:* RTAs have decreased since 2015, with a significant drop in 2020 due to the pandemic. However, 2023 saw a 3.75% increase in RTAs, possibly due to rising vehicle maintenance costs from sanctions.
   
2. *Accident Severity and Types:* Most increases in 2023 were in minor accidents, though severe accidents also rose. Fatal accidents remained stable. Significant increases were seen in "Collisions" and "Loss of Control" incidents, suggesting vehicle condition issues.

3. *Temporal Patterns:* Highest RTAs occur from July to September and on Fridays and Saturdays. Peak accident times are 5 PM to 7 PM, coinciding with heavy traffic.

4. *Causes and Outcomes:* Over half of RTAs are minor; a third are severe, and nearly one in ten are fatal.The majority of RTAs involve vehicle collisions, followed by pedestrian impacts and loss of control.

5. *Environmental Factors:* Fatalities are highest in poor weather and lighting conditions, highlighting the need for better road lighting. Poor road conditions, such as inadequate shoulders and barriers, increase fatality rates.

6. *Regional Analysis:* Regions with the highest severe RTAs include Chechnya and Dagestan; regions with the lowest include Tyumen and Moscow. Saint Petersburg has the lowest fatality rate.

7. *Violations and Vulnerable Groups:* Pedestrian violations are a major cause of fatal RTAs. Cyclists without reflective gear, railway crossing violations, and driving under the influence are high-risk behaviors. Pedestrians and cyclists have the highest injury and fatality rates, necessitating safer infrastructure and stricter regulations.

8. *Driver Experience:* Drivers with over 40 years of experience have the highest fatality rates, while novices have the highest injury rates but lower fatality rates.

The research tested the following hypotheses:
1. *Vehicle Safety:* The fatality rate in accidents involving Russian vehicles is 9%, compared to 12% for foreign vehicles. Despite a slight difference in fatality rates, the statistical analysis shows a significant difference in accident rates, indicating that Russian vehicles pose a greater danger on the roads. However, other factors also influence fatality rates.

2. *Transport Reform Impact in Saint Petersburg:* The 2022 transport reform in Saint Petersburg, which included changes to bus routes, the introduction of modern buses, and the removal of minibuses, led to a 15% reduction in RTAs, including a 29% decrease in fatal accidents and a 15% decrease in accidents with injuries. Accidents involving public transport decreased significantly, with a 37% reduction in 2022 and a further 4.5% in 2023 for accidents with injuries, and a 65% reduction in fatal accidents in 2022, remaining stable in 2023. This suggests that the transport reform had a positive impact on road safety.

3. *Driver Gender Safety:* Male drivers have a higher fatality rate (11%) compared to female drivers (5%). Female drivers are statistically safer, though other factors also influence fatality rates.

These findings highlight the need for improved road conditions, stricter traffic enforcement, effective transport policies and better infrastructure for vulnerable road users to enhance road safety.
