<h1>✈️FlySight: Airline Review Analyzer
FlySight is a data-driven project focused on collecting, analyzing, and visualizing customer reviews for British Airways. By scraping data from Skytrax — a well-known airline review platform — this project uncovers actionable insights into customer satisfaction, sentiment trends, and overall service quality.
Project Objective
To analyze customer reviews of British Airways and provide clear, visual insights into customer ratings, sentiments, and experience patterns. The goal is to help stakeholders identify strengths and areas of improvement in BA's services.
Key Features
•	✅ Web scraping of user reviews from Skytrax
•	✅ Cleaning and preprocessing of textual and numerical data
•	✅ Exploratory data analysis (EDA) using pandas, seaborn, and matplotlib
•	✅ Visualization of: star rating distribution, average ratings by country, word clouds from review text, sentiment breakdown of reviews
•	✅ Highlighting top-rated countries and most common feedback themes
Tech Stack
•	• Python
•	• Pandas – data wrangling
•	• BeautifulSoup – web scraping
•	• Seaborn & Matplotlib – data visualization
•	• WordCloud – for visualizing frequent words
•	• Jupyter Notebook – for analysis and presentation
Sample Visualizations
•	📌 Bar plot of review ratings
•	📌 Country-wise average rating comparison
•	📌 Word cloud for most frequent review terms
•	📌 Breakdown of positive vs negative reviews (if sentiment analysis is extended)
How to Run
1. Clone this repository
   git clone https://github.com/yourusername/FlySight-Airline_Review_Analyzer.git
   cd FlySight-Airline_Review_Analyzer
2. Install required packages
   pip install -r requirements.txt
3. Run the Jupyter Notebook
   jupyter notebook
Project Structure

FlySight-Airline_Review_Analyzer/
├── data/                     # Raw and cleaned datasets
├── notebooks/                # Jupyter notebooks for EDA and visualization
├── visuals/                  # Saved plots and word clouds
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation

Future Enhancements
•	🚀 Add sentiment classification (positive/negative/neutral)
•	🚀 Extend analysis to multiple airlines for comparison
•	🚀 Time series analysis of review trends over the years
