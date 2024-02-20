
# MIT-Emerging-Talent-group-04
This is a Collaborative Data Science project within the Emerging Talent program. For many of us in this group, it marks our first venture into this field. Our primary goal is to learn effective collaboration despite challenges such as varying time zones and remote work, utilizing diverse tools. Additionally, we aim to explore the synergy between data science methodologies and domain expertise to foster new insights. Our focus is on translating these insights into practical real-world solutions.
# Social Media and Mental Health 
## Domain
### Health
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
(the rest of it, is writing soon...)

#### Possible Source of Error
Potential sources of errors in this study primarily stem from the data collection process. The dataset mainly comprises responses from individuals, predominantly students, which could introduce significant biases. It's plausible that mental health issues observed might be influenced by factors beyond social media use, such as university tuition fees and exam pressures.

To mitigate these potential biases and broaden the scope of the analysis, it's essential to gather more extensive and diverse data samples from various social groups. This would provide a more comprehensive understanding of the relationship between social media usage and mental health across different demographics and help to isolate the specific impacts of social media from other potential influences.
### Techniacal Explanation
The following are variable names:
    '1. What is your age?', 
    '2. Gender',
    '3. Relationship Status', '4. Occupation Status',
    '5. What type of organizations are you affiliated with?',
    '6. Do you use social media?',
    '7. What social media platforms do you commonly use?',
    '8. What is the average time you spend on social media every day?',
    '9. How often do you find yourself using Social media without a specific purpose?',
    '10. How often do you get distracted by Social media when you are busy doing something?',
    '11. Do you feel restless if you haven't used Social media in a while?',
    '12. On a scale of 1 to 5, how easily distracted are you?',
    '13. On a scale of 1 to 5, how much are you bothered by worries?',
    '14. Do you find it difficult to concentrate on things?',
    '15. On a scale of 1-5, how often do you compare yourself to other successful people through the use of social media?',
    '16. Following the previous question, how do you feel about these comparisons, generally speaking?',
    '17. How often do you look to seek validation from features of social media?',
    '18. How often do you feel depressed or down?',
    '19. On a scale of 1 to 5, how frequently does your interest in daily activities fluctuate?',
    '20. On a scale of 1 to 5, how often do you face issues regarding sleep?'
As the name of the varibales are long in the bellow table we only use their variable number.
Table 1: Correlation matrix 
|     | 8       | 9      | 10       | 11      | 12      | 13     | 14       | 15     |  16   | 17        | 18      | 19      | 20      |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 8   | 1.00000 | 0.38898 |0.36957 | 0.39590 | 0.33383 | 0.31925 | 0.31242 |0.19380 |  0.05240| 0.10714 | 0.32628 | 0.28820 | 0.16987 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 9   |         | 1.0000 |  0.46335| 0.35903 | 0.36549 | 0.25208 | 0.28882 |0.14820 | 0.08764| 0.14451 | 0.31547 | 0.35937 | 0.26049 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 10  |         |        | 1.0000 | 0.513354 | 0.60741 | 0.34330 | 0.52774 |0.28850 | 0.07806| 0.27014 | 0.37944 | 0.38913 | 0.25536 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 11  |         |        |         | 1.0000 | 0.51480 | 0.34703 | 0.46944 |0.32097 |  0.13419| 0.24592 | 0.32896 | 0.38477 | 0.16660 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 12  |         |        |         |         | 1.0000 | 0.46267 | 0.66276 |0.28612 | 0.01463 | 0.17258 | 0.40766 | 0.47999 | 0.29114 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 13  |         |        |        |         |         | 1.0000 | 0.54590 | 0.41430 | 0.02058 | 0.20884 | 0.58875 | 0.43034 | 0.32736 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 14  |         |        |         |         |         |         | 1.0000 | 0.37115 | 0.06074| 0.24203 | 0.50979 | 0.50319 | 0.35467 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 15  |         |        |         |         |        |         |         | 1.0000 |  -0.01146 | 0.41732 | 0.41780 | 0.37424 | 0.19371 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 16  |         |        |         |         |         |         |         |        | 1.0000 | 0.15357 | 0.03547 | 0.04615 | 0.06851 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 17  |         |        |         |         |         |         |         |        |         | 1.0000 | 0.27212 | 0.27857 | 0.12889 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 18  |         |        |        |         |         |         |         |        |        |         | 1.0000 | 0.49497 | 0.37472 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 19  |         |        |         |         |         |         |         |        |         |         |         | 1.0000 | 0.31924 |
| :-: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | 
| 20  |         |        |        |        |         |         |         |        |         |         |         |         | 1.0000 |

