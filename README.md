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
        - Apps in the <strong>Medium</strong> size category dominate in terms of both popularity and availability, with the highest number of installations and the most apps. <br>
        - <strong>Small</strong> and <strong>Large</strong> size apps follow, while "Very Small" size apps have the lowest installations and availability. <br>
        - Reviews and ratings show a consistent trend across all size categories, with <strong>Medium</strong> size apps contributing approximately <strong>36%</strong>, followed by <strong>Small</strong> at <strong>21%</strong>, and "Very Small" apps having the lowest share.
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
      <img style="max-width: 800px; height: auto;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%202.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
    <td>
      <p>
        - The <strong>Family</strong> category leads with the highest installations, contributing approximately <strong>18%</strong> of total installs, followed by <strong>Games</strong> (10.5%) and <strong>Tools</strong> (8%). <br>
        - Categories like <strong>Medical</strong> and <strong>Business</strong> also show significant numbers, while other categories contribute smaller shares. <br>
        - A similar trend is observed in the number of reviews, with the <strong>Family</strong>, <strong>Games</strong>, and <strong>Tools</strong> categories receiving the most user feedback.
      </p>
    </td>
    
  </tr>
</table>

## Free Vs Paid Apps
<table style="width: 100%; table-layout: fixed;">
  <tr>
    <!-- Paragraph on the left side (40% width) -->
    <td style="width: 40%; vertical-align: top; padding-right: 10px;">
      <p> 
        - Only <strong>7.38%</strong> of users prefer to pay for apps, and this is reflected in the installation numbers, with free apps dominating the market.<br> - Users are most willing to pay for <strong>Medical</strong> apps (24% paid) and <strong>Personalization</strong> apps (21%).<br> 
        - Categories such as <strong>Weather</strong> and <strong>Books & Reference</strong> also see moderate willingness to pay.<br> 
        - Minimal interest is observed in paying for apps in categories like <strong>Beauty</strong>, <strong>Comics</strong>, <strong>News & Magazines</strong>, <strong>Social</strong>, and <strong>Shopping</strong>. 
      </p>
    </td>
    <!-- Image on the right side (60% width) -->
    <td style="width: 60%; text-align: center;">
      <img style="width: 100%; height: auto; object-fit: cover;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%203.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
  </tr>
</table>

## Content Types
<table>
  <tr>
    <td>
      <img style="max-width: 800px; height: auto;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%204.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
    <td>
      <p>
  - The <strong>All Ages</strong> content type has the highest installations (>8,000), followed by <strong>Teenage</strong> (~1,500) and <strong>Mature (17+)</strong> (~1,000). Adults and Unrated have the lowest installs.<br>
  - Reviews follow a similar pattern, with <strong>All Ages</strong> receiving the most feedback.<br>
  - Most apps have <strong>4-star ratings</strong>, followed by <strong>3-star</strong>, while <strong>5-star ratings</strong> are rare. Unrated content also trends toward <strong>4-star</strong> ratings or none.
</p>
    </td>
    
  </tr>
</table>



## Android Version
<table style="width: 100%; table-layout: fixed;">
  <tr>
    <!-- Paragraph on the left side (40% width) -->
    <td style="width: 40%; vertical-align: top; padding-right: 10px;">
      <p>
  - <strong>Android 4.x</strong> is the most common version, compatible with <strong>64.2%</strong> of apps, followed by <strong>Varies</strong> and <strong>Android 2.x</strong>, both around <strong>12.5%</strong>.<br>
  - Newer versions like <strong>5.x</strong>, <strong>6.x</strong>, <strong>7.x</strong>, and <strong>8.x</strong> have minimal app support.<br>
  - Apps supporting <strong>Android 4.x</strong> dominate installations with over <strong>6,000 installs</strong>, while other versions lag behind.<br>
  - Categories like <strong>Family</strong>, <strong>Games</strong>, and <strong>Tools</strong> have the largest app distributions, mostly aligning with <strong>Android 4.x</strong>.<br>
</p>
    </td>
    <!-- Image on the right side (60% width) -->
    <td style="width: 60%; text-align: center;">
      <img style="width: 100%; height: auto; object-fit: cover;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%205.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
  </tr>
</table>

## Changes Over Time
<table>
  <tr>
    <td>
      <img style="max-width: 800px; height: auto;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%206.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
    <td>
      <p>
  - The number of installations and apps has grown significantly over time, with a sharp rise observed in 2018.<br>
  - The <strong>All Ages</strong> content type dominates in terms of app count across all years, followed by <strong>Teenage</strong> and <strong>Mature (17+)</strong> categories. Adults (18+) and Unrated categories show minimal growth.<br>
  - Categories like <strong>Family</strong>, <strong>Games</strong>, and <strong>Tools</strong> exhibit the highest increase in app count, particularly in recent years, indicating their growing popularity.
</p>
    </td>
    
  </tr>
</table>



## Genres
<table style="width: 100%; table-layout: fixed;">
  <tr>
    <!-- Paragraph on the left side (40% width) -->
    <td style="width: 40%; vertical-align: top; padding-right: 10px;">
      <p>
  - Among primary genres, <strong>Tools</strong>, <strong>Entertainment</strong>, and <strong>Education</strong> lead in the number of apps, indicating their popularity.<br>
  - Secondary genres like <strong>Music & Video</strong> and <strong>Education</strong> dominate in terms of installations, showing high user engagement.<br>
  - Genres such as <strong>Creativity</strong> and <strong>Brain Games</strong> have fewer installations, suggesting a niche audience compared to more popular genres.
</p>
    </td>
    <!-- Image on the right side (60% width) -->
    <td style="width: 60%; text-align: center;">
      <img style="width: 100%; height: auto; object-fit: cover;" src="https://github.com/Naimuddin74667/Google_PlayStore_Dashboard/blob/main/Visualization/Question%207.png" alt="Power BI Page Screenshot for Popular Categories">
    </td>
  </tr>
</table>
