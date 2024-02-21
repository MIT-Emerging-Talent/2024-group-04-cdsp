
# MIT-Emerging-Talent-group-04
This is a Collaborative Data Science project within the Emerging Talent program. For many of us in this group, it marks our first venture into this field. Our primary goal is to learn effective collaboration despite challenges such as varying time zones and remote work, utilizing diverse tools. Additionally, we aim to explore the synergy between data science methodologies and domain expertise to foster new insights. Our focus is on translating these insights into practical real-world solutions. This group consist of people from diffirent backgrounds and with different exposures to data and data analyis. We tried learn from each other and make the experience more of a learning, and coordiantion experience. 
# Social Media and Mental Health 
Scial media refers to the online platforms and websites that allow user to create their own profile, engage with other people through creating and sharing contents like text, image, videos and links. Social media allow people to socialize virtually with others, communicate, network, consume news and share ideas without physically comeing together. Beside its advantage of facilitating virtual socialization it comes with many different costs and problems in terms of mental health issues, syberbully and harassment, social media attachment or addiction, comperason and low-self steem. One of the major problems that is more concerning is its nagative effects on mental health. By mental health we mean psyclological, emotional and social well-being of a person that effects how he/she thinks, feels, behaves, handles stresses and relates to other people and sroundings. Social media over use is expected to have negative effects on menthal health causing social isolation, loneliness and anxiety. In this study we aim to explore how social media usage correlates with mental health problems.  
## Domain
Health 
## Project Overview 
 Our project aims to explore the relationship between time spent on social media platforms and mental health outcomes. With the increasing prevalence of social media use globally, understanding its potential impact on mental well-being has become a significant area of interest. This project seeks to contribute to the existing body of knowledge by conducting a comprehensive analysis of this correlation.


## Problem Statement
Human beings are inherently social and rely on connections with others to alleviate stress, anxiety, and sadness, with a lack of social interaction posing significant risks to mental health. Today, virtual connections through social media platforms have become ubiquitous. A staggering 62.3% of the global population engages with social media, spending an average of 2 hours and 23 minutes daily (as of January 2024). While social media offers various positive benefits, experts express concerns over its potential negative impact on mental health, particularly among younger demographics. Mental health, as defined by the World Health Organization (WHO), is essential for individuals to effectively cope with life's challenges, fulfill their potential, and contribute to society. This project aims to explore the relationship between social media usage and mental health outcomes.


## Actionable data questions
To assess the impact of social media on mental health, we consider factors associated with mental health issues such as anxiety and sleep disturbances
1.Correlation between occupation status and average time spent on social media every day?
2. How much average time spent on social media may affect feeling down and depressed?
3.How does age correlate with the amount of time spent on social media and mental health outcomes?
4. Is there a difference in social media usage and its impact on mental health between genders
5.Is there a correlation between time spent on social media and focus problems
6.Is there any correlation between the time spent on social media and being worried and anxious
7.What is the relationship between concentration difficulties and social media usage


## Data 
This dataset was collected for a project to study if spending a lot of time on social media affects mental health. It was gathered through a survey. 

### Source Data 
The link to the dataset: https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health
 
### Data Acquisition 
The data was gathered through survey. It was done from 04/18/2022-11/12/2022

## Data Analysis
### Tools
For analyzing data we used Jupyter Notebook and packages like Pandas, Seaborn, Matplotlib, Sklearn.
### Data cleaning
In data cleaning we did not have any non-entry except for the variable 'Organization type' which was not used in the data analysis therefore there was not removal of any observation. As the variable 'average time spent on social media' was qualitative it was transformed to quantitative by taking the average of an interval for example instead 'between 2 to 3 hour' was replace by '2.5' in order to make analysis possible. Another minor change was that in variable 'gender' some entries were spelled incurrectly which was corrected for. 
## Results and evaluation 
### Non Technical Explanation
This study aimed to investigate whether social media usage correlates with mental health issues. We analyzed a dataset obtained from an online survey focused on this subject. The survey assessed various factors related to mental well-being, including difficulty sleeping, susceptibility to distraction, restlessness, anxiety, depression, comparison with others on social media, and disruption of daily routines.

