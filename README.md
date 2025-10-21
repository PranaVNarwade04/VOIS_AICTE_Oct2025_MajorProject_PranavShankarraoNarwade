# VOIS_AICTE_Oct2025_MajorProject_PranavShankarraoNarwade
Data analysis of Netflix content trends (Movies/TV, Genres, Countries) using Python to derive strategic insights.
Netflix Data Analysis: Content Trends for Strategic Recommendations
VOIS_AICTE_Oct2025_MajorProject_YourName

1. Introduction & Problem Statement
Netflix is a leading global streaming platform, but it faces intense competition. To stay competitive, Netflix must make data-driven decisions about its content strategy.

Problem Statement: This project analyzes the Netflix dataset (7,789 titles) to uncover content trends. The aim is to understand how Netflix's content distribution (Movies vs. TV Shows, genres, and country contributions) has evolved, providing strategic insights for global content expansion.

2. Project Objectives
Analyze the distribution of Movies vs. TV Shows added to the platform over the years.

Identify the most common genres and analyze how their popularity has trended.

Compare country-wise contributions to Netflix’s content catalog.

3. Methodology
Data Cleaning:
- Loaded the Netflix Dataset.csv file.
- Removed 19 duplicate and invalid rows.
- Filled missing values in Director, Cast, and Country with "Unknown".
- Converted the Release_Date column to a proper datetime format.
- Created a new Year_Added column for time-series analysis.

Exploratory Data Analysis (EDA):
Analyzed and visualized trends for all three project objectives using Python libraries (Pandas, Matplotlib, Seaborn).

Technologies Used:
-Python
-Pandas (for data manipulation and cleaning)
-Matplotlib & Seaborn (for data visualization)
-Google Colab (as the development environment)

4. Key Insights & Visualizations
- Objective 1: Movies vs. TV Shows Over Time
Insight: Netflix's content library grew exponentially after 2015. While Movies are more numerous, the number of TV Shows added grew at a much faster rate, reflecting a strategic shift to "binge-worthy" original series.

- Objective 2: Top Genres and Their Trends
Insight: "International Movies," "Dramas," and "Comedies" are the backbone of the library. The high ranking of "International Movies" & "International TV Shows" proves Netflix's heavy investment in a global content strategy.

- Objective 3: Top Content Producing Countries
Insight: The US is the #1 content producer, but key international hubs are critical. India is the clear #2 producer and the UK is #3, highlighting a strategy of investing in countries with strong, established media industries.
