
#Introduction
Dating can be very difficult and there are a lot of different variables and attributes that people look for. What is it that most people are looking for in the opposite sex? If we can narrow down to a specific trait or characteristic that most people are looking for, perhaps there can be better matching rates in dating. There is a set of data from experimental speed dating in 2002 through 2004. Information contains many different information and attributes, ranging from gender, age, income to attributes of what they look in a partner. There are 195 total columns/categories of information of the person’s background, preferences of what they look for in a date, and also opinions of how others perceive them. Focusing on the attributes section of the data - attributes are broken down to 6 different types as follows:
Attractive, sincere, intelligent, fun, ambitious, and shared interests/hobbies 
the person has a 100 points and they can distribute the points to the different categories of what is most important to them (the more points, the more important, the fewer the points, the less importance).
Information was compiled by a professor at Columbia Business School. 

#Research design

Males are more likely to look at attractiveness in their potential dating partners than females.
In order to test this hypothesis we will compare males to females, by first splitting the data between males and females. Then, we will only examine attributes that males and females look for in their dating partner.
Now, we will examine how males and females allocate their 100 points in what they look for in their potential partners. This information can be compared between males vs females of what each gender looks for. 
The information will be graphed to compare the different characteristics for each gender. From here, I will examine any outliers in the data and also examining any missing data collected. 
Data on the categories are dependent on each other (a person is limited to 100 points allocation for varying categories). I will be using one of the non-parametric tests - specifically the Kruskal-Wallis test to compare males vs females on attractiveness.

#Audience

Data set is research with mostly college students as participants - which also implies age groups of 20 to 30 year olds. Targeted audience will be among college students and/or age groups between 20s to 30s. Groups outside the data set will not be applicable to whatever resolution is drawn upon. For those within the criterias corresponding closely to the data sets will learn more about what the opposite gender is looking for in a partner and perhaps the person can potentially somewhat improve their chances by knowing what characteristic(s) is most desirable when looking for a partner.




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
