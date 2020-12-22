# University Data Exploration

## Project Motivation
I wanted to improve my skills in data manipulation and just my overall ability to wrangle data using pandas. I also wanted to add a matplotlib graph. Some of the questions I answered were about trends in racial diversity, gender breakup and graduation rates from the data.

## File Description
I used a csv called 'University_Admission.csv' that I found on kaggle. Here is the link to it: https://www.kaggle.com/samsonqian/college-admissions
I also made a jupyter notebook called 'University_Admission.ipynb' where I did all of my analysis.

## Libraries Used
Numpy, Pandas, matplotlib and sklearn

## Results of the analysis
To read about the results: you can visit https://rohitkumar-31980.medium.com/which-colleges-are-the-most-racially-diverse-ef818bf94b6a.

## CRISP-DM Process
<b> Business Understanding:</b> From the datasets I wanted to gain a better understanding of the demographics of colleges. Where exactly does each race go for college. Four business aspect questions were asked before diving into the dataset:

(1) Which colleges have an abnormal amount of women and minorities?
(2) What are some colleges with a lot of racial diversity?
(3) What factors correlated (positively and negatively) with racial diversity?
(4) What factors correlated (positively and negatively) with graduation rates?
 
 <b> Data Understanding：</b> The data contains 108 different columns giving information about the profile of their college, including tuition, demographics, average SAT score, yeild rate, etc. There were 1534 different universities.
 
<b> Prepare Data: </b> I took out rows with a significant number of missing values (NaN), created dummy variables, used zero fill, and used mean fill. More is explained in the notebook.

<b> Data Modeling: </b> I did not create any machine learning models. 

<b> Evaluate the Results: </b> Result and discussion are published in https://rohitkumar-31980.medium.com/which-colleges-are-the-most-racially-diverse-ef818bf94b6a and inside the notebook.
