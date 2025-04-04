# Netflix Movies & TV Shows Analysis

## 📌 Project Overview
This project analyzes the Netflix Movies & TV Shows dataset to extract valuable insights about content distribution, trends over time, and popular genres. The goal is to help Netflix (or streaming platforms in general) make data-driven decisions about content production and acquisition.

## 📊 Dataset Information
- **Source:** [Netflix Movies & TV Shows Dataset (Kaggle)](https://www.kaggle.com/datasets)
- **Total Entries:** 8,807
- **Columns:** 12 (Show ID, Title, Type, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Listed In, Description)

## 🎯 Objectives & Key Questions
This project aims to answer:
1. What type of content dominates Netflix (Movies vs TV Shows)?
2. Which countries produce the most content on Netflix?
3. How has Netflix’s content production evolved over time?
4. What are the most popular genres?
5. What is the distribution of movie durations?
6. What trends can help Netflix focus on better content in 2025?

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Database:** SQLite (for SQL analysis)

## 🚀 Implementation Steps
### 1️⃣ Data Cleaning & Preprocessing
- Removed missing values and duplicates
- Converted `date_added` to datetime format
- Extracted `year_added` and `month_added`
- Cleaned `duration` column (converted to numeric values)

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized content distribution (Movies vs TV Shows)
- Analyzed top contributing countries
- Examined genre trends using word clouds
- Studied content addition trends over time

### 3️⃣ SQL Analysis (Key Insights)
- Found the top 10 directors with the most content
- Identified the most popular genres
- Analyzed the frequency of content addition by year

## 📈 Key Insights & Findings
- Movies dominate Netflix (~70%) compared to TV Shows.
- The **United States, India, and the United Kingdom** are the top content-producing countries.
- **Dramas and Comedies** are the most frequent genres.
- Content production **spiked significantly after 2015**, showing Netflix’s rapid expansion.

## 🔧 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-analysis.git
   cd netflix-analysis
   ```
2. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn sqlite3
   ```
3. **Run the analysis script:**
   ```bash
   python netflix_analysis.py
   ```

## 📜 Future Improvements
- Implement machine learning to predict trending genres.
- Integrate IMDb ratings for more insights.
- Perform sentiment analysis on movie descriptions.

## 📢 Contributing
Feel free to fork this repository and contribute by improving data visualizations or adding new analyses.

## 📬 Contact
For any questions, reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or email at your.email@example.com.

---
🛠 **By:** Your Name | 🚀 **GitHub:** [YourUsername](https://github.com/YourUsername)

