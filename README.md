# Stackoverflow-survey-analysis-Udacity-DSN-project
Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

1. Project was built on Python. Used libraries in the project are:
 - Pandas for data manipulation purposes
 - Numpy for arithmetic calculation
 - Matplotlib for data visualization
 
2. This project dedicated to analysis of stackoverflow survey data. Main aim of the project is to find out career satisfaction across countires, professions and undergraduate majors
Exploratory data analysis techniques were used to analyze data. I used pandas and matplotlib libraries which contains data manipulation and plotting functions. Pandas is used for aggregation (finding mean, sum by groups), filtering (removing rows with missing values and matplotlib is used for plotting histograms (to see distribution of values), scatterplots and etc.

3. The file contain survey data gathered in 2017 and conducted by Stackoverflow. It has 51392 rows and 154 columns. Columns that have missing values less 20% were kept for analysis and these columns are: 

Respondent
Professional
ProgramHobby
Country
University
EmploymentStatus
FormalEducation
MajorUndergrad
HomeRemote
YearsProgram
CareerSatisfaction
PronounceGIF
ClickyKeys

4. Results
## Based on our data we can conclude the following:

 - Generally professional developers happier in their career
 - Some small countries (by population) like Israel, Lithuania have enough respondents
 - Developers in the USA, Israel, Mexico and Canada are happier than in other countries. Developers in Italy, Turkey and India seems less happier with their career
 - Respondents with business and social sciences undergraduate majors are happier than respondets with computer science related undergrad
 
5. Credits must be given to Stack Overflow for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available https://www.kaggle.com/stackoverflow/so-survey-2017 
