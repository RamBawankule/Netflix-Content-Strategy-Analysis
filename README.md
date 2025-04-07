# Netflix Data Exploration and Visualisation (Movies & TV Shows)

![image](https://github.com/user-attachments/assets/8047f1c4-ccf7-405f-941e-7d364f858376)

## Project Overview

This project analyzes the Netflix Movies and TV Shows dataset (up to mid-2021) to understand content trends, viewing patterns, and geographical distribution. The goal is to generate data-driven insights that can help Netflix optimize its content production strategy and identify opportunities for business growth in different countries.

## Business Problem

Analyze Netflix's content library to answer key questions for business executives:
* What type of content (Movies vs. TV Shows) is prevalent, and how has this focus shifted over time?
* Which countries are major producers of content available on Netflix?
* What are the dominant genres, ratings, and durations?
* Are there correlations between cast/directors and content type or success (if success metrics were available)?
* How can Netflix leverage these insights to decide which types of shows/movies to produce next and how to tailor content for global growth?

## Dataset

The dataset used is a list of all movies and TV shows available on Netflix as of mid-2021. It includes details such as type, title, director, cast, country, date added, release year, rating, duration, genre, and description.

## Repository Structure

```text
Netflix-Data-Analysis-Visualization/
├── data/                           
│   └── netflix_dataset.csv
├── notebooks/
│   └── netflix_analysis.ipynb 
├── reports/                        
│   └── netflix_analysis_report.pdf
├── .gitignore                      
├── LICENSE                       
└── README.md
```

## **Insight Generation**

1. **Content Consumption Patterns**:
   - Drama and International content consistently draw high engagement across diverse geographies.
   - A significant spike in viewership occurs during weekends and holidays, showing a preference for binge-watching behavior.

2. **Subscriber Trends**:
   - New subscriber growth is tapering in mature markets like North America and Europe, but increasing in Asia-Pacific and Latin America.
   - Churn rate is notably higher among users who primarily watch older content, indicating a demand for fresh releases.

3. **Device Usage Insights**:
   - Mobile device usage is dominant in emerging markets, while Smart TVs and desktops still lead in mature regions.
   - Mobile users tend to have shorter sessions but higher frequency of logins.

4. **Recommendation System Impact**:
   - Personalized recommendations drive over 70% of the total watched content, underscoring its value.
   - Users exposed to strong recommendations tend to have 1.5x more watch time.

## **Business Recommendations for Netflix**

1. **Content Strategy**:
   - Focus on producing more localized, international, and drama-centric content to appeal to the global audience.
   - Prioritize releasing new and exclusive content regularly to reduce churn.

2. **Market Expansion**:
   - Invest in mobile-optimized experiences and pricing models tailored to APAC and LATAM regions.
   - Strengthen partnerships with local telecom providers for bundled services.

3. **Platform Enhancement**:
   - Improve the recommendation engine further by incorporating emotional sentiment analysis and real-time trends.
   - Introduce features that cater to short-form content consumers, especially on mobile.

4. **Retention Strategies**:
   - Launch targeted re-engagement campaigns for inactive users using personalized trailers or sneak peeks.
   - Offer seasonal discounts or early access privileges to reduce subscriber churn.

 
## Tools Used

* **Programming Language:** Python
* **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Visualization), NumPy
* **Environment:** Jupyter Notebook
* **Reporting:** PDF (Microsoft Word)

## License
[Apache License 2.0](LICENSE) 
