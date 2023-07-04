# BellaBeat Capstone - Sheets, SQL &amp; Tablea

### Google Data Analytics BellaBeat Capstone - Sheets, SQL & Tableau


1. Table Of Contents
    - a. Case Study Summary
    - b. Introduction
    - c. Scenario
    - d. Characters & Products
    - e. About The Company

2. Ask Phase
    - a. Business Task
    - b. Identifying Key Stakeholders
    - c. Prepare Phase

3. Data Used
    - a. Data Organization
    - b. Data Summary
    - c. Data Credibility
    - d. Problems With The Data

4. Process Phase
    - a. Chosen Data Sets
    - b. Data Cleaning With Google Sheets
    - c. Clean Data Shared File & Next Steps


5. Analyze Phase / Visualizations With Sheets
    - a. Uploaded CSV Files Into BigQuery (SQL)
    - b. User Verification
    - c. Proposed Questions, Query Performed, Resulting Data Sets & Insights
    - d. Active Minutes Per User
    - e. Steps Per Day Per User
    - f. Calories Consumed Per Day Per User

6. Share Phase / Visualizations With Tableau Dashboard
    - a. Tableau Dashboard

7. Act Phase
    - a. Final Conclusions & Recommendations
    - b. Closing Thoughts


### 1. Case Study Summary

#### _a. Introduction_
Welcome to the Bellabeat data analysis case study! In this case study, you will perform many real-world tasks of a junior data analyst. You will imagine you are working for Bellabeat, a high-tech manufacturer of health-focused products for women, and meet different characters and team members. In order to answer the key business questions, you will follow the steps of the data analysis process: ask, prepare, process, analyze, share, and act. Along the way, the Case Study Roadmap tables — including guiding questions and key tasks — will help you stay on the right path. By the end of this lesson, you will have a portfolio-ready case study. Download the packet and reference the details of this case study anytime. Then, when you begin your job hunt, your case study will be a tangible way to demonstrate your knowledge and skills to potential employers.



#### _b. Scenario_
You are a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights you discover will then help guide the marketing strategy for the company. You will present your analysis to the Bellabeat executive team along with your high-level recommendations for Bellabeat’s marketing strategy.



#### _c. Characters & Products_

**Characters**

**○ Urška Sršen:** Bellabeat’s co-founder and Chief Creative Officer

**○ Sando Mur:** Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team

**○ Bellabeat marketing analytics team:** A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy. You joined this team six months ago and have been busy learning about Bellabeat’s mission and business goals — as well as how you, as a junior data analyst, can help Bellabeat achieve them.

**Products**

**○ Bellabeat app:** The Bellabeat app provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness products.

**○ Leaf:** Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf Tracker connects to the Bellabeat app to track activity, sleep, and stress.

**○ Time:** This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.

**○ Spring:** This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.

**○ Bellabeat membership:** Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health, and beauty, and mindfulness based on their lifestyle and goals.

#### _d. About The Company_
About the company Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. By 2016, Bellabeat had opened offices around the world and launched multiple products. Bellabeat products became available through a growing number of online retailers in addition to their own e-commerce channel on their website. The company has invested in traditional advertising media, such as radio, out-of-home billboards, print, and television, but focuses on digital marketing extensively. Bellabeat invests year-round in Google Search, maintains active Facebook and Instagram pages, and consistently engages consumers on Twitter. Additionally, Bellabeat runs video ads on Youtube and display ads on the Google Display Network to support campaigns around key marketing dates. Sršen knows that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, using this information, she would like high-level recommendations for how these trends can inform Bellabeat's marketing strategy.



### 2. Ask Phase
#### _a. Business Task_
Analyze the data the "FitBit Fitness Tracker Data" to gain insight into how people are using their devices, in order to identify trends that can be used in Bellabeat's marketing strategy.

#### _b. Identifying Key Stakeholders_
**○ Urška Sršen:** Bellabeat’s co-founder and Chief Creative Officer

**○ Sando Mur:** Mathematician and Bellabeat’s cofounder; a key member of the Bellabeat executive team

**○ Bellabeat marketing analytics team:** A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy.



### 3. Prepare Phase
#### _a. Data Used_
The data that was used for this capstone was pulled from the “FitBit Fitness Tracker Data” and was directly downloaded from Kaggle.


