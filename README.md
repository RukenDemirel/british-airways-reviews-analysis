British Airways Reviews: Web Scraping &amp; Sentiment Analysis
📌 Overview
This project analyzes British Airways customer reviews collected from Skytrax to understand sentiment trends, passenger satisfaction, and key factors influencing airline ratings. Using web scraping, data cleaning, sentiment analysis, and data visualization, this study uncovers insights into customer experiences and airline performance.

🔍 Data Collection
The dataset was obtained via web scraping using BeautifulSoup and requests to extract structured information from Skytrax. The collected data includes:

Review text
Rating (0-10 scale)
Date of review
Reviewer’s location
Type of traveler (e.g., business, solo, family)
Aircraft model
Seat type (e.g., economy, business)
Recommendation status (recommended/not recommended)
🛠️ Data Cleaning
The raw data was processed to ensure accuracy and consistency. Key steps included:

Removing missing values and incomplete reviews
Eliminating duplicate entries
Standardizing text format by removing special characters and extra spaces
Converting dates to datetime format for trend analysis
📊 Sentiment Analysis
To determine the overall sentiment of each review, VADER (Valence Aware Dictionary and sEntiment Reasoner) was used. Each review was classified as:

Positive (score ≥ 0.05)
Neutral (-0.05 to 0.05)
Negative (≤ -0.05)
Sentiment Trends
Sentiment distribution was visualized using bar charts.
Time-series analysis was conducted to observe trends in sentiment over time.
✈️ Ratings Analysis
Seat Type: Investigating how ratings vary by seat class (economy, business, etc.).
Seasonal Trends: Identifying fluctuations in customer satisfaction across different months.
Location-Based Ratings: Comparing passenger ratings across various countries.
Traveler Type: Analyzing differences in ratings based on traveler categories.
📊 Visualizations & Insights
Python (Matplotlib, Seaborn): Used to generate sentiment trends, rating distributions, and recommendation breakdowns.
Tableau Dashboard: Built for interactive exploration of customer reviews, including sentiment trends, ratings by seat type, and recommendation status.
🚀 Technologies Used
Python (Pandas, NumPy, BeautifulSoup, Matplotlib, Seaborn, NLTK)
Sentiment Analysis: VADER (Natural Language Processing)
Web Scraping: BeautifulSoup, Requests
Data Visualization: Matplotlib, Seaborn, Tableau
📌 Key Takeaways
A large proportion of reviews were negative, highlighting areas for service improvement.
Business class received higher ratings compared to economy class.
Seasonal variations affected overall customer satisfaction.
Regional differences in reviews suggest varying customer expectations.
Many customers did not recommend British Airways, indicating areas for potential improvement.

