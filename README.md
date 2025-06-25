# Netflix_Data_Analysis
Project Description:
This project aims to analyze the Netflix dataset to uncover meaningful insights about its content, such as distribution by genre, release trends, top contributing countries, and content ratings. The goal is to convert raw data into a beautiful, interactive Power BI dashboard that supports data-driven decisions and storytelling.

📁 Dataset:
📂 Source: Netflix Movies and TV Shows dataset on Kaggle
Contains information about:
Title, Type, Country, Release Year, Duration, Rating, Genre, Date Added, etc.

🛠️ Tools Used:
Python: Pandas, NumPy, Matplotlib
Power BI: For building an interactive dashboard
Jupyter Notebook / VS Code: For EDA


Project Workflow:
1. Data Collection
Imported dataset from Kaggle

2. Data Cleaning (Python)
Removed null values and duplicates
Split columns like duration and listed_in
Formatted date fields (date_added) into proper datetime format

3. Exploratory Data Analysis (EDA)
Total Movies vs TV Shows
Content distribution over years
Top 10 countries with most content
Genre frequency
Common content ratings
TV Show duration patterns (no. of seasons)

4. Data Visualization
Created visuals in Power BI:
Pie/Donut chart: Content Type
Line chart: Year-wise content trend
Bar chart: Country-wise content
Tree map: Content Ratings
Slicers: Country, Type, Rating

5. Dashboard Deployment
Interactive Power BI dashboard with filters & KPIs

Insights include:
Most content added post-2016
TV-MA and PG-13 are most common ratings
U.S., India, and U.K. lead in content count

📊 Sample Dashboard Preview:
(You can attach a screenshot here or add a Power BI .pbix file in your repo)

📈 Key Insights:
Majority of content is Movies (~70%)
U.S. dominates content distribution
Dramas, Documentaries, and Comedies are the top genres
Content growth spiked in 2018–2020
TV Shows usually last 1–2 seasons


