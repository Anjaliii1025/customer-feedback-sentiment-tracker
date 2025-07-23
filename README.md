# ✈️ Customer Feedback Sentiment Tracker

This project analyzes customer feedback related to airline services, using Twitter sentiment data. The goal is to visualize sentiment trends and derive key insights using basic data analysis and visualization techniques.

---

## 📌 Objective

To track and visualize customer sentiment from Twitter feedback using pre-labeled sentiment data (`Positive`, `Neutral`, `Negative`). This helps identify customer satisfaction levels and highlights areas of improvement for airlines.

---

## 🗃️ Dataset

- **Source:** [Kaggle – Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- **Fields Used:**
  - `text`: The feedback (tweet)
  - `airline_sentiment`: Labeled sentiment (positive/negative/neutral)

---

## 📊 Project Outputs

### ✔️ Visualizations:
- **Bar Chart:** Count of each sentiment category
- **Pie Chart:** Percentage distribution of sentiments
- **Table:** Sample feedback with sentiment labels

### ✔️ KPIs:
- 👍 Positive Feedback %
- 👎 Negative Feedback %
- 😐 Neutral Feedback %

---

## 🧰 Tools & Libraries

- `pandas` for data manipulation  
- `matplotlib` and `seaborn` for visualizations  

---

## 📌 Key Insights

- Most tweets are **negative**, indicating a general trend of dissatisfaction among users.
- **Positive feedback** is relatively low, showing potential improvement areas.
- **Neutral sentiment** occupies a moderate space, reflecting mixed reactions.

