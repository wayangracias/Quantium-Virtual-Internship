# Quantium Virtual Internship

This repository contains results of the completed tasks for Quantium Virtual Internship Experience Program by Forage, designed to replicate life in the Retail Analytics and Strategy team at Quantium, using R.

## Task 1: Data preparation and customer analytics
- Analyze the data in order to comprehend the prevailing patterns and actions related to purchases. The client displays a specific interest in the purchasing behavior of customer segments, particularly in relation to chip products. 
- LIFESTAGE: refers to a customer attribute that determines whether they have a family and at which stage of life they currently are, such as having children in pre-school, primary school, or secondary school.
- PREMIUM_CUSTOMER is a customer segmentation approach utilized to distinguish shoppers based on the price range of the products they buy and the specific types of products they prefer. This segmentation helps identify whether customers are inclined to spend more for quality or brand, or if they tend to opt for the most affordable options available.

Insights
- Sales have mainly been due to Budget - older families, Mainstream - young singles/couples, and Mainstream - retirees shoppers.
- The high spend on chips for mainstream young singles/couples and retirees is due to more of them than other buyers.
- Mainstream, mid-age, and young singles and couples are also more likely to pay more per packet of chips. This is indicative of impulse buying behavior.
- Mainstream young singles and couples are 23% more likely to purchase Tyrrells chips compared to the rest of the population.

Thus, the Category Manager may want to increase the category’s performance by off-locating some Tyrrells and smaller packs of chips in discretionary space near segments where young singles and couples frequent more often to increase visibility and impulse behavior.

## Task 2: Experimentation and uplift testing

Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.
Steps including:
- Create a measure to compare different control stores to each of the trial stores to do this, write a function to reduce having to re-do the analysis for each trial store.
- Consider using Pearson correlations or a metric such as a magnitude distance e.g., 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.
- Compare each trial and control pair during the trial period.

Insights
- We’ve found control stores 233, 155, 237 for trial stores 77, 86, and 88 respectively.
- The results for trial stores 77 and 88 during the trial period show a significant difference in at least two of the three trial months, but this is not the case for trial store 86.
- We can check with the client if the implementation of the trial was different in trial store 86, but overall, the trial shows a significant increase in sales.

## Task 3: Analytics and commercial application

Provide the manager insights and recommendations that they can use when developing the strategic plan for the next half year.
Use the "Pyramid Principles" framework when putting together a report for our clients. The report must include data visualisations, key callouts, insights as well as recommendations and/or next steps.
