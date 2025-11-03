# Product Analysis Project

## Table of Contents
- [Project Overview](#Project-Overview)
- [Data Sources](#Data-Sources)
- [Tools](#Tools)
- [Data Cleaning/Preparation](#Data-Cleaning/Preparation)
- [Data Analysis](#Data-Analysis)
- [Key Performance Indicators (KPIs) Generation](#Key-Performance-Indicators-(KPIs)-Generation)
- [Insights](#Insights)
- [Recommendations](#Recommendations)
- [Data Visualisation](#Data-Visualisation)



## Project Overview

This project involved an analysis of product usage data from an e-commerce firm aiming to extract valuable insights into user engagement with the application. An interactive Tableau dashboard was developed to facilitate the monitoring of user adoption and engagement trends on the app.

## Data Sources

The dataset used for this project was the product usage data which include date, total app installs, user sign ups, daily active users, number of transactions, uninstalls, number of app crashes, Average time spent per user, region and device. 

## Tools

- Google Sheets: For Data Collection and Preparation
- Tableau: For building an interactive dashboard and forecasting app trends

## Data Cleaning/Preparation

An initial data cleaning was performed on Google Sheets before connecting to Tableau for detailed analysis and dashboard development. The cleaning process included:

1. Data loading and inspection
2. Handling missing values and removing duplicates
3. Handling formatting
4. Data validation


## Data Analysis
A comprehensive data analysis was conducted using Tableau to evaluate app performance and user engagement

## Key Performance Indicators (KPIs) Generation

### KPIs for App Performance
The following KPIs were generated and visualised using Tableau:

- **Installs:** Measured the total number of times the app was downloaded and installed on a device.
- **Sign Ups:** Counts of users who have registered or created an account on the app up to the specified date.
- **Sign Up Rate:** Percentage of installed users who eventually signed up on the app.
- **Uninstalls:** Measured the total number of times the app was removed from devices.
- **App churn Rate:** Percentage of users who uninstalled the app from their devices.
- **App Crashes:** The total instances where the app unexpectedly stopped working


<img width="1188" height="220" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/56d1159c-1682-4d63-94bf-c4777b3f74b7" />

### User Engagement Metric

This section focuses on generating key engagement metrics

- **Average Daily App Users:** This represents the average number of unique users who interact with the app daily.
- **Average User Session Length:** The average duration, in minutes, that each user spent interacting with the app daily.
- **Transaction Volume:** Measures the total number of trade transactions executed by users within the app.

<img width="1181" height="165" alt="Engagement" src="https://github.com/user-attachments/assets/7291e790-59d9-4a6a-a7b4-39453c564165" />

## Insights

#### App Performance
- The app performance indicators (KPIs) demonstrated overall positive trends compared to the previous month; however, there were notable exceptions. Specifically, app crashes increased by 24.4%, and the sign-up rate experienced a decline of 3.4%.
- A significant spike in app uninstalls was recorded on July 23, with a total of 819 users removing the app. Subsequent data indicated a decrease in uninstalls the following day, leading to relative stabilisation in uninstall rates thereafter.

#### Engagement Metrics
- Engagement metrics reveal a favourable growth trend over the previous months. Key observations include:
  - An average daily active user (DAU) increase of 6.10%
  - A user session increase of 2.7%
  - A transaction volume increase of 6.3%
  
- The majority of installed users are Android users, totalling 1,164,619, while iOS users account for 817,188. Analysis indicates that Android users exhibit higher activity levels within the app and engage in more transactions. In contrast, iOS users tend to spend more time interacting with app features.
  
- Geographically, the United States (US) leads with the highest levels of active users and transaction volume. The Europe, Middle East, and Africa (EMEA) region registers the longest session lengths.
  
- The top three performing regions based on engagement scores are:
  - US: 0.98
  - Canada: 0.75
  - EMEA: 0.74

**Note:** Engagement scores were calculated by normalising engagement metrics, assigning weights of 0.5 to transaction volume, 0.3 to session length, and 0.2 to the number of active users.

### Predictive Analysis
This section utilises predictive analytics to project key engagement metrics, including Daily app users, user session length, and transaction volume. The Tableau forecasting tool was employed to analyse historical trends and patterns for performance projections over the next 60 days. These insights provide a data-driven approach to strategic decision-making, enabling stakeholders to anticipate growth opportunities, allocate resources efficiently, and mitigate potential risks.

- **Forecast for Daily App Users:** Projections indicate a slight increase in daily app users with expected fluctuations throughout the forecasted period.
  
- **Transaction Volume Forecast:** Stability in transaction volume is anticipated during this period.

- **User Session Length Prediction:** The average time users spend interacting with the app is expected to decline, and stability is anticipated thereafter.


## Recommendations

### App Stability 
- Investigate crash logs by device to identify triggers (e.g., updates, bugs), and release a stability patch.
- Set automated alerts for unusual spikes in crashes or uninstalls.

### Optimise User Experience

- Investigate if users face difficulty in the sign-up process and aim to review and streamline the registration flow to reverse the sign-up decline.
- Device Focus:
   - **Android:** Improve transaction flow and performance since these users are more active.
   - **iOS:** Deepen feature engagement; users spend longer per session.

### Regional strategy
- Maintain momentum in the US through loyalty or referral programs to reinforce strong engagement

### Continous Tracking
- **Key KPIs to monitor:** crash rate, uninstall rate, sign-up, daily app users, and session length by region/device.

## Data Visualisation
An interactive Tableau dashboard was developed to facilitate app performance and user engagement monitoring
Click [here](https://public.tableau.com/views/ProductAnalysisDashboard_17599495005740/OverviewPage?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link) to view dashboard.
