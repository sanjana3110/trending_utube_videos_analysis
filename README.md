# YouTube Trending Video Analytics
## 📌 Overview
This project analyzes YouTube trending videos across multiple regions to uncover patterns in popularity, sentiment, and regional preferences. Using Python (for data cleaning and sentiment analysis), SQL (for querying insights), and Tableau (for visualization), the project identifies key trends to help creators and marketers optimize content strategies.

**Key Questions Answered**:
- Which video categories dominate trending lists?
- How does sentiment in video titles correlate with popularity?
- What are the regional differences in trending content?

---

## 🛠️ Tools & Technologies
- **Python**: `pandas`, `TextBlob`, `matplotlib`, `seaborn`  
- **SQL**: SQLite for querying and aggregation  
- **Tableau**: Interactive dashboards  
- **Data Source**: [YouTube Trending Videos Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new) (Kaggle)  

---

## 📂 Project Structure
youtube-trending-analytics/
├── data/ # Raw and cleaned datasets
│ ├── raw/ # Original datasets (CSV/JSON)
│ └── processed/ # Cleaned and sentiment-labeled data
├── notebooks/ # Jupyter notebooks for analysis
│ ├── 1_data_cleaning.ipynb
│ ├── 2_sentiment_analysis.ipynb
│ └── 3_sql_analysis.ipynb
├── sql/ # SQL queries and scripts
├── tableau/ # Tableau workbook and exports
├── README.md # This file
└── requirements.txt # Python dependencies
