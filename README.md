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

​```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
​```

> Install with:
> ​```bash
> pip install pandas numpy seaborn matplotlib jupyter
> ​```

---

## 🧹 Data Cleaning Summary

| Task | Details |
|------|---------|
| `Size` column | Converted `M` and `k` to bytes, `Varies with device` → NaN |
| `Installs` column | Removed `+` and `,`, converted to integer |
| `Price` column | Removed `$`, converted to float |
| Missing values | 1,695 in Size (15.6%), 1,474 in Rating (13.6%) — imputed/kept |
| Dropped rows | 12 rows with minor nulls in Category, Type, Genres, etc. |
| Duplicates | 483 duplicate rows removed |

---

## 📈 Key Conclusions

1. **📱 Most Apps** — `Family` has the most apps (1,939), `Game` is 2nd (1,121)
2. **⭐ Highest Rated** — `Events` (4.39) → `Education` (4.37) → `Books & Reference` (4.36)
3. **📥 Most Installs** — `Game` leads with 31.5B installs; `Communication` is 2nd with 24.1B
4. **📝 Most Reviews** — `Game` leads with 1.41B reviews; `Communication` is 2nd
5. **💰 Free vs Paid** — Free apps get more installs; Paid apps get slightly higher ratings
6. **👨‍👩‍👧 Content Rating** — `Everyone` is the most common (8,372 apps) with highest installs

---

## 🚀 How to Run

​```bash
git clone https://github.com/your-username/google-playstore-eda.git
cd google-playstore-eda
pip install pandas numpy seaborn matplotlib jupyter
jupyter notebook google_playstore.ipynb
​```

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