#### _b. Data Organization_

The Data set was provided by a user called Mobius and is part of the public domain. The data was organized into 18 CSV files.


#### _c. Data Summary_
This dataset was generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring.


#### _d. Data Credibility_
Considering the data comes from a first-party source the data should be considered credible.


#### _e. Problems With The Data_
The “FitBit Fitness Tracker Data” has several problems that make drawing meaningful conclusions on it in relation to our business task impossible.


### 4. Process Phase
#### _a. Chosen Data Sets_
For this capstone, the following data sets were chosen from the “FitBit Fitness Tracker Data” to be used:

	-dailyActivity_merged
	-dailyCalories_merged
	-dailyIntensities_merged
	-dailySteps_merged
	-weightLogInfo_merged
	-sleepDay_merged

 
#### _b. Data Cleaning WIth Google Sheets_

Each of the table listed above were cleaned using google sheets, specifically the following changes were made:

	-Header row was frozen then data was sorted in ascending order based on ID for each table
	-Data clean up "Remove Duplicates" was used on each sheet - 3 duplicate rows were found in the table sleepDay_merged
	-Separated the Date column in table weightLogInfo_merged into a Date and Time column to preserve the data using the “split text to column tool”
	-Normalized formatting of dates across sheets into MM/DD/YY date format to ensure consistency
	-Formatted all numerical data into Number format with 2 decimal places
	-Sorted each table by date in ascending order to determine the length of time this data set contains data for
	-Formatted any time data into 00:00:00 format for consistency
	-The length of all ID numbers was tested to ensure accuracy
	-Pivot tables were created for each data set then COUNTUNIQUE function was used to confirm the number of unique rows in each data set


#### _c. Clean Data Shared Files & Next Steps_
Once my data was cleaned, I decided to use SQL to analyze it. The reason I chose to do this instead of staying in sheets or working in R was that I wanted more practice writing queries in SQL.

Despite my choice to use BigQuery, this analysis could have been done using Sheets, Excel, or R.