A total of 481 individuals participated in the survey, ranging in age from 13 to 91 years old, with an average age of 26.1 years. Out of these participants, 478 reported using social media, while 3 individuals did not. On average, participants spent 3.5 hours per day on social media platforms.
There are four variables that in this study we consider as social media related variables, we categorize them in 2 groups : 1.Time spent on social media:’ average time spent on social media per day’, 2. Attachment to the social media: 'finding oneself using social media without a specific purpose', 'getting distracted by social media when one is busy doing something' and 'feeling restless if one is not having used social media in a while'
The data suggests that while average time spent on social media per day has low correlation with mental health problems, attachment to social media, particularly aspects related to social media addiction, shows moderate correlations with certain mental health issues such as difficulty concentrating and being easily distracted. However, seeking validation from social media features and feeling depressed or down have low correlation with social media related variables.


#### Possible Source of Error
Potential sources of errors in this study primarily stem from the data collection process. The dataset mainly comprises responses from individuals, predominantly students, which could introduce significant biases. It's plausible that mental health issues might be influenced by factors beyond social media use, such as university tuition fees and exam pressures.

To mitigate these potential biases and broaden the scope of the analysis, it's essential to gather more extensive and diverse data samples from various social groups. This would provide a more comprehensive understanding of the relationship between social media usage and mental health across different demographics and help to isolate the specific impacts of social media from other potential influences.
### Techniacal Explanation
The following are variable names:
   1. What is your age?, 
   2. Gender,
   3. Relationship Status,
   4. Occupation Status,
   5. What type of organizations are you affiliated with?,
   6. Do you use social media?,
   7. What social media platforms do you commonly use?,
   8. What is the average time you spend on social media every day?,
   9. How often do you find yourself using Social media without a specific purpose?,
   10. How often do you get distracted by Social media when you are busy doing something?,
   11. Do you feel restless if you haven't used Social media in a while?,
   12. On a scale of 1 to 5, how easily distracted are you?,
   13. On a scale of 1 to 5, how much are you bothered by worries?,
   14. Do you find it difficult to concentrate on things?,
   15. On a scale of 1-5, how often do you compare yourself to other successful people through the use of social media?,
   16. Following the previous question, how do you feel about these comparisons, generally speaking?,
   17. How often do you look to seek validation from features of social media?,
   18. How often do you feel depressed or down?,
   19. On a scale of 1 to 5, how frequently does your interest in daily activities fluctuate?,
   20. On a scale of 1 to 5, how often do you face issues regarding sleep?

As the name of the varibales are long in the bellow table we only use their variable number.
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

There are four variables that in this study we consider them as social media related variables, they are as following:
  A) Time spent on social media: 'average time spent on social media per day'
  B) Attachment to the social media: 'finding oneself using social media without a specific purpose', 'getting distracted by social media when one is busy doing something' and 'feeling restless if one is not having used social media in a while'

In the correlation table it illustrates that 'average time spent on social media per day' is not highly correlated with any of the self reported mental health problems such as being bothered by worries, finding difficulty to concentrate, feeling depressed or down and facing issues regarding sleep. In the correlation table the highest correlation that 'average time spent on social media per day' has with other variable is with 'feeling restless if one is not having used social media in a while' which is 0.396. It is followed by 'finding oneself using social media without a specific purpose' which is 0.389.

The other variable of interest which is somehow an indicator of social media addiction is 'finding oneself using social media without a specific purpose', the highest correlation of it is with variable 'getting distracted by social media when one is busy doing something' which is 0.463, followed by 'average time spent on social media per day' which already mentioned above (0.389). Next variable of interest is 'getting distracted by social media when one is busy doing something', it is highly correlated with 'how easily one is distracted' with the correlation coefficient of 0.607. The second highest correlation it has is with variable 'finding difficult to concentrate' which is 0.528 followed by 'feeling restless when not having used social media for a while' with the correlation coefficient of 0.513. The next variable of interest is 'feeling restless when not having used social media for a while', which also is an indicator of being addicted to social media. This variable has the highest correlation with 'how easily distracted one is' which has a correlation coefficient of 0.515, it is followed by correlation with 'getting distracted by social media when one is busy doing something' with a score of 0.513. The third highest correlation of this variable is with 'finding difficulty to concentrate on things' with a score of 0.469. 

In the above we discussed mostly the variables that are showing how much time one spent on social media and how attached one is to social media and how they correlate with the self reported problems of mental health and well-being. It is clear that except average time spent on social media on daily basis other variables have moderate correlation within themselevs and with some of self reported mental health problems. In the following paragraphs we discuss how these problems are correlated with the above variables. 

To continue our discussion of correlation table now we concentrate more on self reported mental health, we can see in the table that the variable 'how easily distracted one is' has the highest correlation with 'finding difficulty to concentrate' with score of 0.663 which is intuitive as both are pointing to the same problem. The other highest correlation of this variable is with 'getting distracted by social media when one is busy doing something' and 'feeling restless when not having used social media for a while' with correlation coefficients of 0.607 and 0.515 respectively. The next variable in our list is 'how much one is bother by worries' which has the highest correlation with 'feeling depressed or down' and 'finding difficulty to concentrate on things' with a score of 0.589 and 0.546 respectively, which is also intuitive. However it has lower than 35 % correlation with variables related to social media use and atachment. Another variable that indicates mental health problem is 'finding difficulty to concentrate on things' this variable too is moderately correlated with other indicator of mental health and also has moderate correlation with these social media related variables  'getting distracted by social media when one is busy doing something' and 'feeling restless if one is not having used social media in a while' with score of 0.528 and 0.469 respectively. 

Another variable which shows related to mental health is 'seeking validation from features of social media' which has low correlation with all the variables bellow 0.3. In addition 'feeling depressed or down' also have low correlation with variables related to social media use or attachment which is bellow 0.4, furthermore correlation of 'fluctuation of interest in daily activities' with the time spent on social media and atachment to social media variables are also low bellow 0.4. In the same manner the 'facing issues regarding sleep' is also lowly correlated with social media related variables bellow 0.3. 

Conclusion: The data in this study shows that 'average time spent on social media per day' has low correlation with mental health problems while three other variables which are related to social media attachment are moderately correlated with some of the variables of mental health issues such as 'how easily distracted one is' and 'finding difficulty to concentrate on things'. However other mental health problems have low correlation with all the social media related variables.  

# Visual analyis:
In order to further enhance our understanding of the correlation between social media variables and mental health variable we tried to visualize it by drawing some scatter plots, figure 1 illustrtes how variables 'getting distracted by social media when one is busy doing something' versu 'how easily distracted one is' are going along. The scatter plot does not help us in understanding the correlation well. 

Figure 1: scatter plot of variable 10 versu 12
![Screenshot 2024-02-21 194259](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/043c8d60-1ac9-4b69-9848-de0a7c3db410)

We also tried to understand if disaggregation by gender can explain it better. Figure 2 shows that even disaggregation by gender do not make a clear pattern that can enhance the correlation analysis. Although  these two variables are moderately correlated and their correlation coefficient is 0.607. 

Figure 2: scatter plot of variable 10 versus 12 by gender disaggregation
![Screenshot 2024-02-21 194317](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/8c786fc5-fcd5-4a3f-a2b3-7ecdfcbcb52e)

We are curious to see if other variables' correlation change by gender disaggregation. To do so we examined by drawing figure 3 which plots the data of variables 8-14 and 18 versus each other. 

Figure 3: scatter plot of variables 8-14 and 18 versus each other disaggregated by gender.
![Screenshot 2024-02-21 194539](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/93520d2d-520a-4c5c-93eb-b77d7a0d0dca)

Figure 3 illustrates that visually there is no any clear pattern between different variables even when it is disaggregated by gender. However it is possible to further analyze and come with a better conclussion with quantitative correlation analysis considering gender disaggreation. 

Further more we want to visualize and check how runing regression and ploting regression line can explain the relationship of the social media variables with mental health variables. Therefore we run regression for a single independent variable and draw its line.
Figure 4 illustrate the regression line of variable 'finding oneself using social media without a specific purpose' and variable 'how easily distracted one is' 

Figure 4: regression line with scatter plot of variable 9 versus 12
![Screenshot 2024-02-21 194652](https://github.com/MIT-Emerging-Talent/2024-group-10-collaboration-practice/assets/147745327/bc45cd1a-be65-410c-9536-7326f6ff3d50)

In figure 4 we examine the relation of one social media variable as regressor or independent variable and a mental health variable as dependent or outcome variable. It depect a positve but low relationship between the two variables similar to the low correlation coeficeint which is 0.356. 

## Contributors 
Hannamariam, Mahdi Gholami, Mahnaz Nabizada, Rohollah Mohammadi,  

Sediqe Mohammadi, Zainab Hussaini, Hossain Ali Dornam

 

## License 
MIT License. 
