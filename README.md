# 📊 YouTube Trending Data Science Dashboard

A **Full-Stack Data Science** application designed to uncover the hidden patterns behind viral content. This project uses **Pandas** for exploratory data analysis (EDA), **FastAPI** to serve insights, and an **HTML/JS** frontend to visualize global YouTube trends.

---

## 🔬 The Data Science Workflow

1.  **Data Acquisition:** Ingesting multi-regional CSV datasets.
2.  **Data Cleaning:** Handling missing values and formatting dates with Pandas.
3.  **Feature Engineering:** Creating custom engagement metrics (Likability & Velocity).
4.  **Insight Visualization:** Mapping complex data into interactive Chart.js graphs.

---

## 🏗️ The Tech Stack

| Layer | Technology | Role |
| :--- | :--- | :--- |
| **Frontend** | HTML5 / CSS / JS | Data Visualization (Chart.js) |
| **Backend** | FastAPI | Analytical API Layer |
| **Analysis** | Pandas | Data Science Engine |
| **Infrastructure**| Docker | Reproducible Environment |

---

## 💡 Key Research Questions Answered
* **Category Dominance:** Which genres (Music vs. Gaming) stay trending the longest?
* **Engagement Ratios:** Does a high view count always correlate with a high "Likability" score?
* **Timing Optimization:** What is the "Golden Hour" for publishing to increase trending probability?

---

## 🛠️ Setup & Deployment
```bash
# Build the data science environment
docker-compose up --build
