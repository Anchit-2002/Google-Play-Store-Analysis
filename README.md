# Play Store App Review Analysis

# 📋 Objective
The objective is to provide insights into customer demands, helping developers optimize their apps for greater success. By analyzing attributes like app type (free or paid), user reviews, and ratings, The aim is to uncover key relationships and create visualizations to understand app preferences. These insights will guide developers in aligning their apps with user needs, boosting engagement and success in a competitive market.

# 📖 Problem Statement:

Mobile applications play a vital role in modern life, serving a variety of functions across categories such as family, communication, entertainment, tools, and music. In a highly competitive global market, app developers face immense pressure to stay relevant and maintain their market position. This project leverages a dataset of 10,000 Google Play Store applications, divided into two CSV files: Play Store Data (10,841 rows, 13 columns) and User Reviews (64,295 rows, 5 columns). The primary aim is to analyze factors that influence app popularity by examining attributes such as app category, pricing, size, and user sentiment. The key questions include understanding what makes an app popular, the optimal pricing and size for an app, and identifying trends in user sentiment across different categories. The goal is to filter and make plots accordingly for a better EDA (Exploratory Data Analysis) with respect to the final data.


1. **The Content of Play Store Data** :

- **App**: Name of the app with optional description.
- **Category**: App category (33 categories in total).
- **Size**: Disk space needed for installation.
- **Rating**: Average user rating (1-5).
- **Reviews**: Number of user reviews.
- **Installs**: Approximate install count.
- **Type**: Indicates if the app is free or paid.
- **Price**: App price (0 for free apps).
- **Content Rating**: Suitable age group.
- **Genres**: Genre(s) of the app.
- **Last Updated**: Date of the latest update.
- **Current Ver**: Current app version.
- **Android Ver**: Required Android version.

2. **User Reviews Contents:**

- **App**: Name of the app.
- **Translated Review**: English-translated user review.
- **Sentiment**: User's attitude/emotion (Positive, Negative, Neutral).
- **Sentiment Polarity**: Review polarity (-1 to 1; -1 = Negative, 1 = Positive).
- **Sentiment Subjectivity**: Measures review subjectivity (0 to 1); higher indicates more public opinion-based.


# 🛠 Challenges Faced:  

- **Data Cleaning**: The primary challenge was handling errors, duplicates, and NaN values in the dataset.  
- **Missing Reviews**: 13.60% of reviews were NaN, and after merging both dataframes, we couldn't infer much to fill them, leading to their removal.  
- **Limited Merged Data**: The merged dataframe contained only 816 common apps (10% of cleaned data), limiting the analysis. Having 70-80% of the data would have provided more valuable insights.  
- **User Reviews Data**: With 42% of NaN values, the user reviews data could have been used to analyze category-wise sentiments, helping to fill the 13.60% NaN values in the Reviews column.  
- **Untapped Potential**: Further analysis could include exploring the relationship between app size, Android version, and installs.  
- **Machine Learning**: Machine learning could uncover deeper insights and improve interpretations, planned for future work.  
- **Visualization**: Designing effective visualizations to summarize and communicate the dataset's findings clearly was another challenge.


# 📋 Conclusions

- **Focus on Free Apps**: Most apps are free, so developers should prioritize creating free apps to attract a larger customer base.
- **Paid Apps**: For paid apps, the size should not exceed 40MB, and the price should be affordable (under $1).
- **Explore less represented Categories**: Categories like Events, Beauty, and Parenting are less explored but have high popularity and installations.
- **Regular Updates**: Apps should be updated regularly to retain the customer base.
- **Accessible Content**: Developers should ensure app content is available to a wide audience.
- **Bulky Apps**: Larger apps are more suited for categories like Games and Family.
- **Paid App Size and Price**: For paid apps, keep the size under 20MB and price affordable.
- **Game and Family Apps**: These categories often receive negative reviews, so careful development is needed.
- **Exploratory Data Analysis (EDA)**: Conducting EDA helps identify potential risks, uncover insights, and improve app development strategies.
    Play Store App Review Analysis

















