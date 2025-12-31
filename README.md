# Airbnb San Francisco Market Analysis (Python EDA)

An end-to-end Python analysis of **Airbnb listings in San Francisco** using a 2025 dataset.  
The project focuses on **data cleaning, feature engineering, exploratory analysis, and insight generation** around pricing, neighborhoods, host behavior, and amenities.

## Purpose

This project was built to:
- Clean and prepare a large, messy real-world dataset
- Identify key drivers of Airbnb pricing in San Francisco
- Compare listing performance across neighborhoods, room types, and hosts
- Translate exploratory analysis into clear, business-relevant insights

## Key Questions Answered

- How are Airbnb prices distributed across San Francisco?
- Which room types and neighborhoods command higher prices?
- Do superhosts charge more or receive better ratings?
- How do amenities and host experience influence pricing?
- Are higher ratings associated with higher prices?

## Analysis Highlights

- Price distribution analysis across thousands of listings
- Pricing comparisons by room type (entire home, private room, shared space)
- Neighborhood-level price differences among the most active areas
- Superhost vs non-superhost behavior and pricing
- Relationship between amenities, host tenure, ratings, and price

## Key Insights

- Prices are highly skewed: most listings are under **$300**, with a small luxury segment driving the upper tail.
- **Room type** is a major price driver; entire homes and apartments command the highest rates.
- Neighborhoods vary significantly; Western Addition, Bernal Heights, Cole Valley, and Alamo Square show higher median prices.
- Superhosts charge slightly more, but ratings are similar to non-superhosts.
- Ratings cluster tightly between **4.5–5.0**, limiting their usefulness as a price differentiator.
- Listings with more amenities generally command higher prices, especially within the same room type.
- Host tenure aligns more with optimized pricing than with higher ratings.

## Tools & Skills Used

- Python
- pandas (data cleaning and transformation)
- NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Data wrangling, feature engineering, EDA, and insights storytelling

## Files Included

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

## Data Source
- [Inside Airbnb – San Francisco (2025)](https://insideairbnb.com/get-the-data/)

## Author

**Mohammed Zareef-Mustafa**

## License

This project is licensed under the **MIT License**. See the [LICENSE.txt](LICENSE.txt) file for details.