[Copy of cleaned data tables](https://docs.google.com/spreadsheets/d/1TLA8PGj6xoouE0aFrDxnotu--e7O6jzuEbGh3x1W33U/edit?usp=sharing)


### 5. Analyze Phase / Visualizations With Sheets
#### _a.Uploaded CSV Files Into BigQuery (SQL)_

The clean data sets were uploaded into BigQuery under a project named 'clean-athlete-388418.bellabeats', the specific data uploaded were:

	-dailyActivity_merged
	-dailyCalories_merged
	-dailyIntensities_merged
	-dailySteps_merged
	-weightLogInfo_merged
	-sleepDay_merged


#### _b. User Verification_

The data sets were verified by checking the total number of unique user ids.

**Query Performed:**
	
 	SELECT DISTINCT Id AS UniqueID 
	FROM `clean-athlete-388418.bellabeats.dailyintensities`

Each data set returned 33 unique Ids except sleepDay which returned 24 and weightLogInfo which returned 8 unique entries. Due to the number of unique entries for these tables being under 30, I will exclude their data.


#### _c. Proposed Questions, Queries Performed, Resulting Data Sets & Insights_

How often did each unique Id use/wear their fitbit?

**Query performed:**
	
 	SELECT Id,
	COUNT(Id) AS total_entries
	FROM `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets, and named "Daily Usage".

Next, I wanted to categorize each user based on how often they wore their FitBit, to do this I created 3 separate categories:

_Active Users-_ Wore their tracker for between 27 and 31 days
_Moderate Users-_ Wore their tracker for between 22 and 26 days
_Light Users-_ Wore their tracker for between 0 and 21 days

**Query performed:**

	SELECT Id, COUNT(Id) AS Total_Logged_Uses,
	CASE
	WHEN COUNT(Id) BETWEEN 27 AND 31 THEN 'Active User'
	WHEN COUNT(Id) BETWEEN 22 and 26 THEN 'Moderate User'
	WHEN COUNT(Id) BETWEEN 0 and 21 THEN 'Light User'
	END Usage_Level
	FROM clean-athlete-388418.bellabeats.dailyactivity
	GROUP BY Id
	ORDER BY Total_Logged_Uses DESC

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Usage Level".

![Level Of FitBit Usage In Each Category (2)](https://github.com/peige07/BellaBeat/assets/136380370/218cc831-477e-4aa6-a4f9-29e98455968d)


Next, I wanted to identify the MIN, MAX, and AVG of the data for totalsteps, totaldistance, calories, and activity level for each id.

**Query performed:**

	SELECT Id,
	MIN(TotalSteps) AS Min_Total_Steps,
	MAX(TotalSteps) AS Max_Total_Steps,
	AVG(TotalSteps) AS Avg_Total_Stpes,
	MIN(TotalDistance) AS Min_Total_Distance,
	MAX(TotalDistance) AS Max_Total_Distance,
	AVG(TotalDistance) AS Avg_Total_Distance,
	MIN(Calories) AS Min_Total_Calories,
	MAX(Calories) AS Max_Total_Calories,
	AVG(Calories) AS Avg_Total_Calories,
	MIN(VeryActiveMinutes) AS Min_Very_Active_Minutes,
	MAX(VeryActiveMinutes) AS Max_Very_Active_Minutes,
	AVG(VeryActiveMinutes) AS Avg_Very_Active_Minutes,
	MIN(FairlyActiveMinutes) AS Min_Fairly_Active_Minutes,
	MAX(FairlyActiveMinutes) AS Max_Fairly_Active_Minutes,
	AVG(FairlyActiveMinutes) AS Avg_Fairly_Active_Minutes,
	MIN(LightlyActiveMinutes) AS Min_Lightly_Active_Minutes,
	MAX(LightlyActiveMinutes) AS Max_Lightly_Active_Minutes,
	AVG(LightlyActiveMinutes) AS Avg_Lightly_Active_Minutes,
	MIN(SedentaryMinutes) AS Min_Sedentary_Minutes,
	MAX(SedentaryMinutes) AS Max_Sedentary_Minutes,
	AVG(SedentaryMinutes) AS Avg_Sedentary_Minutes
	From `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id
	ORDER BY Id

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "MIN, MAX, AVG".
 
**Data Insight:** This data showed us each unique id’s average steps, distance, calories, and activity minutes. From this data we are able to draw several meaningful conclusions such as those who are more active each day tend to have higher total steps

![Correlation Between Activity Minutes and Total Steps (2)](https://github.com/peige07/BellaBeat/assets/136380370/4732bb74-c1e7-419a-bd63-6e5a787fb4df)


Now I wanted to take a look at which days of the week users appeared to be the most active.

**Query performed:**

	SELECT Id, ActivityDate,
	AVG(VeryActiveMinutes) AS Avg_Very_Active_Minutes,
	AVG(FairlyActiveMinutes) AS Avg_Fairly_Active_Minutes,
	AVG(LightlyActiveMinutes) AS Avg_Lightly_Active_Minutes,
	AVG(SedentaryMinutes) AS Avg_Sedentary_Minutes
	From `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id, ActivityDate
	ORDER BY ActivityDate

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Average Activity Level".

![Activity Level Based On Day Of Week (2)](https://github.com/peige07/BellaBeat/assets/136380370/d3368cce-0990-4df7-8d17-f6d571c0ed99)


Finally, I wanted to determine which days of the week users took the most steps.

**Query Performed:**

	SELECT ActivityDay,
	AVG(StepTotal) AS Average_Total_Steps
	FROM clean-athlete-388418.bellabeats.dailysteps
	GROUP BY ActivityDay
	ORDER BY ActivityDay;

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Steps Per Day Of Week".

**Data Insights:** The data shows that on average users took the most steps on Saturday, Tuesday and Thursday while taking the least amount of steps on Sundays.

![Average_Total_Steps vs  ActivityDay (2)](https://github.com/peige07/BellaBeat/assets/136380370/90a8fdbc-3131-48ab-bbf2-01073bfe095f)


#### _d. Active Minutes Per User_

The CDC recommends getting at least 150 minutes of cardio in each week, we will be using the activity level of each user to determine if they are meeting this recommendation.

**Query Performed:**

	SELECT Id,
	avg(VeryActiveMinutes) + avg(FairlyActiveMinutes) + avg(LightlyActiveMinutes) AS Total_Avg_Active_Minutes,
	CASE
	WHEN avg(VeryActiveMinutes) + avg(FairlyActiveMinutes) + avg(LightlyActiveMinutes) >= 150 THEN 'Meets CDC Recommendation'
	WHEN avg(VeryActiveMinutes) + avg(FairlyActiveMinutes) + avg(LightlyActiveMinutes) < 150 THEN 'Does NOT Meet CDC Recommendation'
	END CDC_Recommendation
	From `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "CDC Activity Rec".

**Data Insights:** Out of the 33 total users 27 were found to have been active for at least 150 minutes per week while 6 were active for less than 150 minutes per week.

![CDC Recommendation Met (2)](https://github.com/peige07/BellaBeat/assets/136380370/d1db4484-43b8-4b5f-99f9-336dce7391f0)


Next, I wanted to determine how many of our users would meet the CDC activity recommendation if we removed the category of LightActiveMinutes from out calculation.

**Query Performed:**

	SELECT Id,
	SUM(VeryActiveMinutes + FairlyActiveMinutes) AS Total_Avg_Active_Minutes,
	CASE
	WHEN SUM(VeryActiveMinutes + FairlyActiveMinutes) >= 150 THEN 'Meets CDC Recommendation'
	WHEN SUM(VeryActiveMinutes + FairlyActiveMinutes) <150 THEN 'Does Not Meet CDC Recommendation'
	END CDC_Recommendations
	FROM `clean-athlete-388418.bellabeats.dailyactivity`
	WHERE ActivityDate BETWEEN '2016-05-01' AND '2016-05-08'
	GROUP BY Id

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Very Active + Active".

**Data Insights:** The results of this query indicated that when removing LightActiveMinutes now only 22 out of 33 users met the CDC’s recommendation of being active for 150 minutes or more per week.

![CDC Recommendation Met Based ON Very Active + Active Minutes (2)](https://github.com/peige07/BellaBeat/assets/136380370/2405cc70-fa82-43cb-984d-836b2f200c44)

#### _e. Steps Per Day Per User_

We will use information from [1000steps.org]((http://www.10000steps.org) to determine how active each user was based on their steps per day, each user will fall into one of the following categories:

**Sedentary** is less than 5,000 steps per day
**Low active** is 5,000 to 7,499 steps per day
**Somewhat active** is 7,500 to 9,999 steps per day
**Active** is 10,000 to 12,299 steps per day
**Highly active** is more than 12,500

**Query Performed:**
	
 	SELECT Id,
	AVG(totalsteps) AS `Average Total Steps`,
	CASE
	WHEN AVG(TotalSteps) < 5000 THEN 'Sedentary'
	WHEN AVG(TotalSteps) BETWEEN 5000 AND 7499 THEN 'Low Active'
	WHEN AVG(TotalSteps) BETWEEN 7500 AND 9999 THEN 'Somewhat Active'
	WHEN AVG(TotalSteps) BETWEEN 10000 AND 12499 THEN 'Active'
	WHEN AVG(TotalSteps) >= 12500 THEN 'Highly Active'
	END AS Activity_Level
	FROM `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id
	ORDER BY Activity_Level;

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Average Steps".

**Data Insight:** The query and accompanying visualization indicates that only 7 out of 33 users were considered active or highly active.

_The data breaks down into the following categories:_

	Sedentary - 8
	Low active - 9
	Somewhat active- 9
	Active - 5
	Highly active - 2
 
![Users Activity Based On Steps Per Day (2)](https://github.com/peige07/BellaBeat/assets/136380370/9de74740-780a-42fb-8293-13c2190dbe17)


#### _f. Calories Consumed Per Day Per User_

Now I wanted to determine how many calories per day each user was consuming. According to [NHS](https://www.nhs.uk/common-health-questions/food-and-diet/what-should-my-daily-intake-of-calories-be/#:~:text=An%20ideal%20daily%20intake%20of,women%20and%202%2C500%20for%20men.) generally, the recommendation for daily calories is 2,000 for women and 2,500 for men.

**Query performed:**

	SELECT Id,
	AVG(Calories) AS `Average Calories Per Day`,
	FROM `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id
	
 [Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Calories Per Day".

**Data Insight:** According to our data on average each user consumed 2,282 calories. Due to the limitations of our data not providing sex as a variable we cannot determine if the average user is consuming the proper amount of calories.

![Average Calories Per Day (2)](https://github.com/peige07/BellaBeat/assets/136380370/b0565102-ad13-42e0-bdd3-9fc6a57023f1)


Next, I categorized each user by the amount of calories they were consuming on average each day.

_Categories assigned:_

**Not Enough** - < 2000
**Enough** - Between 2000 AND 2500
**Too Much** - >2500

**Query Performed:**

	SELECT Id,
	AVG(Calories) AS `Average Calories Per Day`,
	CASE
	WHEN AVG(Calories) < 2000 THEN 'Not Enough'
	WHEN AVG(Calories) BETWEEN 2000 AND 2500 THEN 'Enough'
	WHEN AVG(Calories) > 2500 THEN 'To Much'
	END AS Daily_Caloric_Intake
	FROM `clean-athlete-388418.bellabeats.dailyactivity`
	GROUP BY Id

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Daily Caloric Intake".

**Data Insight:** According to the data 12 out of 33 users are consuming more calories per day than recommended.

![Daily Caloric Intake (2)](https://github.com/peige07/BellaBeat/assets/136380370/a1d7573e-1272-4a08-9c1a-751cb50f0388)


Finally, I wanted to practice using the INNER JOIN clause so I combined the dailyacitivty table and the sleep day table.

**Query Performed:**

	SELECT da.id, sd.id,
	AVG(da.TotalSteps) AS AvgTotalSteps,
	AVG(da.Calories) AS AvgCalories,
	AVG(sd.TotalTimeInBed) AS AvgTotalMinutesAsleep
	FROM `clean-athlete-388418.bellabeats.dailyactivity` AS da
	INNER JOIN `clean-athlete-388418.bellabeats.sleepday` AS sd ON da.id = sd.id
	GROUP BY da.id, sd.id;

[Resulting table generated](https://docs.google.com/spreadsheets/d/1XlKgC4iiuuXQkT3W9Nfw5qQ9E4eUgmCNeycsrfr1PPc/edit?usp=sharing), CSV uploaded into Sheets and named "Id, Steps, Calories, Asleep".

**Data Insight:** The data shows a correlation between average calories consumed and average steps per day.

![Calories Consumed Vs  Steps Taken (2)](https://github.com/peige07/BellaBeat/assets/136380370/bce75d51-c3c5-46a3-8603-043f50b2f56d)


### 6. Share Phase / Visualizations With Tableau

After completing the SQL queries, uploading CSV files into sheets & completing visualizations for several tables I wanted to practice making a dashboard inside of Tableau to tell the story of the data.

[Tableau Dashboard](https://public.tableau.com/app/profile/peige.malys/viz/GoogleDataAnalyticsBellaBeatCapstoneDashboard/Dashboard1)


### 7. Act Phase
#### _a. Final Conclusions & Recommendations_

Based on the data and analysis performed several trends were able to be identified that could prove useful when addressing the business task of “Analyzing the data the FitBit Fitness Tracker Data to gain insight into how people are using their devices, in order to identify trends that can be used in Bellabeats marketing strategy.”

The first trend we were able to identify was that 81.8% of users were considered “Active” users meaning that they wore their FitBit between 27 and 31 days of the 31-day tracked period. Due to the active category likely indicating successful adoptions of the fitness device, we can extrapolate that we should gear our marketing campaigns toward a similar audience.

The next trend we were able to observe was that users took the least amount of steps on Sundays and Fridays. This information could be used by Bellabeats marketing team to create an awareness campaign aimed at getting people to move more on these low-step days and the potential benefits taking an extra 2,000 steps each of these days could have on someone's over all health.

The last trend we were able to observe based on the data was that 51% of users were considered to be sedentary or low active according to information from the NHS website. This information could easily be used to create marketing materials aimed at potential users who believe they fall into these categories and educate them on the negative consequences that can come from living a low-activity lifestyle and ultimately how BellaBeats products can help them make better data-driven decisions.

Overall there are several more conclusions that can be drawn from the data and analysis that were performed depending on what specific questions that need to be answered.

#### _b. Closing Thoughts_

Theoretically, we can draw some general ideas and trends from this data, it is my personal belief that there are far too many limitations to the data set provided to be used for any marketing campaign.

First, this data set did not include demographic information, which is hugely problematic for Bellabeats since their target audience is assumingly female.

Second, there were simply not enough users to draw a meaningful conclusion that could be representative of an entire population.
