# IMDB-Movies-Data-Analysis

This project involves analyzing IMDb movie data to extract valuable insights, such as trends in genres, ratings, and production companies. The dataset includes 10,000 rows with details about movies like budgets, grosses, ratings, and more.

**Project Workflow**

**Data Collection**:
Scraped data for 10,000 movies from IMDb, extracted various values including 
Genre , Ratings , Metascore , Budget , GRoss Revenue , Movie Title, etc
Technology used: Python , Javascript in console, selenium and beautiful soup

**Data Overview**:
The data used for this project was sourced from IMDb through web scraping. It consists of detailed information about 10,000 movies, including their financial performance, ratings, and production details. Dataset Summary:Rows: 10,000 , Columns: 22 , The Budget and Gross values are extracted and cleaned from multiple pages.
Data Characteristics:
Numerical Columns: Budget, Rating, Metascore, Duration etc.
Categorical Columns: Genre, Director Name, Actor Names etc.
Missing Values: The Metascore column has approximately 10% missing values

**Data Cleaning**:
The raw IMDb dataset contained missing values, inconsistent formats, and outliers that could have impacted the analysis. Cleaning was essential to improve data quality and ensure reliable results
Technologies Used:Python libraries such as Numpy and Pandas
Problem Faced: Some columns like Metascore have missing values , The Duration column had mixed formats (e.g., 2h 30m and 150 minutes), which required cleaning.

**Exploratory Data Analysis(EDA)**:
Exploratory Data Analysis was conducted to understand the characteristics of the dataset, identify trends in the data, and detect potential correlations between key features like budget, ratings, and revenue."
Technologies Used: Python libraries like Pandas, Matplotlib, and Seaborn.
Steps:
Explored relationships between Budget and Gross Worldwide, Vote Count as well as Rating and Metascore, using scatterplots and correlation matrices.
Analyzed the distribution of key features like Rating, Duration, and Budget using histograms and boxplots
Explored what are the top performing Actor and Director pair
Key Findings: Movies with higher budgets tend to have better gross revenue but not necessarily better ratings.
Thriller movies dominate the top-grossing films, The average duration of movies has slightly decreased over the decades.
Vote Count effect the overall performance of the movie so if they are god movie will perform well else not

**Dashboarding**:
The IMDb Dashboard provides an interactive platform for exploring and analyzing movie data. It was designed to showcase trends, insights, and key metrics in an accessible and visually appealing format.
Tools Used: Microsoft Power BI
Key Features:
Top Movies: A bar chart displaying the top 10 movies by gross revenue.
Genre Insights: A pie chart showing the distribution of movies across genres.
Trends Over Time: A line graph visualizing gross revenue trends by release year.
Filters: Users can filter data by genre, year, and rating.
KPIs: Metrics like average rating, total revenue, and most popular genres.

**Answered Several Questions Such as**:
1. Movie Trends Over Time:
   - How has the number of movies released each year changed?
   - What are the most popular genres over the years?
   - What trends are observed in movie durations (e.g., are movies getting longer or shorter over time)?
     
2. Ratings Distribution:
   - What is the overall distribution of movie ratings?
   - How many movies fall into specific rating categories (e.g., below 5, between 5–7, above 7)?

3. Top Movies:
   - What are the highest-rated movies?
   - Which movies have the longest durations?
   - Which movies have the highest metascores?

4. Actor Insights:
   - Who are the most frequently appearing actors?
   - Which actor has the highest average star rating?
   - Who are the most versatile actors (appearing in diverse genres)?

5. Director Insights:
   - Which director has directed the most movies?
   - Who is the director with the highest average star rating?
   - Do certain directors specialize in specific genres?

6. Actor-Director Collaborations:
   - Which actor-director pairs produce the highest-rated movies?
   - Are there collaborations that occur frequently but have poor ratings?

7. Genre Popularity:
   - What are the most common genres in the dataset?
   - Which genres have the highest average ratings?
   - Are certain genres associated with longer or shorter movies?

8. Budget and Revenue Analysis:
   - Is there a correlation between budget and ratings?
   - Are higher-budget movies generally better rated?

9. Star Power:
   - Do movies with top-rated actors or directors tend to perform better?
   - Are there any underperforming actors/directors despite frequent appearances?

10. Yearly Comparisons:
   - Which year had the highest average movie rating?
   - Are there "golden years" for movies?

11. Actor Comparisons:
   - How do actors compare in terms of average ratings?
   - Who are the top 5 actors with the highest-rated movies?

12. Director Comparisons:
   - How do directors compare in terms of average ratings?
   - Are there directors who are consistently average (neither top-rated nor bottom-rated)
    
13. Correlations:
   - Is there a correlation between metascore and star rating?
   - Do movie durations correlate with star ratings or metascores?
 
14. Popularity:
   - (If included) Which movies have the most user reviews or votes?
   - Are highly-rated movies also the most popular?

15. Director or Actor Influence:
   - Do star directors or actors tend to boost movie ratings significantly?

**Technologies Used**
Programming Languages: Python
Libraries: Pandas, NumPy, Requests, BeautifulSoup ,Selenium, Matplotlib, Seaborn
Visualization: Power BI

**Contributing**:
Feel free to fork this repository, make enhancements, and submit a pull request.




































👋 Hi, I’m Palash Karda
👀 I’m interested in data science, machine learning, and generative AI
🌱 I’m currently learning machine learning and generative AI
💞️ I’m looking to collaborate on data analysis and machine learning projects
📫 How to reach me: palashkarda10@gmail.com
😄 Pronouns: He/Him
⚡ Fun fact: I enjoy exploring new tech!
