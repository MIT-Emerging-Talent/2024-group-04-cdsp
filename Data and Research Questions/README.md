# Social Media and Mental Health

Social media encompasses online platforms and websites that allow users to create profiles and engage with others by sharing content like text, images, videos, and links. While it offers the advantage of facilitating virtual socialization, it also poses various costs and problems related to mental health issues, cyberbullying, social media attachment or addiction, comparison, and low self-esteem. One major concern is its negative impact on mental health, which includes psychological, emotional, and social well-being, affecting how individuals think, feel, behave, handle stress, and relate to others and their surroundings. Social media overuse is expected to have adverse effects on mental health, leading to social isolation, loneliness, and anxiety. This study aims to explore the correlation between social media usage and mental health problems.

---

## Domain: *Health*

### Project Overview:

Our project aims to explore the relationship between time spent on social media platforms and mental health outcomes. With the increasing prevalence of social media use globally, understanding its potential impact on mental well-being has become a significant area of interest. This project seeks to contribute to the existing body of knowledge by conducting a comprehensive analysis of this correlation.

### Problem Statement:

Human beings are inherently social and rely on connections with others to alleviate stress, anxiety, and sadness; a lack of social interaction poses significant risks to mental health. Today, virtual connections through social media platforms have become ubiquitous. A staggering 62.3% of the global population engages with social media, spending an average of 2 hours and 23 minutes daily (as of January 2024). While social media offers various positive benefits, experts express concerns over its potential negative impact on mental health, particularly among younger demographics. Mental health, as defined by the World Health Organization (WHO), is essential for individuals to effectively cope with life's challenges, fulfill their potential, and contribute to society. This project aims to explore the relationship between social media usage and mental health outcomes.

### Actionable Data Questions:

To assess the impact of social media on mental health, we consider factors associated with mental health issues such as anxiety and sleep disturbances:

1. Correlation between occupation status and the average time spent on social media every day?
2. How does the average time spent on social media affect feelings of depression?
3. How does age correlate with the amount of time spent on social media and mental health outcomes?
4. Is there a difference in social media usage and its impact on mental health between genders?
5. Is there a correlation between time spent on social media and focus problems?
6. Is there any correlation between the time spent on social media and feelings of worry and anxiety?
7. What is the relationship between concentration difficulties and social media usage?

### Data:

This dataset was collected for a project to study if spending a lot of time on social media affects mental health. It was gathered through a survey.

### Source Data:

The link to the dataset is: [Kaggle - Social Media and Mental Health Dataset](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health)

### Data Acquisition:

The data was gathered through a survey conducted from 04/18/2022 to 11/12/2022.

---

## Data Analysis:

### Tools:

For analyzing data, we used Jupyter Notebook and packages like Pandas, Seaborn, Matplotlib, and Scikit-learn.

### Data Cleaning:

In data cleaning, we did not encounter any non-entries except for the variable 'Organization type', which was not used in the data analysis. Therefore, no observations were removed. The variable 'average time spent on social media' was qualitative and was transformed into quantitative by taking the average of an interval. For example, 'between 2 to 3 hours' was replaced by '2.5' to facilitate analysis. Additionally, some entries in the 'gender' variable were spelled incorrectly and were corrected.

---

## Results and Evaluation:

### Non-Technical Explanation:

This study aimed to investigate whether social media usage correlates with mental health issues. We analyzed a dataset obtained from an online survey focused on this subject. The survey assessed various factors related to mental well-being, including difficulty sleeping, susceptibility to distraction, restlessness, anxiety, depression, comparison with others on social media, and disruption of daily routines. A total of 481 individuals participated in the survey, ranging in age from 13 to 91 years old, with an average age of 26.1 years. Out of these participants, 478 reported using social media, while 3 individuals did not. On average, participants spent 3.5 hours per day on social media platforms.

### Correlation Analysis:

The data suggests that while the average time spent on social media per day has a low correlation with mental health problems, attachment to social media, particularly aspects related to social media addiction, shows moderate correlations with certain mental health issues such as difficulty concentrating and being easily distracted. However, seeking validation from social media features and feeling depressed or down have a low correlation with social media-related variables.

### Possible Sources of Error: 

Potential sources of errors in this study primarily stem from the data collection process. The dataset mainly

---

## Technical Explanation

The following are variable names:

- What is your age?
- Gender
- Relationship Status
- Occupation Status
- What type of organizations are you affiliated with?
- Do you use social media?
- What social media platforms do you commonly use?
- What is the average time you spend on social media every day?
- How often do you find yourself using social media without a specific purpose?
- How often do you get distracted by social media when you are busy doing something?
- Do you feel restless if you haven't used social media in a while?
- On a scale of 1 to 5, how easily distracted are you?
- On a scale of 1 to 5, how much are you bothered by worries?
- Do you find it difficult to concentrate on things?
- On a scale of 1-5, how often do you compare yourself to other successful people through the use of social media?
- Following the previous question, how do you feel about these comparisons, generally speaking?
- How often do you look to seek validation from features of social media?
- How often do you feel depressed or down?
- On a scale of 1 to 5, how frequently does your interest in daily activities fluctuate?
- On a scale of 1 to 5, how often do you face issues regarding sleep?


As the names of the variables are long in the bellow table we only use their variable number.
Table 1: Correlation matrix 
|     | 8       | 9      | 10       | 11      | 12      | 13     | 14       | 15     |  16   | 17        | 18      | 19      | 20      |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| 8   | 1.00000 | 0.38898 |0.36957 | 0.39590 | 0.33383 | 0.31925 | 0.31242 |0.19380 |  0.05240| 0.10714 | 0.32628 | 0.28820 | 0.16987 |
| 9   |         | 1.0000 |  0.46335| 0.35903 | 0.36549 | 0.25208 | 0.28882 |0.14820 | 0.08764| 0.14451 | 0.31547 | 0.35937 | 0.26049 |
| 10  |         |        | 1.0000 | 0.513354 | 0.60741 | 0.34330 | 0.52774 |0.28850 | 0.07806| 0.27014 | 0.37944 | 0.38913 | 0.25536 |
| 11  |         |        |         | 1.0000 | 0.51480 | 0.34703 | 0.46944 |0.32097 |  0.13419| 0.24592 | 0.32896 | 0.38477 | 0.16660 |
| 12  |         |        |         |         | 1.0000 | 0.46267 | 0.66276 |0.28612 | 0.01463 | 0.17258 | 0.40766 | 0.47999 | 0.29114 |
| 13  |         |        |        |         |         | 1.0000 | 0.54590 | 0.41430 | 0.02058 | 0.20884 | 0.58875 | 0.43034 | 0.32736 |
| 14  |         |        |         |         |         |         | 1.0000 | 0.37115 | 0.06074| 0.24203 | 0.50979 | 0.50319 | 0.35467 |
| 15  |         |        |         |         |        |         |         | 1.0000 |  -0.01146 | 0.41732 | 0.41780 | 0.37424 | 0.19371 |
| 16  |         |        |         |         |         |         |         |        | 1.0000 | 0.15357 | 0.03547 | 0.04615 | 0.06851 |
| 17  |         |        |         |         |         |         |         |        |         | 1.0000 | 0.27212 | 0.27857 | 0.12889 |
| 18  |         |        |        |         |         |         |         |        |        |         | 1.0000 | 0.49497 | 0.37472 |
| 19  |         |        |         |         |         |         |         |        |         |         |         | 1.0000 | 0.31924 |
| 20  |         |        |        |        |         |         |         |        |         |         |         |         | 1.0000 |




There are four variables that in this study we consider as social media-related variables, they are as follows: 
A) Time spent on social media: 'average time spent on social media per day' 
B) Attachment to social media: 'finding oneself using social media without a specific purpose', 'getting distracted by social media when one is busy doing something', and 'feeling restless if one is not having used social media in a while' 

