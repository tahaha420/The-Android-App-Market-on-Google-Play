# 📱 The Android App Market on Google Play

## 🧩 Project Overview
Mobile apps are everywhere — they’re easy to create and can be highly profitable. Because of this, the app ecosystem is growing rapidly, with millions of apps competing for user attention.  

In this project, I conducted a **comprehensive analysis of the Android app market** using scraped data from **Google Play Store**, covering over **10,000+ apps** across multiple categories.  
The goal was to uncover insights that can help developers and businesses **drive growth, improve retention, and identify market opportunities**.

---

## 📊 Dataset Description

### 1. `apps.csv`
Contains all the details of the apps on Google Play.  
Each row describes an app with the following features:
- `App` — Name of the app  
- `Category` — App category (e.g., GAME, BUSINESS, TOOLS)  
- `Rating` — Average user rating  
- `Reviews` — Number of user reviews  
- `Size` — Size of the app  
- `Installs` — Number of installations  
- `Type` — Free or Paid  
- `Price` — Price in USD  
- `Content Rating` — Target age group  
- `Genres` — App genres  
- `Last Updated`, `Current Ver`, `Android Ver` — Metadata

### 2. `user_reviews.csv`
Contains 100 most helpful reviews per app, each tagged with a sentiment score.  
Columns include:
- `App` — Name of the app  
- `Translated_Review` — Cleaned and preprocessed review text  
- `Sentiment` — Positive, Negative, or Neutral  
- `Sentiment_Polarity` — Sentiment intensity score  

---

## 🧠 Project Tasks & Workflow

### 1. Data Loading and Cleaning
- Loaded datasets (`apps.csv` and `user_reviews.csv`)  
- Removed duplicates and missing values  
- Corrected data types for numerical and categorical consistency  

### 2. Exploratory Data Analysis (EDA)
- **Explored app categories:** Identified which categories dominate the Play Store  
- **Distribution of app ratings:** Checked the spread of app ratings and average user satisfaction  
- **Size and price analysis:** Investigated how app size and pricing vary across categories  
- **Price vs. category relation:** Studied which app types tend to be free or paid  
- **Filtered “junk” apps:** Removed low-quality or irrelevant apps for cleaner insights  

### 3. Market Insights
- **Popularity of paid vs free apps:** Compared installs and ratings  
- **Sentiment analysis:** Used review data to assess user satisfaction levels by category  
- **Data visualizations:** Created plots to illustrate key findings (category distribution, price trends, sentiment proportions, etc.)

---

## 📈 Key Insights
- Most apps on Google Play are **free**, but **paid apps** often have **higher average ratings**.  
- The **GAME** and **FAMILY** categories dominate in volume and installs.  
- **Business**, **Education**, and **Health & Fitness** categories show strong growth potential.  
- Sentiment analysis reveals that apps with **frequent updates** tend to have **more positive reviews**.  

---

## 🧰 Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook / Google Colab**  
- **Natural Language Processing (NLP)** for sentiment analysis  
- **Data Visualization** for insight discovery  

---

