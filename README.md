# 🍽️ Zomato Data Analysis Dashboard

This project focuses on analyzing restaurant data from Zomato to uncover insights about food trends, user preferences, restaurant ratings, and more.

The analysis was performed using **Python (Jupyter Notebook)** and the dashboard was built using **Power BI**.

---

## 📌 Project Workflow

1. **Dataset Collection**  
   The dataset was taken from [Kaggle](https://www.kaggle.com/datasets/darshangandhi/zomato-india-dataset?resource=download) and contains details about restaurants in India, including:
   - Name
   - Location
   - Ratings
   - Cuisine
   - Cost
   - Votes, etc.

2. **Data Cleaning & Preprocessing**  
   - Performed in **Jupyter Notebook**
   - Cleaned null values, handled duplicates, formatted columns, etc.
   - Exported the cleaned dataset as `.xlsx` for visualization

3. **Data Visualization**  
   - Imported the cleaned dataset into **Power BI**
   - Created custom measures (like Popularity Score, Vote Normalization, etc.)
   - Built a dynamic and interactive dashboard

---

## 📂 Files Included

- `ZomatoDataAnalysis.ipynb` – Jupyter Notebook for data cleaning & preprocessing
- `ZomatoDashboard.pbix` – Power BI file (dashboard)
- `README.md` – Project overview and documentation
- `datasetlink` – Contains links to the raw & cleaned datasets

---

## 🔗 Dataset & Dashboard Links

| File Type        | Description            | Link |
|------------------|------------------------|------|
| Raw Dataset       | Original dataset from Kaggle | [📥 Kaggle Dataset](https://www.kaggle.com/datasets/darshangandhi/zomato-india-dataset?resource=download) |
| Cleaned Dataset   | Cleaned `.xlsx` file from Jupyter | [📥 Download from Google Drive](https://docs.google.com/spreadsheets/d/1BZPBusa_wJoFHbcOXi9fX9EsRFNuTomT/edit?usp=sharing&ouid=103000238047034750178&rtpof=true&sd=true) |
| Power BI Dashboard | Final dashboard `.pbix` file | [📊 View/Download Dashboard](https://drive.google.com/file/d/1QaQELBqgIjmTeTv6DB1nPXH2VqmyRD-K/view?usp=sharing) |

> ⚠️ **Note:** The Power BI dashboard file is too large to preview directly on GitHub.  
> You can still download it by clicking on **"View Raw"** in the GitHub file view, or directly from the **Google Drive link** provided above.

---

## 📊 Dashboard Features

- Rating distribution histogram
- Cuisine-wise analysis
- City-wise restaurant count
- Popularity scoring
- Votes and cost correlation
- Interactive filters for city, cuisine, and price range

---

## 📌 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI
- Git & GitHub
