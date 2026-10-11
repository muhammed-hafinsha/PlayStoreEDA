# PlayStoreEDA


## Overview
An exploratory data analysis project examining Google Play Store app listings to understand category distribution, ratings, install counts, reviews, pricing, and differences between Free and Paid apps.

## Objectives
- Identify the most common app categories.
- Explore app rating distributions.
- Compare Free and Paid apps.
- Investigate install counts across categories.
- Examine the relationship between reviews and ratings.
- Analyze paid app pricing and numerical feature relationships.

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Analysis Performed
- Data cleaning and missing-value handling
- Feature preparation for installs, reviews, prices, and app sizes
- Univariate analysis using histograms, bar charts, pie charts, and boxplots
- Bivariate analysis of ratings, reviews, installs, and app categories
- Comparison of rating distributions for Free and Paid apps
- Paid app price distribution analysis
- Multivariate Spearman correlation analysis using a heatmap

## Key Insights
- Category counts reveal which app categories have the most listings.
- Median installs provide a comparison of typical install levels across categories.
- Free and Paid app distributions help describe the pricing structure of the dataset.
- Ratings and review counts can be examined for possible monotonic relationships.
- Reviews and installs show a very strong positive correlation (0.97) in the analyzed data.
- Price has a weak negative correlation with installs (-0.23), while ratings have very weak correlations with most numerical variables.

## Repository Contents
- `Google_Play_Store_Analysis(1).ipynb` — data cleaning, analysis, visualizations, and findings.
- `README.md` — project documentation.
- Dataset file — add the dataset separately if redistribution is permitted.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scipy jupyter`
3. Open the notebook in Jupyter Notebook or VS Code.
4. Place the Google Play Store dataset in the expected location or update the file path.
5. Run the notebook cells in order.

## Conclusion
This project demonstrates how exploratory data analysis can reveal app-market patterns involving categories, ratings, install counts, reviews, and pricing.
