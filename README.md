# E-commerce-Marketing-and-Shopping-EDA-Hypothesis-testing-with-Python

To conduct a thorough exploratory data analysis (EDA) and hypothesis testing on two comprehensive datasets one containing information on customers visiting the shopping site for purchase and another that has demographic, purchase, and marketing information about the group of people

### Expectations:
The project expects you to Analyze user behavior across different page categories, engagement time, and other features. Gain insights into factors influencing purchase decisions and identify areas for optimization. Formulate some hypotheses on the dataset and check if they are correct.

## Shopping dataset:
- Preprocessing of data as required
- Univariate Analysis: Plot histograms or box plots for each numerical feature to identify outliers and distribution shapes.
- Correlation Analysis: Calculate correlations between numerical features to identify potential relationships.
- Visualizations: Use scatter plots, pair plots, or heatmaps to visualize relationships between numerical features.
- Class Distribution: Check the distribution of the target variable ('Revenue') to understand class balance.
- Summarize page views, durations, and bounce/exit rates for each page category.
- Analyze SpecialDay distribution and its correlation with Revenue.
- Generate a binary feature indicating whether the user visited all three-page categories.
- Explore PageValues distribution and its relationship with TrafficType, VisitorType, and Region.
- Investigate user session lengths and their impact on conversion rates.
- Group users based on VisitorType, OperatingSystems, and Region to identify potential differences in behavior and conversion rates.
- Segment users based on TrafficType and analyze their engagement patterns and purchase probability.

## Campaign Dataset:
- EDA on various features and columns.
- Feature engineering for the required analysis.
- Remove extreme values if required.
- Hypothesis testing:
  - Is income of customers dependent on their education
 -  Do higher income people spend more (take in account spending in all categories together)
  - Do couples spend more or less money on wine than people living alone (set 'Married','Together':'In couple' and 'Divorced','Single','Absurd','Widow','YOLO':'Alone')
  - Are people with lower income are more attracted towards campaign or simply put accept more campaigns. ( create two income brackets one below median , other above median income and create a column which tells if they have ever accepted any campaign)
- Select suitable tests according to the need and check the hypotheses


