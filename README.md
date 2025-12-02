# netflix_titles

- Title / Purpose
  - Overview of the dataset (Netflix titles) and objectives (explore dataset, extract insights, visualize trends).

- Data loading
  - Read netflix_titles.csv into a DataFrame (pandas).
  - Display of initial rows and basic info (shape, dtypes).

- Data cleaning / preprocessing
  - Handling missing values (e.g., cast, director, date_added).
  - Converting date fields to datetime, parsing numeric durations.
  - Removing duplicates and normalizing text fields (strip, lower).

- Exploratory data analysis (EDA)
  - Dataset summary: number of titles, breakdown by type (Movie vs TV Show).
  - Counts and distributions: release year distribution, date_added distribution.
  - Top contributors: top directors, top actors/cast members.
  - Geographic distribution: counts by country.
  - Genre / category analysis: most frequent listed genres or listed_in categories.
  - Rating analysis: counts by content rating (TV-MA, PG-13, etc.).
  - Duration analysis: runtime distributions for movies and seasons for TV shows.

- Time-trend analysis
  - Trends in titles added to Netflix over time (by year/month).
  - Release-year vs. addition-year comparisons.

- Cross-analysis / segmentation
  - Popular genres by country or by year.
  - Director/actor relationships with ratings or popularity proxies (if available).
  - Correlations or relationships (e.g., release year vs. duration).

- Visualizations
  - Bar charts (top categories, top directors).
  - Histograms (release years, durations).
  - Time series plots (titles added per year/month).
  - Heatmaps or pivot tables (genre × country or genre × year).

- Summary / conclusions
  - Key observations (e.g., dominant genres, growth/decline trends).
  - Potential follow-ups or questions for deeper analysis.

