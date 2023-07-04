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

[Resulting table generated](https://docs.google.com/spreadsheets/d/1TLA8PGj6xoouE0aFrDxnotu--e7O6jzuEbGh3x1W33U/edit?usp=sharing), CSV uploaded into Sheets, and named "Daily Usage".

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

[Resulting table generated](https://docs.google.com/spreadsheets/d/1TLA8PGj6xoouE0aFrDxnotu--e7O6jzuEbGh3x1W33U/edit?usp=sharing), CSV uploaded into Sheets and named "Usage Level".

[Users In Each Category](https://storage.googleapis.com/kagglesdsdata/datasets/3463543/6053632/Level%20Of%20FitBit%20Usage%20In%20Each%20Category.png?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20230629%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20230629T161209Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=1497b46bcb6af8e4e97f074a2f863124b5dc74b0e325689826fd3149b11ce3f0b775d99d01866aeb3e7b20bc38302bd3a26b249844e8f9a8dc950fdfa00a202f4d5ba61bc83a4fced6be8ce5d7dcaa5d8cc531b37cd98d0307fd1f486dddbf709a4d0f010669bd552a1dde9adc381c1e461d0f117a38277405a0a1c4cfe3b343d6909b48b5c3a3d4ccd5533b52976fd357397069ae52421350153083675919c7f420b7d90db9f38f505bfe3f438e52fef17a2d6211b1911878fd56b629b9da8035659e7fc0277e28561977792cebf079e98cd9d4296ae30c70e43c3cb2398fe6d768322b3e5b4a1b43f0b9341a58817969e038f6a33fd9bdc1aec034a3559097)
