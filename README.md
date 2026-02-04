# 📊 Exploratory Data Analysis of Google Play Store Apps

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Google Play Store Apps dataset to understand app popularity, user engagement, pricing trends, and other key insights.  
The analysis focuses on identifying patterns in installs, reviews, ratings, categories, and app types (Free vs Paid).

---

## 📂 Dataset
- **Source:** Google Play Store Apps Dataset  
- **Records:** Apps available on the Google Play Store  
- **Key Features:**
  - App
  - Category
  - Rating
  - Reviews
  - Size
  - Installs
  - Type (Free / Paid)
  - Price
  - Content Rating
  - Genres
  - Last Updated
  - Android Version

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🔍 Data Cleaning Steps
- Removed special characters (`$`, `+`, `,`, `M`, `k`)
- Converted columns to proper numeric formats
- Handled missing and null values
- Standardized Android version values
- Extracted date features (day, month, year)

---

## 📈 Key Analysis Performed
- Category-wise installs and reviews
- Free vs Paid app comparison
- App-level popularity and engagement
- Rating analysis by category
- Content rating impact on installs
- Android version compatibility analysis
- Genre-level trends
- Time-based analysis of app updates

---

## 📊 Key Insights
- **Game apps** are the most installed and most reviewed category
- **Free apps dominate** the Play Store in both count and installs
- Paid apps generally have **slightly higher ratings**
- Apps rated **“Everyone”** achieve the highest reach
- Supporting **older Android versions** increases app installs
- A small number of apps dominate installs and reviews (long-tail distribution)

---

## ✅ Final Conclusion
The Google Play Store ecosystem is driven by **free, widely compatible, and entertainment-focused apps**, especially games.  
While popularity brings massive installs and reviews, higher quality ratings are often achieved by niche apps with smaller audiences.

---

## 📁 Files in Repository
- `Google_play_store.ipynb` → Jupyter Notebook with full EDA
- `df_copy.csv` → Cleaned dataset
- `README.md` → Project documentation

---

## 🚀 How to Run
1. Clone the repository  
2. Open `Google_play_store.ipynb` in Jupyter Notebook  
3. Run all cells sequentially  

---

## ✨ Future Scope
- Predict app installs using machine learning
- Sentiment analysis on user reviews
- Recommendation system for app categories

---

## 👤 Author
**Soumya Saha**

---

## 📌 License
This project is for educational and learning purposes.
