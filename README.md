# Customer Segmentation Analysis for a fitness company using Fitness Tracker data in excel 
<details>
  <summary><h2>TABLE OF CONTENTS</h2></summary>

  - [OBJECTIVE](#obj)
  - [PREREQUISITE](#pre)
  - [IMPLEMENTATION](#imp)
  - [RESULT](#res) 

</details>

<a id="obj"></a>
### OBJECTIVE
This data analysis project aimed to identify potential clients for a fitness company by leveraging data collected from FitBit fitness tracker. The business sells specialized dietary plans, fitness gears and apparels. They also have an app to track customers' sleeping habits. 

<a id="pre"></a>
### PREREQUISITE 

- Knowledge of Pivot Tables
- Conditional Formatting
- Data Visualization
- Understanding of Advanced functions such as XLOOKUP

<a id="imp"></a>
### IMPLEMENTATION

1. <u>Data collection</u> :
   This dataset was downloaded from Kaggle where it was uploaded by Möbius. These datasets were generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016 - 05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. Individual reports can be parsed by export session ID (column A) or timestamp (column B). Variation between output represents use of different types of Fitbit trackers and individual tracking behaviors/preferences. [See the source](https://zenodo.org/record/53894#.Y7PTU3ZBy3C "The Fitness Tracker Dataset")

2. <u>Data Pre-processing</u> :
    To ensure data integrity and accuracy, I cleaned the data by removing duplicates, handling missing values and standardizing the data format.

3. <u>Exploratory Data Analysis</u> :
   After identifying distinct individuals, they were categorized based on their usage of the fitness tracker on different days of the month as Light, Moderate and Active Users based on certain criteria. I used pivot tables to find the  Mean distance covered by each user and the calories burned, using which I created a line chart to show the relationship between total number of steps taken and calories burned.
   With the help of heart rate data, I was able to identify clients who can buy the personalized dietary plan. For example, if the heartbeat of a person exceeds 185 or 200 beats per minute, during exercise, then they are susceptible to heart diseases such as heart attack. This can be avoided by following a healthy weight plan. So, I used advanced filter options to filter out clients who are most likely to buy this weight plan by analyzing their heartrate.
    Similarly using the BMI data, I classified the users into normal, overweight and obese using conditional formatting and created a pie chart to depict the percentage of users belonging to each category. After thorough analysis of the ActiveMinutes data, I was able to conclude that individuals with over 1 hour of Active Minutes and less than 10 minutes of sedentary minutes are bound to buy the company's fitness apparels. Furthermore, I summarized the sleep habits data of every user into a pivot table to spot potential clients for the company's sleep tracker app and personalized subscriptions to track their sleep.

<a id="res"></a>
### RESULT
By using Excel's data analysis capabilities effectively, I successfully drew beneficial insights to help the company target potential customers. 

    
   