The correlation table illustrates that 'average time spent on social media per day' is not highly correlated with any of the self-reported mental health problems such as being bothered by worries, having difficulty concentrating, feeling depressed or down, and facing issues regarding sleep. In the correlation table, the highest correlation that 'average time spent on social media per day' has with another variable is with 'feeling restless if one is not having used social media in a while', which is 0.396. It is followed by 'finding oneself using social media without a specific purpose', which is 0.389. The other variable of interest, which is somehow an indicator of social media addiction, is 'finding oneself using social media without a specific purpose', the highest correlation of it is with the variable 'getting distracted by social media when one is busy doing something', which is 0.463, followed by 'average time spent on social media per day', which already mentioned above (0.389). The next variable of interest is 'getting distracted by social media when one is busy doing something', it is highly correlated with 'how easily one is distracted' with a correlation coefficient of 0.607. The second-highest correlation it has is with the variable 'finding it difficult to concentrate' which is 0.528 followed by 'feeling restless when not having used social media for a while' with a correlation coefficient of 0.513. The next variable of interest is 'feeling restless when not having used social media for a while', which also is an indicator of being addicted to social media. This variable has the highest correlation with 'how easily distracted one is' which has a correlation coefficient of 0.515, it is followed by a correlation with 'getting distracted by social media when one is busy doing something' with a score of 0.513.

The third-highest correlation of this variable is with 'finding difficulty to concentrate on things' with a score of 0.469. In the above, we discussed mostly the variables that show how much time one spends on social media how attached one is to social media, and how they correlate with the self-reported problems of mental health and well-being. It is clear that except for the average time spent on social media daily, other variables have a moderate correlation within themselves and with some of the self-reported mental health problems. In the following paragraphs, we discuss how these problems are correlated with the above variables.

To continue our discussion of the correlation table, we now concentrate more on self-reported mental health. We can see in the table that the variable 'how easily distracted one is' has the highest correlation with 'finding difficulty to concentrate' with a score of 0.663, which is intuitive as both are pointing to the same problem. The other highest correlation of this variable is with 'getting distracted by social media when one is busy doing something' and 'feeling restless when not having used social media for a while', with correlation coefficients of 0.607 and 0.515 respectively.

The next variable in our list is 'how much one is bothered by worries', which has the highest correlation with 'feeling depressed or down' and 'finding difficulty to concentrate on things' with scores of 0.589 and 0.546 respectively, which also intuitive. However, it correlates lower than 35% with variables related to social media use and attachment.

Another variable that indicates a mental health problem is 'finding difficulty to concentrate on things'. This variable is moderately correlated with another indicator of mental health and also has a moderate correlation with these social media-related variables: 'getting distracted by social media when one is busy doing something' and 'feeling restless if one has not used social media in a while', with scores of 0.528 and 0.469 respectively.

 
Another variable related to mental health is 'seeking validation from features of social media', which has a low correlation with all the variables below 0.3. In addition, 'feeling depressed or down' also has a low correlation with variables related to social media use or attachment, which is below 0.4. Furthermore, the correlation of 'fluctuation of interest in daily activities' with the time spent on social media and attachment to social media variables is also low, below 0.4. Similarly, 'facing issues regarding sleep' is also weakly correlated with social media-related variables, below 0.3.

---

## Visual analysis:

To further enhance our understanding of the correlation between social media variables and mental health, we tried to visualize it by drawing some scatter plots. Figure 1 illustrates how variables 'getting distracted by social media when one is busy doing something' versus 'how easily distracted one is' are related. The scatter plot does not help us in understanding the correlation well.

