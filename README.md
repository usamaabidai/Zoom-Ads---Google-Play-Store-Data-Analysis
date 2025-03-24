# Zoom Ads - Google Play Store Data Analysis

## Project Overview
Advertising is a crucial component of marketing, used to promote or sell products and services. Android, the dominant mobile operating system, holds approximately 69% of the global market share. The Google Play Store serves as the primary app distribution platform for Android users.

Zoom Ads, an advertising agency, aims to analyze Google Play Store data to identify trends in mobile applications. The goal is to determine which app categories are trending and provide insights that can maximize advertising revenue by targeting high-performing applications.

As a Data Scientist, you are required to analyze a dataset containing information on over 4000 apps across different categories, including key attributes such as Ratings, Reviews, and Installations.

## Data Description
The dataset includes the following attributes:
- **App**: Name of the application
- **Category**: The category to which the app belongs (`Others` category contains apps from various excluded categories)
- **Rating**: The overall user rating of the app
- **Reviews**: Number of user reviews
- **Size**: App size in kilobytes
- **Installs**: Number of downloads/installs
- **Paid/Free**: Indicates whether the app is free or paid
- **Price**: The price of the app in dollars (if paid)
- **Content Rating**: The target age group for the app
- **Ad Supported**: Whether the app contains ads (Yes/No)
- **In-App Purchases**: Whether the app includes in-app purchases (Yes/No)
- **Editors' Choice**: Whether the app has been rated as an Editor’s Choice (Yes/No)

## Key Findings
Following an in-depth analysis of the dataset using descriptive statistics and visualizations, the following insights were derived:

1. **Category Distribution**: The dataset comprises 16 categories. The largest category is `Others`, followed by `Family`, making `Family` the most dominant specific category.
2. **Ad-Supported Free Apps**: Most trending apps are free and support advertisements.
3. **Impact of Ads on Free Apps**: A significant difference exists between free apps that support ads and those that do not.
4. **Content Rating**: Approximately 80% of apps are rated suitable for all age groups.
5. **Ratings & App Category**: App ratings do not significantly vary across different categories.
6. **Reviews & Installations Correlation**: Apps with higher review counts tend to have higher installation numbers.
7. **Family Category Performance**: Despite being costlier, apps in the `Family` category receive good ratings, substantial reviews, and high installation counts.
8. **Trending Categories**: Besides `Family`, other trending categories include `Game` and `Tools`.

## Recommendations
Based on the findings, the following recommendations are made for Zoom Ads:

1. **Invest in Family Category Apps**: Given their popularity, advertising in the `Family` category is likely to yield the best results. Additional focus can be placed on `Game` and `Tools` categories.
2. **Prioritize Free, Ad-Supported Apps**: Free apps that support ads present the highest advertising potential.
3. **Avoid Certain Categories**: Investment in `Finance` and `Medical` categories should be minimized as they often do not support ads.
4. **Focus on Highly Reviewed Apps**: Since a high number of reviews correlates with higher installations, prioritizing such apps for advertising is beneficial.
5. **Exclude Low-Performing Categories**: Avoid investing in `Business` and `Books & References` apps as they exhibit low user engagement and installation rates.

## Conclusion
This analysis provides actionable insights for Zoom Ads to optimize its advertising strategy on the Google Play Store. By targeting high-performing categories and prioritizing ad-supported apps, the agency can maximize profitability and engagement.