There are four variables that in this study we consider them as sociala media related variables, they are as following:
A) Time spent on social media: 'average time spent on social media per day'
B) Attachment to the social media: 'finding oneself using social media without a specific purpose', 'getting distructed by social media when one is busy doing something' and 'feeling restless if one is not having used social media in a while'

In the correaltion table it illustrate that 'average time spent on social media per day' is not highly correlated with any of the self reported mental health problems such as being bothered by worries, finding difficult to concentrate, feeling depressed or down and facing issues regarding sleep. In the correlation table the highest correlation that 'average time spent on social media per day' has with other varibable is with 'feeling restless if one is not having used social media in a while' which is 0.396. It is followed by 'finding oneself using social media without a specific purpose' which is 0.389.
The other variable of interest which is somehome an indicator of social media addection is 'finding oneself using social media without a specific purpose', the highest correlation of it is with variable 'getting distructed by social media when one is busy doing something' which is 0.463, followed by 'average time spent on social media per day' which already mentioned above (0.389). Next variable of interest is 'getting distructed by social media when one is busy doing something', it is highly correlated with 'how easily one is distructed' with the correlation coefficeint of 0.607. The second highest correlation it has is with variable 'finding dificult to concentrate' which is 0.528 followed by 'feeling restless when not having used social media for a while' with the correlation coeficient of 0.513. The next variable of interest is 'feeling restless when not having used social media for a while', which also is an indicator of being addected to social media, loosly speaking. This variable has a highest correlation with 'how easily distructed one is' which has a correlation coefficient of 0.515, if is followed by correlation with 'getting distructed by social media when one is busy doing something' with score of 0.513. The third highest correlation of this variable is with 'finding difficult to concentrate on things' with score of 0.469. 
In the above we disscussed mostly the variables that are showing how much time one spent on social media and how attached one is to social media and how they correlate with the self reported problems of mental health and well-being. It is clear that except average time spent on social media on daily basis other variables have moderate correlation within themsleves and with self reported mental health problems. In following paragraphs we dissuss how these problems are correlated with the above variables. 

To continue our discussion of correlation table now we concentrate more on self reported mental health, we can see in the table that the variable 'how easily distructed one is' has highest correlation with 'finding difficult to concentrate' with score of 0.663 which is intuitive as both are pointing to the same problem. The other highest correlation of this variable is with 'getting distructed by social media when one is busy doing something' and 'feeling restless when not having used social media for a while' with correlation coefficients of 0.607 and 0.515 repsectively. The next variable in our list is 'how much one is bother by worries' which has highest correlation with 'feeling depressed or down' and 'finding difficult to concentrate on things' with score of 0.589 and 0.546 respectively, which is also intuitive. However it has lower than 35 % correlation with variables related to social media use and attachment. Another variable that indicate mental health problem is 'finding difficult to concentrate on things' this variable too is moderately correlated with other indicator of mental health and also has moderate correaltion with these social media related variables  'getting distructed by social media when one is busy doing something' and 'feeling restless if one is not having used social media in a while' with score of 0.528 and 0.469 respectively. 
Another variable which shows related to mental health is 'seeking validation from features of social medis' which has low correlation with all the variables bellow 0.3. In addition 'feeling depressed or down' also have low correlation with variables related to social medai use or atachment which is bellow 0.4, furthermore correlation of 'flactuation of interest in daily activities' with the mentioned variables are also low bellow 0.4. In the same manner the 'facing issues regarding sleep' is also lowly correlated with social media related variables bellow 0.3. 

Conclusion: The data in this study shows that 'average time spent on social media per day' has low correlation with mental health problems while three other variables which are related to social media atachment are moderately correlated with some of the variables of mental health issues such as 'how easily distructed one is' and 'finding difficult to concentrate on things'. However other mental health problems has low correlation all the social media related variables.  

## Contributors 
Hannamariam, Mahdi Gholami, Mahnaz Nabizada, Rohollah Mohammadi,  

Sediqe Mohammadi, Zainab Hussaini, Hossain Ali Dornam

 

## License 
MIT License. 
