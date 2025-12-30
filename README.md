# 🏡 Airbnb San Francisco Analysis (Python Data Cleaning + EDA Project)

An end-to-end Python project analyzing Airbnb listings in San Francisco (2025 scrape).
Includes data cleaning, feature engineering, exploratory data analysis, statistical summaries, visualizations, and a written insights report.

## 🚀 What This Project Shows

- Real-world data cleaning with pandas
- Handling missing values, mixed data types, and messy fields
- Feature engineering (amenities count, price per person, host tenure, rating % score)
- Exploratory data analysis using plots and grouped statistics
- Insight generation across pricing, neighborhoods, hosts, reviews, and amenities
- Professional notebook structure and storytelling through data

---

## 📊 Analysis Highlights

This project explores:
- Price Distribution across thousands of San Francisco listings
- Room Type Pricing (Entire home vs Private room vs Shared spaces)
- Neighborhood Differences using the top 10 areas by listing volume
- Ratings & Review Trends and their relationship to price
- Superhost Behavior and how it compares to non-superhosts
- Host Tenure and its influence on listing performance
- Amenities & Value (Do more amenities → higher pricing?)
Visualizations include:
- Histograms (price, ratings)
- Boxplots (room type, neighborhood, superhost status)
- Scatterplots (rating vs price, amenities vs price, host tenure vs price)
- Zoomed-in scatterplots for better visibility of heavy-tailed price data

---

## 🛠 Tools & Skills Used

- Python
- pandas for data cleaning & transformation
- NumPy for numeric handling
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook for reproducible analysis
- Data wrangling, feature engineering, exploratory analysis, and insights storytelling

---

## 📂 Files Included

```text
data/
│
├── clean/
│   └── listings_clean.csv            <-- cleaned dataset
│
└── raw/
    └── listings.csv                  <-- raw data preserved

notebooks/
├── 01_data_cleaning.ipynb            <-- cleaning workflow
└── 02_eda.ipynb                      <-- analysis, plots, insights

.gitignore                             <-- should exclude venv, __pycache__, etc.

README.md                              <-- main project documentation
```


---

## 🧠 Key Insights (Quick Summary)

- Prices are highly skewed, with most listings under $300 and a smaller luxury segment driving the upper tail.
- Room type is a major price driver: entire homes/apartments command the highest rates.
- Neighborhoods vary significantly: Western Addition, Bernal Heights, Cole Valley, and Alamo Square show higher median prices.
- Superhosts charge slightly more, but ratings between superhosts and non-superhosts remain similar.
- Ratings are tightly clustered between 4.5 and 5.0, showing limited price differentiation.
- More amenities generally correlate with higher pricing, especially within each room type category.
- Host experience (tenure) does not guarantee higher ratings but tends to align with more optimized pricing.
(Full insights available in 02_eda.ipynb.)

---

## 📦 Data Source
- [Inside Airbnb – San Francisco (2025)](https://insideairbnb.com/get-the-data/)

---

## 👤 Author

**Mohammed Zareef-Mustafa**

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE.txt](LICENSE.txt) file for details.
