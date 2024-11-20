
# Google Play Store Apps Analysis

## Introduction
This project focuses on analyzing the Google Play Store Apps dataset to uncover insights and trends about the apps available on the platform. By leveraging Python and the Pandas library, various data exploration and analysis tasks are performed to understand app characteristics such as categories, ratings, reviews, and installs.
---

## Dataset Overview
The dataset consists of **10,841 rows** and **13 columns**, each representing attributes of Google Play Store apps:

- **App**: Name of the app.
- **Category**: App category.
- **Rating**: Average user rating.
- **Reviews**: Number of reviews.
- **Size**: Size of the app.
- **Installs**: Number of installations.
- **Type**: Indicates whether the app is free or paid.
- **Price**: Cost of the app.
- **Content Rating**: Target audience age group.
- **Genres**: App genre.
- **Last Updated**: Last update date.
- **Current Version**: Current version of the app.
- **Android Version**: Minimum Android version required.

---

## Key Findings and Insights
1. **App Titles Containing "Astrology"**:
   - Identified the total number of app titles that include the term "Astrology."

2. **Average Rating**:
   - Calculated the overall average rating for all apps.

3. **Unique Categories**:
   - Found the total number of unique app categories in the dataset.

4. **Highest Average Ratings by Category**:
   - Determined the app category with the highest average rating.

5. **5-Star Apps**:
   - Counted the total number of apps with a perfect 5-star rating.

6. **Average Reviews**:
   - Computed the average number of reviews, accounting for cases where reviews are represented in millions.

7. **Free vs. Paid Apps**:
   - Counted the total number of free and paid apps.

8. **App with Maximum Reviews**:
   - Identified the app with the highest number of reviews.

9. **Top 5 Apps by Reviews**:
   - Displayed the top 5 apps with the highest number of reviews.

10. **Average Rating by Type**:
    - Compared the average ratings of free and paid apps.

11. **Top 5 Apps by Installs**:
    - Listed the top 5 apps with the highest number of installations.

---

## Conclusion
This analysis provides actionable insights into the Google Play Store ecosystem, including:
- Identifying popular app categories and highly-rated apps.
- Understanding the distribution of free vs. paid apps.
- Highlighting apps with high user engagement through reviews and installs.

These findings can guide app developers, marketers, and analysts to make data-driven decisions about app development, promotion, and user engagement strategies.

---

## Setup Instructions
1. Clone the repository or download the dataset.
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy

