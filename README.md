# 📱 Google Play Store — Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-green?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-orange?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-yellow?style=for-the-badge&logo=jupyter)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle)

---

## 📌 Overview

A comprehensive EDA on the Google Play Store dataset from Kaggle. This project cleans, explores, and visualizes data from **10,841 apps** to uncover actionable insights for developers and businesses.

---

## 📁 Project Structure

📁 google-playstore-eda/  
├── 📓 google_playstore.ipynb — Main Jupyter Notebook  
├── 📄 googleplaystore.csv — Raw Dataset  
└── 📄 README.md — Project Documentation  

---

## 📊 Dataset Info

| Property      | Details        |
|--------------|----------------|
| Total Rows    | 10,841         |
| Total Columns | 13             |
| Clean Rows    | 10,346         |
| Source        | [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps/) |

---

## 🛠️ Libraries Used

- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Seaborn** — Statistical data visualization
- **Matplotlib** — Plotting and charting

> Install with:
> pip install pandas numpy seaborn matplotlib jupyter

---

## 🧹 Data Cleaning Summary

| Task | Details |
|------|---------|
| Size column | Converted M and k to bytes, Varies with device → NaN |
| Installs column | Removed + and , converted to integer |
| Price column | Removed $ sign, converted to float |
| Missing values | 1,695 in Size (15.6%), 1,474 in Rating (13.6%) — imputed/kept |
| Dropped rows | 12 rows with minor nulls in Category, Type, Genres etc. |
| Duplicates | 483 duplicate rows removed |

---

## 📈 Key Conclusions

1. **📱 Most Apps** — Family has the most apps (1,939), Game is 2nd (1,121)
2. **⭐ Highest Rated** — Events (4.39) → Education (4.37) → Books & Reference (4.36)
3. **📥 Most Installs** — Game leads with 31.5B installs; Communication is 2nd with 24.1B
4. **📝 Most Reviews** — Game leads with 1.41B reviews; Communication is 2nd
5. **💰 Free vs Paid** — Free apps get more installs; Paid apps get slightly higher ratings
6. **👨‍👩‍👧 Content Rating** — Everyone is the most common (8,372 apps) with highest installs

---

## 🚀 How to Run

1. Clone the repository
> git clone https://github.com/your-username/google-playstore-eda.git

2. Go into the folder
> cd google-playstore-eda

3. Install libraries
> pip install pandas numpy seaborn matplotlib jupyter

4. Open the notebook
> jupyter notebook google_playstore.ipynb

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://linkedin.com/in/your-linkedin)

---

## 🙏 Acknowledgements

Dataset by **Lavanya** on [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps/)

---

<p align="center">⭐ If you found this helpful, please star the repo! ⭐</p>
