# Google Playstore Dashboard
## Introduction
The **Play Store** is home to millions of applications, catering to various user needs, from entertainment and education to business and productivity. With such a diverse range of apps available, understanding the factors contributing to an app's success is essential for developers, marketers, and product managers.

In this analysis, we explore several key variables that impact the performance of apps on the Play Store, using a dataset containing information about app categories, size, user ratings, reviews, Android versions, and more. By investigating the relationships between these variables, we aim to uncover trends that can provide insights into what makes certain apps more successful than others.

This project aims to provide actionable insights for developers and stakeholders to make informed decisions about app development and marketing strategies on the Play Store. By understanding the factors that drive success, we can help create more engaging and successful apps for users worldwide.
## Problem Statement
The Play Store has a diverse ecosystem of applications, ranging from games to productivity tools. Understanding what drives an app's success can provide valuable insights for developers, marketers, and decision-makers looking to optimize their offerings.

[Play Store Problem Statement Questions](https://github.com/user-attachments/files/17783714/Play.Store.Problem.Statement.1.docx)

## Dataset

Below are the details of the Datasets used for the Dashboard:
- **App :**	The app's name is listed on the Google Play Store.
- **Category :** The category to which the app belongs (e.g., ART_AND_DESIGN, GAME).
- **Rating :**	The user rating of the app on a scale from 1 to 5.
- **Reviews :**	The number of user reviews for the app.
- **Size :**	The app size is in megabytes (MB) or kilobytes (KB).
- **Installs :**	The number of installs/downloads of the app (e.g., 10,000+).
- **Type :** Indicates whether the app is free or paid.
- **Price :**	The app's price is in USD if paid.
- **Content Rating :**	The target audience for the app (e.g., Everyone, Teen, Mature 17+).
- **Genres :**	The genres associated with the app (e.g., Art & Design, Creativity).
- **Last Updated :**	The date when the app was last updated.
- **Current Ver :**	The current version of the app.
- **Android Ver :**	The minimum Android version required to run the app.

## Data Cleaning & ETL
In this project, a comprehensive data cleaning and ETL (Extract, Transform, Load) process was applied to ensure data accuracy and consistency for analysis. We standardized key columns such as app size, ratings, and installs by removing duplicates and handling missing values. Additionally, we converted categorical variables (like app size categories and Android versions) to more usable formats, facilitating better analysis.

The ETL process involved transforming raw data into structured formats, categorizing app attributes, and applying necessary conversions. These steps helped prepare the dataset, making it ready for effective analysis and visualization, leading to meaningful insights into app performance on the Play Store.

## Dashboard
<p align="center">
<img width="638" alt="Dashboard" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Dashboard.png">
</p>

### Key Observations from the Dashboard
**1. Top Categories by Installations**
- The Family category leads with the highest installations (~2K), followed by Games (1.1K) and Tools (800).

**2. Willingness to Pay for Apps**
- Users are most willing to pay for Medical apps (24% paid) and Personalization apps (21%). Categories like Weather and Books & Reference also show moderate willingness.
On the other hand, users show minimal interest in paying for apps in categories such as Beauty, Comics, News & Magazines, Social, and Shopping.

**3. Dominant Primary Genres**
- The most common primary genres include Tools, Entertainment, and Education, followed by Medical, Business, Productivity, and Sports in descending order.
**4. Android Version Compatibility**
- A majority (64%) of apps support Android 4+, while 12.5% are compatible with Android 2+, and another 12.5% vary by device.

**5. Growth in App Releases**
- App releases began to rise significantly in 2014, with a sharp increase post-2017, marking a period of rapid growth in the Play Store.

**6. App Size Distribution**
- Around 36% of apps fall into the Medium size category, while 15% have sizes that vary by device.

**7. Installations by Content Rating**
- All Ages content dominates installations, followed by apps rated for Teenagers and Mature (17+) audiences.
Categories like Kids, Adults, and Unrated apps have the lowest installation counts.

## App Size Impact

<table style="width: 100%; table-layout: fixed;">
  <tr>
    <!-- Paragraph on the left side (40% width) -->
    <td style="width: 40%; vertical-align: top; padding-right: 10px;">
      <p>
        - The <strong>Family</strong> category leads with the highest installations, contributing approximately <strong>18%</strong> of total installs, followed by <strong>Games</strong> (10.5%) and <strong>Tools</strong> (8%).<br>
        - Categories like <strong>Medical</strong> and <strong>Business</strong> also show significant numbers, while other categories contribute smaller shares.<br>
        - A similar trend is observed in the number of reviews, with the <strong>Family</strong>, <strong>Games</strong>, and <strong>Tools</strong> categories receiving the most user feedback.
      </p>
    </td>
    <!-- Image on the right side (60% width) -->
    <td style="width: 60%; text-align: center;">
      <img style="width: 100%; height: auto; object-fit: cover;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%201.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
  </tr>
</table>







## Popular App Categories
<table>
  <tr>
    <td>
      <p>
        - The <strong>Family</strong> category leads with the highest installations, contributing approximately <strong>18%</strong> of total installs, followed by <strong>Games</strong> (10.5%) and <strong>Tools</strong> (8%). <br>
        - Categories like <strong>Medical</strong> and <strong>Business</strong> also show significant numbers, while other categories contribute smaller shares. <br>
        - A similar trend is observed in the number of reviews, with the <strong>Family</strong>, <strong>Games</strong>, and <strong>Tools</strong> categories receiving the most user feedback.
      </p>
    </td>
    <td>
      <img style="max-width: 800px; height: auto;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%202.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
  </tr>
</table>

## Free Vs Paid Apps
<p align="center">
<img width="638" alt="Question 3" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%203.png">
</p>

## Content Types
<p align="center">
<img width="638" alt="Question 4" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%204.png">
</p>

## Android Version
<p align="center">
<img width="638" alt="Question 5" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%205.png">
</p>

## Changes Over Time
<p align="center">
<img width="638" alt="Question 6" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%206.png">
</p>

## Genres
<p align="center">
<img width="638" alt="Question 7" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%207.png">
</p>





<table style="width: 100%; table-layout: fixed;">
  <tr>
    <!-- Paragraph on the left side (40% width) -->
    <td style="width: 40%; vertical-align: top; padding-right: 10px;">
      <p>
        - The <strong>Family</strong> category leads with the highest installations, contributing approximately <strong>18%</strong> of total installs, followed by <strong>Games</strong> (10.5%) and <strong>Tools</strong> (8%).<br>
        - Categories like <strong>Medical</strong> and <strong>Business</strong> also show significant numbers, while other categories contribute smaller shares.<br>
        - A similar trend is observed in the number of reviews, with the <strong>Family</strong>, <strong>Games</strong>, and <strong>Tools</strong> categories receiving the most user feedback.
      </p>
    </td>
    <!-- Image on the right side (60% width) -->
    <td style="width: 60%; text-align: center;">
      <img style="width: 100%; height: auto; object-fit: cover;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%207.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
  </tr>
</table>
