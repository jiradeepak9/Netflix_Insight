# Netflix_Insight
An interactive Power BI dashboard built to analyze Netflix’s catalog of movies and shows using IMDb ratings, votes, runtime, and release trends. The project uncovers performance insights, audience preferences, and rating patterns across genres, release years, and certifications.


# **The dashboard was built using the following tools and technologies**

- 📊 Power BI Desktop - Data modeling, dashboard design, interactive visuals.
- 🧠 DAX (Data Analysis Expressions) - Custom KPIs, Measures for IMDb averages, votes, and performance.
- 📝 Data Cleaning & Modeling (Star Schema) - Structured star-schema-like model for efficient queries.
- 📅 Excel - Input datasets for Netflix titles, metadata, and IMDb data.
- 📁 File Format – .pbix for development and .png for dashboard previews.

# **📂 Data Source**

The dataset includes Netflix Movies & Shows metadata, enriched with IMDb details: 

- title, type (Movie/Show)
- age_certification (TV-MA, PG, etc.)
- imdb_score, imdb_votes
- release_year, runtime
- Overall_Performance (calculated field)

# **🧠 Business Problem**
Netflix needed a way to:

- Measure quality vs quantity of its growing catalog.
- Understand IMDb ratings and votes distribution across movies vs shows.
- Identify top-performing movies based on audience reception.
- Detect trends in ratings over time (are newer titles performing better or worse?).

# **🎯 Goal of the Dashboard**
To create an executive-ready dashboard that:
- Provides KPIs like total titles, average IMDb score.
- Highlights audience engagement via IMDb votes.
- Tracks content quality across certifications, release years, and runtime.
- Surfaces top 5 movies with highest engagement.

# **📊 Walkthrough of Key Visuals**
            Visual	                                          Insight
    KPI Cards (5235 Titles, Avg IMDb Score 6.53)       Snapshot of Netflix library size and average audience reception.
    KPI Cards (5235 Titles, Avg IMDb Score 6.53)	   Snapshot of Netflix library size and average audience reception.
    Avg IMDb Score by Age Certification (Bar Chart)	   Reveals quality trends across certifications – e.g., TV-14 leads with 7.3 avg.
    Avg Votes by Type (Donut Chart)	                   Audience engagement split – movies receive ~60% votes, shows ~40%.
    Avg IMDb Score by Year (Line Chart)                Shows declining trend in recent years (7.0 in 2000 → 6.26 in 2022).
    Total Movies by Year (Line Chart)	               Explosive growth post-2000, content surge visible.
    Top 5 Movies (Treemap)	                           Highest IMDb-voted titles (Inception, Django Unchained, Forrest Gump).
    Avg Runtime by Movies (Bar Chart)	               Longest titles sorted, e.g., No Longer Kids, Once Upon a Time in America.

# **📈 Business Impact & Insights**
          Insight	                                  Business Value
    ⭐ Quality Decline Over Time	             Average IMDb scores decreased after 2010 → Netflix may need to invest more in quality over quantity.
    📊 Movies Drive Engagement	                 60% of IMDb votes go to movies → marketing strategy should prioritize blockbuster launches.  
    🧑‍🤝‍🧑 Certification Performance	             TV-14 titles perform best (avg 7.3) → expand family/teen friendly catalog.
    🎥 Top Movies Analysis	                     Classics like Inception & Forrest Gump drive huge engagement, proving long-term audience retention.
    📈 Content Explosion                        Post-2000	Supports Netflix’s global expansion and aggressive catalog acquisition.
    ⏱ Runtime Variation	                     Movies with longer runtimes aren’t necessarily higher rated, showing runtime isn’t a predictor of quality.

 📊**Screenshot and Demo**

![Dashboard Overview]()
![Dashboard Overview]()

# **🔧 Features**
- Interactive filters (Year, Movies vs Shows)
- Dynamic IMDb performance metrics
- Certification-wise analysis
- Audience engagement through IMDb votes
-Top movie drilldowns

# **🚀 Future Enhancements**
- Add genre-level analysis (action, drama, comedy).
- Integrate Netflix Originals vs Licensed content comparison.
- Add forecasting: predict IMDb ratings based on historical trends.
- Incorporate geographical analysis (regional content demand).

# **🔗 Tags**
#PowerBI #NetflixAnalytics #Dashboard #IMDb #BusinessIntelligence #DataVisualization
