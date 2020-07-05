# Mobile-Apps-Profitability-Analysis
- Apple App Store and Google Play Store mobile apps analysis

- Technology: Mobile App Development

- Descriptive multivariate data analysis was conducted on mobile apps data from the Apple Mobile App Store and Google Play Store. 10,000 Play Store apps and 7,200 Mobile App Store apps data sets from Kaggle were imported, cleaned, and analyzed. The profitability of App Store and Google Play Store apps were explored to identify which types of apps are likely to attract more users, this information is then used to inform app development within the company to reduce development risk.

- Two datasets were gathered and munged. The data was analyzed and descriptive statistics were generated. Mobile apps were identified with profiles that were successful on both Apple App Store and Google Play store markets to mitigate risk and overhead for company app development. The mean was calculated for the average number of installs by genre for App Store and Google Play Store mobile apps. The most common genres in the App Store market and Google Play Store market were visualized in frequency tables.

- 10,000 Play Store apps and 7,200 App Store apps datasets from Kaggle that include 13 features from the Play Store and 10 features from the App Store that describe the given app. A complete explanation can be found at the Kaggle webpages: https://www.kaggle.com/lava18/google-play-store-apps, https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps?select=AppleStore.csv

## Processing Instructions:
- https://drive.google.com/file/d/17FJWXqMo7ZxWnvyrYR8xCvDBndVAOtYd/view?usp=sharing to view HMTL version of report.
- To improve reproducibility of the data analysis, a Jupyter Notebook file is included.

## Steps to Transformation:
- Data was downloaded from https://www.kaggle.com/lava18/google-play-store-apps, https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps?select=AppleStore.csv
- Files “applestore.csv”, “googleplaystore.csv” were imported into Jupyter Notebook.
- The Google Play Store apps data set has an error in one of its rows: a "CATEGORY" value is missing. Removed the row with the error.
- Duplicate entries were removed using the criterion of “entries with number of reviews lower than entry with highest number of reviews”.
- Non-English language apps were removed and a new data set was created.
- Removed all paid iOS and Android apps.
- Identified app profiles that were successful on both iOS and Android platforms which
included:
  - iOS and Android data sets with most common genres in each market visualized in frequency tables.
  - iOS and Android apps by genre by average number of installs.


