# Walmart CLT Hypothesis Testing
## Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female). The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. 
Dataset: https://github.com/lordchan/Walmart_CLT_HypothesisTesting/blob/main/walmart_dataset.csv
## Procedure:
1. Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset.
2. Detect Null values & Outliers (using boxplot, “describe” method by checking the difference between mean and median, isnull etc.)
3. Do some data exploration steps like:
Tracking the amount spent per transaction of all the 50 million female customers, and all the 50 million male customers, calculate the average, and conclude the results.
Inference after computing the average female and male expenses.
4. Use the sample average to find out an interval within which the population average will lie. Using the sample of female customers you will calculate the interval within which the average spending of 50 million male and female customers may lie.
5. Use the Central limit theorem to compute the interval. Change the sample size to observe the distribution of the mean of the expenses by female and male customers.
6. The interval that you calculated is called Confidence Interval. The width of the interval is mostly decided by the business: Typically 90%, 95%, or 99%. Play around with the width parameter and report the observations.
7. Conclude the results and check if the confidence intervals of average male and female spends are overlapping or not overlapping. How can Walmart leverage this conclusion to make changes or improvements?
8. Perform the same activity for Married vs Unmarried and Age
9. For Age, you can try bins based on life stages: 0-17, 18-25, 26-35, 36-50, 51+ years.
10. Give recommendations and action items to Walmart.

## What does the analysis report contain:

1. Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category', statistical summary.
2. Non-Graphical Analysis: Value counts and unique attributes ​
3. Visual Analysis - Univariate & Bivariate
4. For continuous variable(s): Distplot, countplot, histogram for univariate analysis
5. For categorical variable(s): Boxplot
6. For correlation: Heatmaps, Pairplots
7. Missing Value & Outlier Detection 
8. Business Insights based on Non- Graphical and Visual Analysis
9. Comments on the range of attributes and distribution of the variables and relationship between them.
10. Are women spending more money per transaction than men? Why or Why not? 
11. Confidence intervals and distribution of the mean of the expenses by female and male customers.
12. Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this conclusion to make changes or improvements? (10 Points)
13. Results when the same activity is performed for Married vs Unmarried using t-test.
14. Results when the same activity is performed for Age.
15. Affects of type of city and no. of years of stay in that city with respect to purchase value using ANOVA test.
16. Affects of occupation of customer on purchase value.

## Recommendation to Walmart:
1. Inventory Management: The business can optimize its inventory management based on the preferences of each gender. By stocking products that are popular among each group, the business can reduce overstocking of less popular items and improve turnover rates.
2. Personalized adveertisements: People from different cities have different cultural background. Unique adds can be shown to people which resonates with their background.
3. Visual Merchandising: Physical stores can arrange their displays to cater to the preferences of each gender. This could lead to more appealing shopping experiences and increased sales.
4. Targeted Marketing Campaigns: Walmart can create tailored marketing campaigns that specifically target the preferences and spending patterns of each gender.
5. Pricing Strategy: Walmart can change the price of certain products that appeal to a particular gender, so as to increase the profits.
6. Segregating products: Products which cater to different genders can be seperated at the stores, so that customers purchasing a product, might stumble upon other products and buy them.
7. Forming partnerships or collaborations with other companies that target specific genders could lead to mutually beneficial marketing initiatives.
8. Diversity and Inclusion: Using this information ethically, the business can also ensure it is promoting diversity and inclusion in its marketing, product offerings, and overall operations.
9. Walmart shouldn't focus too much on segregating customers based on maritial status.
10. Certain kind of expensive items like, furniture, electronics can be recommended more to male audience, because product categories and price does affect spending behaviour between male and female.
