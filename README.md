
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
In the correaltion table it illustrate that average time spent on social media per day is not highly correlated with any of the self reported mental health problems such as being bothered by worries, finding difficult to concentrate, feeling depressed or down and facing issues regardign sleep. In the correlation table the highest correlation that 'average time spent on social media per day' has with other varibable is with 'feeling restless if one is not having used social media in a while' which is 0.396. It is followed by 'finding oneself using social media without a specific purpose' which is 0.389.
The other variable of interest which is somehome an indicator of social media addection is 'finding oneself using social media without a specific purpose', the highest correlation of it is with variable 'getting distructed by social media when one is busy doing something' which is 0.463, followed by 'average time spent on social media per day' which already mentioned above (0.389). 


## Contributors 
Hannamariam, Mahdi Gholami, Mahnaz Nabizada, Rohollah Mohammadi,  

Sediqe Mohammadi, Zainab Hussaini, Hossain Ali Dornam

 

## License 
MIT License. 
