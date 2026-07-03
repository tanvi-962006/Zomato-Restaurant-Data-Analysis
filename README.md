# Zomato Restaurant Data Analysis

I picked up this Zomato dataset from Kaggle and wanted to dig into what's actually going on with restaurant listings across different cities in India. Things like which cuisines dominate, how prices vary, and whether dining ratings actually line up with delivery ratings.

## What I Did

Started with the raw dataset which had around 1.2 lakh rows. It was pretty messy, had extra spaces in city names, missing values in the bestseller column, duplicate entries, and some crazy outlier prices that didn't make sense.

So I cleaned it up first. Fixed the column names, stripped out whitespace issues, filled in missing values where it made sense, dropped duplicates, and used IQR to filter out the price outliers. After all that, the data was in a much better shape to actually analyze.

Then I built out a bunch of visualizations to see what patterns show up. Made bar charts for top cities and cuisines, a histogram for price distribution, scatter plot comparing dining vs delivery ratings, and a heatmap to check correlations between different numeric columns.

## Tools Used

Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Some Things I Found

The dataset is heavily dominated by a few cities and a handful of cuisines. Most items fall in a pretty affordable price range, and there's a decent positive correlation between dining and delivery ratings which kind of makes sense. Only a small percentage of items actually get tagged as bestsellers.

## Dataset

Zomato Restaurant Dataset from Kaggle

## How to Run

Just open the notebook in Jupyter and run all cells. Make sure you have pandas, matplotlib, and seaborn installed.
