# 🎬 MovieLens 100K Data Analysis with Python

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Made with Pandas](https://img.shields.io/badge/Made%20with-Pandas-150458?logo=pandas)](https://pandas.pydata.org/)
[![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-0099CC)](#)

> A Python-based project for performing EDA, visualization, and insight generation on the [MovieLens 100K dataset](https://grouplens.org/datasets/movielens/100k/), exploring user ratings, demographics, and genre trends.

---


## ❓ Problem Statement

This project is built using the MovieLens 100K dataset from the GroupLens Research Project at the University of Minnesota. It is widely used for collaborative filtering and recommendation systems, but here, the goal is to demonstrate Python proficiency in data handling, analysis, and visualization.

### Dataset:
- Downloaded from [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/)
- Files used:
  - `u.data`: user ratings
  - `u.item`: movie metadata
  - `u.user`: user demographics

### Objectives:
- Perform exploratory data analysis (EDA)
- Create univariate plots for: `rating`, `age`, `release date`, `gender`, `occupation`
- Visualize how **popularity of genres** has changed over the years
- Display **Top 25 movies** by average rating (only movies with ≥ 100 ratings)
- Verify:
  - Do men watch more Drama and Romance than women?
  - Do women watch more Sci-Fi than men?

This hands-on project demonstrates the use of Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to draw actionable insights from entertainment data.


---

## 📌 Project Overview

This project showcases key data analysis skills using Python by working with the MovieLens 100K dataset. It covers:

- Data loading and wrangling from multiple sources
- Exploratory Data Analysis (EDA)
- Univariate and bivariate visualizations
- Insight extraction on genre popularity and user behavior

---

## 🧠 Learning Objectives

- Work with real-world structured datasets
- Practice data cleaning and preprocessing
- Build visualizations using Matplotlib and Seaborn
- Draw business-relevant conclusions from user activity and preferences

---

## 📊 Project Tasks

✅ Load and merge data from:
- `u.data` – Movie ratings
- `u.item` – Movie metadata
- `u.user` – User demographics

✅ Analyze and visualize:
- Distribution of ratings, age, gender, and occupations
- Genre popularity trends by year
- Top 25 highest-rated movies with at least 100 reviews
- Gender-based genre viewing preferences (Drama, Romance, Sci-Fi)

✅ Techniques used:
- Pandas for manipulation
- NumPy for numerical operations
- Regex for string parsing
- GroupBy, Merge, and Filtering
- Histograms, Bar Plots, Line Plots, Heatmaps

---

## 🧰 Tech Stack

| Category        | Tools |
|----------------|-------|
| Language        | Python 3.8+ |
| IDE/Notebook    | Jupyter Notebook |
| Libraries       | Pandas, NumPy, Matplotlib, Seaborn, Regex |
| Dataset         | [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/) |
| File Formats    | `.data`, `.item`, `.user`, `.ipynb` |

---

## 📁 Folder Structure

```
.
├── Intro to python- project.ipynb     # Main Jupyter Notebook
├── ml-100k/                           # MovieLens dataset folder
│   ├── u.data
│   ├── u.item
│   └── u.user
├── README.md                          # Project documentation
```

---

## 📷 Example Visuals

> 📈 Genre popularity over years  
> 🧑‍💼 User demographic breakdown  
> 🎥 Top 25 movies by average rating (≥100 reviews)

---

## 📌 References

- [MovieLens Official](https://movielens.org/)
- [GroupLens Research](https://grouplens.org/)

---

## 👤 Author

**Your Name**  
Python Data Enthusiast | Data Science Learner  
📧 [your.email@example.com](mailto:your.email@example.com)  
🔗 [GitHub](https://github.com/yourusername) • [LinkedIn](https://linkedin.com/in/yourusername)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
