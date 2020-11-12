# Dating_v1.01
Analysis on data gathered from speed dating. Examine specific qualities or traits a person looks for in a potential partner (Male versus Female)

## Background:
Dating can be difficult during this day and age. Especially with online dating - how can you enable yourself to compete with others or to stand above others? From extensive research and data accumulated from a Professor from Columbia Business School, we will examine the dataset and narrow down by gender and what they are looking for their potential partner. Keep in mind, the dataset is not generalized enough to include the entire population - the data is well intended for college students or age groups between 20 and some early 30s. Outside the scope or range identified will not be valid.

## The Data:
First, let's get a breif background of the datasets. The data is collected from speed dating which includes many different characteristics, attributes, and also opinions. In more details, the data consist of participant's basic background such as age and gender to questionaire before and after the speed dating, also basic questions of what participants are looking for in their potential partners. There are 195 different categories of information! We will only focus on specific information - specifically what these approximately 8,000 participants thoughts and opinions in a potential partner. 
Link: https://www.kaggle.com/annavictoria/speed-dating-experiment
There are 195 different features or attributes - data will only examine:

  - Gender
  - Age
6 Qualities/Traites
  - Attractiveness
  - Sincere
  - Intelligence
  - Funny
  - Ambitious
  - Shared Interests
Each participants in the data set are given 100 points to allocate to the 6 qualities from above - the more the points allocated for a category, the more important that category is for that participant. Also true, the least the points allocated to a category, the least the importance of that category for that partipant

## Cleaning:
Seperate data into Male and Female as the two will be compared. Data contains values that are not registered as numericals, numbers may includes symbols or decimal point values - these values are converted to integers so that they are standardized and will be processed later. Get rid of outliers in our data, there some that allocates 100 points towards one quality/trait. Normalize the dataset as best as possible to run A/B Testing.

## The Test:

  Mann-Whitney U Test: p-value = 0
  
  Kruskal Test: p-value = 0

## Conclusion:
As we can see the p value is very low - we can reject the null hypothesis. There is significant evidence to say that we accept the alternative hypothesis and reject the null hypothesis. In other words, there is signficant evidence to say that males overall tend to seek attractiveness in a partner versus females who are less likely than males to seek attractiveness.

Data can be normalized further winsorizing the data or filling in missing data with similar/close values. Normalizing the data further will give more accurate result. Further research needs to be done to find out more about each gender and their interests.
