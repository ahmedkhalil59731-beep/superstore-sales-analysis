# 🎬 Netflix Dataset — Exploratory Data Analysis


> An exploratory data analysis (EDA) project on Netflix's content library — uncovering trends in content type, release year, country distribution, ratings, and top directors.

---

## 📌 Table of Contents

- Overview
- Dataset
- Objectives
- Tech Stack
- Project Structure
- Key Insights
- Getting Started
- Results

---

## 📖 Overview

With the rapid growth of streaming platforms, understanding how content is distributed across genres, countries, and time periods has become increasingly valuable. This project performs a full EDA on Netflix's catalog dataset to extract meaningful patterns and deliver data-driven insights.

---

## 📦 Dataset

| Property | Value |
|----------|-------|
| Source | Kaggle — Netflix Movies and TV Shows |
| Rows | 8,807 |
| Columns | 12 |
| File | `netflix1.csv` |

**Columns include:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🎯 Objectives

- ✅ Perform data cleaning and preprocessing
- ✅ Handle missing values and fix data types
- ✅ Explore the dataset using descriptive statistics
- ✅ Visualize key trends and patterns
- ✅ Compare Movies vs. TV Shows distribution
- ✅ Identify top countries, directors, and rating categories

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data manipulation & cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| Jupyter Notebook | Interactive development |

---

## 📁 Project Structure

```
netflix-eda/
│
├── Netflix.ipynb        # Main analysis notebook
├── netflix1.csv         # Dataset (download from Kaggle)
└── README.md            # Project documentation
```

---

## 💡 Key Insights

- 📺 The dataset contains significantly more **Movies** than **TV Shows**
- 🌍 The **United States** leads in content production by a wide margin
- 🎬 A handful of directors appear repeatedly, dominating Netflix's catalog
- ⭐ **TV-MA** and **TV-14** are the most common content ratings
- 📅 Content additions peaked in recent years, showing platform growth

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Notebook

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/netflix-eda.git
   cd netflix-eda
   ```

2. **Download the dataset** from Kaggle and place `netflix1.csv` in the project root.

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Netflix.ipynb
   ```

---

## 📊 Results

| Analysis | Description |
|----------|-------------|
| Content Type | Movies vs. TV Shows comparison |
| Top Countries | Bar chart of top 10 content-producing countries |
| Ratings Distribution | Distribution of content ratings (TV-MA, PG, etc.) |
| Top Directors | Most frequent directors on the platform |

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open source and available under the MIT License.

---

<p align="center">Made with ❤️ using Python & Jupyter</p>
