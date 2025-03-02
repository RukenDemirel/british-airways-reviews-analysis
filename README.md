# British Airways Reviews: Web Scraping &amp; Sentiment Analysis

## 📌 Project Overview
This project analyzes British Airways customer reviews collected from [Skytrax](https://www.airlinequality.com/) to understand sentiment trends, passenger satisfaction, and key factors influencing airline ratings. Using web scraping, data cleaning, sentiment analysis, and data visualization, this study uncovers insights into customer experiences and airline performance.

## 🔍 Data Collection
The dataset was obtained via web scraping using BeautifulSoup and requests to extract structured information from Skytrax. The collected data includes:

- Review text
- Rating (0-10 scale)
- Date of review
- Reviewer’s location
- Type of traveler (e.g., business, solo, family)
- Aircraft model
- Seat type (e.g., economy, business)
- Recommendation status (recommended/not recommended)

## 🛠️ Data Cleaning
The raw data was processed to ensure accuracy and consistency. Key steps included:

- Removing missing values and incomplete reviews
- Eliminating duplicate entries
- Standardizing text format by removing special characters and extra spaces
- Converting dates to datetime format for trend analysis
  
## 📊 Sentiment Analysis
VADER (Valence Aware Dictionary and sEntiment Reasoner) was used to determine the overall sentiment of each review. Each review was classified as:

- Positive (score ≥ 0.05)
- Neutral (-0.05 to 0.05)
- Negative (≤ -0.05)

### Sentiment Trends
- Sentiment distribution was visualized using bar charts.
- Time-series analysis was conducted to observe trends in sentiment over time.

## ✈️ Ratings Analysis
- Seat Type: Investigating how ratings vary by seat class (economy, business, etc.).
- Seasonal Trends: Identifying fluctuations in customer satisfaction across different months.
- Location-Based Ratings: Comparing passenger ratings across various countries.
- Traveler Type: Analyzing differences in ratings based on traveler categories.

## 📊 Visualizations & Insights
- Python (Matplotlib, Seaborn): Used to generate sentiment trends, rating distributions, and recommendation breakdowns.
- Tableau Dashboard: Built for interactive exploration of customer reviews, including sentiment trends, ratings by seat type, and recommendation status.
- Click [here](https://public.tableau.com/app/profile/ruken.demirel/vizzes) to see Tableau dashboard

## 🚀 Technologies Used
- Python (Pandas, NumPy, BeautifulSoup, Matplotlib, Seaborn, NLTK)
- Sentiment Analysis: VADER (Natural Language Processing)
- Web Scraping: BeautifulSoup, Requests
- Data Visualization: Matplotlib, Seaborn, Tableau
  
## 📌 Key Takeaways
-The overall rating for British Airways is 5.2/10, with service areas such as food, entertainment, and value for money receiving lower scores.
-54% of customers do not recommend British Airways.
-First Class has the highest ratings, while Economy Class has the lowest.
-Sentiment analysis shows positive reviews are more frequent than negative ones, but sentiment scores vary based on rating, review length, and time period.
-2023-2024 has seen an increase in negative reviews, suggesting a decline in customer satisfaction.

