# Airline Passenger Review Analysis

An exploratory analysis of 600 airline passenger reviews, focused on how Value for Money relates to overall ratings and recommendation behavior.

## Highlights

- Checked missing values, duplicate records, labels, and rating ranges.
- Compared recommendation and overall ratings across travel classes and airline groups.
- Measured a Pearson correlation of 0.889 between Value for Money and Overall Rating in the analysis sample.
- Compared selected review terms across low and high Value for Money groups.
- Documented sampling limits and avoided causal claims.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Files

- `airline_review_analysis.ipynb`: analysis workflow and interpretation
- `ETM1005_A2_AirlineReviews.csv`: source review dataset with the reviewer-name column removed
- `requirements.txt`: Python packages used by the notebook

## Data

The included CSV contains 8,100 airline reviews. The original `Name` column was removed before publication because it is not used in the analysis. The notebook creates a reproducible 600-review sample using a fixed random seed.