Figure 1:
scatter plot of variable 10 versus 12 Screenshot 2024-02-21 194259
![Screenshot 2024-02-21 194259](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/043c8d60-1ac9-4b69-9848-de0a7c3db410)![image](https://github.com/MIT-Emerging-Talent/2024-group-04-cdsp/assets/155782968/79c193eb-5083-4d1b-b10a-50a25cc69082)


We also tried to understand if disaggregation by gender can explain it better. Figure 2 shows that even disaggregation by gender does not reveal a clear pattern that can enhance the correlation analysis, although these two variables are moderately correlated and their correlation coefficient is 0.607.

Figure 2: scatter plot of variable 10 versus 12 by gender disaggregation Screenshot 2024-02-21 194317
![Screenshot 2024-02-21 194317](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/8c786fc5-fcd5-4a3f-a2b3-7ecdfcbcb52e)![image](https://github.com/MIT-Emerging-Talent/2024-group-04-cdsp/assets/155782968/3ff62b4e-b399-45fe-a49a-54cbcd75bebc)


We are curious to see if other variables' correlation changes with gender disaggregation. To do so, we examined by drawing Figure 3 which plots the data of variables 8-14 and 18 versus each other.

Figure 3: scatter plot of variables 8-14 and 18 versus each other disaggregated by gender. Screenshot 2024-02-21 194539

Figure 3 illustrates that visually there is no clear pattern between different variables even when they are disaggregated by gender. However, it is possible to further analyze and come to a better conclusion with quantitative correlation analysis considering gender disaggregation.

Furthermore, we want to visualize and check how running regression and plotting regression lines can explain the relationship of social media variables with mental health variables. Therefore, we ran a regression for a single independent variable and plotted its line. Figure 4 illustrates the regression line of the variable 'finding oneself using social media without a specific purpose' and the variable 'how easily distracted one is'.

Figure 4: regression line with scatter plot of variable 9 versus 12 Screenshot 2024-02-21 194652
![Screenshot 2024-02-21 194539](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/93520d2d-520a-4c5c-93eb-b77d7a0d0dca)![image](https://github.com/MIT-Emerging-Talent/2024-group-04-cdsp/assets/155782968/e94a79be-1840-4a4d-b223-2af9b5dd52f3)


In Figure 4, we examine the relation of one social media variable as a regressor or independent variable and a mental health variable as a dependent or outcome variable. It depicts a positive but low relationship between the two variables, similar to the low correlation coefficient which is 0.356. Furthermore, the coefficient of the model is 0.39 with an intercept of 1.95 and an R-square of 0.13. The low R-square indicates that only 13% of the variation in the dependent variable can be explained by the independent variable.

Figure 4: regression line with a scatter plot of variable 9 versus 12
![Screenshot 2024-02-21 194652](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/bc45cd1a-be65-410c-9536-7326f6ff3d50)![image](https://github.com/MIT-Emerging-Talent/2024-group-04-cdsp/assets/155782968/62b6e110-4f3a-41dc-83ed-72e21ecf8c0c)

---

## Regression Analysis
To further analyze the relationship between what we call social media variables and mental health variables, we ran two types of regression: simple linear regression and multiple linear regression. In the simple linear regression, we calculated each social media variable as an independent variable and for each mental health variable as a dependent variable. However, we found that the variability of most of the mental health variables is not explained by the variability of social media variables. Most of the R-squares of these regressions are below 0.2, with some as low as 0.007 or lower. Only two mental health variables have R-squares above 0.2 with two social media variables:

1. 'How easily distracted one is' as a dependent variable and 'getting distracted by social media when one is busy doing something' as an independent variable has the highest R-square of the simple regressions we ran, which is 0.37. This means that the goodness of fit for this regression model is 37%. The coefficient and intercept are 0.54 and 1.56, respectively.

2. 'Finding difficulty to concentrate on things' as a dependent variable with the same independent variable as before has an R-square above 0.2 (i.e., 0.29) with coefficients and an intercept of 0.54 and 1.47, respectively.

The above two mentioned dependent variables, namely 'how easily distracted one is' and 'finding difficulty to concentrate on things', while 'feeling restless if one is not used social media in a while' being the independent variable, have R-square scores above 0.2 (i.e., 0.27 and 0.22, respectively) with coefficients of 0.48 and 0.5, as well as intercepts of 2.1 and 1.94, respectively.

To delve deeper and examine whether two or more of the social media variables together may explain the data better and improve the R-squared value, we conducted multiple linear regression models. However, we found that even multiple linear regression did not significantly improve the R-squared values for most of the dependent variables, except for those two variables with R-squared values higher than 0.2 in simple linear regression. One exception was the variable 'fluctuation of interest in daily activities,' which showed an improved R-squared value in multiple linear regression, rising above 0.2.

We ran three types of multiple linear regressions. First, we ran a model for each dependent variable with all four social media variables as independent variables. In the second step, noticing that the variable 'average time spent on social media' had p-values greater than 0.05, and in some cases even greater than 0.1, with coefficients not exceeding 0.13, indicating statistical insignificance, we omitted this variable and ran our regression with the three remaining social media variables. Again, we observed that the variable 'finding oneself using social media without a specific purpose' also suffered from statistical insignificance in most models, so we omitted this variable as well and ran another regression with two social media variables as independent variables.

In the last regression model with two independent variables, the results were as follows: The dependent variable 'how easily distracted one is' with independent variables 'getting distracted by social media when one is busy doing something' and 'feeling restless if one is not having used social media in a while' had an adjusted R-squared value of 0.42, with coefficients of 0.41 and 0.26 for each independent variable, respectively, and an intercept of 1.31, with p-values of 0.000 for all three variables. The next dependent variable with a higher R-squared value above 0.2 was 'finding difficulty to concentrate on things,' with the same independent variables as before, showing an adjusted R-squared value of 0.33, with coefficients of 0.39 and 0.29 and an intercept of 1.19, with p-values of 0.000 for all three variables.


Another dependent variable that had an R-squared value below 0.2 in simple regression but showed improvement as a result of multiple linear regression is 'fluctuation of interest in daily activities,' with the same independent variables as in the previous two models. The adjusted R-squared value is 0.2, with coefficients of 0.22 and 0.18 and an intercept of 1.23, with p-values of 0.000 for all three variables.

---

Conclusion:
The data in this study shows that 'average time spent on social media per day' has a low correlation with mental health problems, while three other variables related to social media attachment are moderately correlated with some mental health issues such as 'how easily distracted one is' and 'finding difficulty to concentrate on things'. However, other mental health problems have a low correlation with all the social media-related variables. Visual analysis and regression analysis also confirm the relationships found in the correlation analysis.

---
---

 ## Below are additional articles related to the topic:

### Social Media Use and Depression and Anxiety Symptoms: A Cluster Analysis

This study examined social media use (SMU) patterns among a nationally representative sample of 19-to-32-year-olds in the US and their associations with depression and anxiety symptoms. Using cluster analysis, five distinct SMU patterns were identified based on time spent on social media, frequency of site visits, multiple platform use, problematic social media use (PSMU), and social media intensity (SMI). Two patterns, labeled "Wired" and "Connected," showed the highest risk for depression and anxiety symptoms. The other three patterns did not show significant associations with these symptoms. The findings suggest that understanding patterns of SMU rather than individual characteristics may be more useful in identifying those at risk for mental health issues and in developing interventions.

Read the full article [here!](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5904786/)

---

### A systematic review: the influence of social media on depression, anxiety and psychological distress in adolescents

This systematic review investigated the relationship between social media use and mental health issues in adolescents. It analyzed 13 studies, with depression being the most commonly studied outcome. The review found that factors such as time spent on social media, specific activities like constant message checking, personal investment, and addictive or problematic use were associated with depression, anxiety, and psychological distress in adolescents. However, the review emphasized the need to differentiate between association and causation, noting that while there is evidence of an association between social media use and mental health problems, causation has not been definitively established. The review categorized key findings into four exposure categories: time spent, activity, investment, and addiction, all of which were correlated with mental health issues. It also identified gaps in the literature, such as methodological shortcomings and a lack of exploration of certain mediators and moderators of the relationship. The review calls for further research to better understand the complex relationship between social media use and adolescent mental health.

Read the full article [here!](https://www.tandfonline.com/doi/full/10.1080/02673843.2019.1590851)
