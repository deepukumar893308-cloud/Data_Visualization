# &#x20;— Task 3: Data Visualization

## Objective

Transform raw e-commerce data into understandable visual formats, use Matplotlib/Seaborn, communicate insights clearly, and support decision-making with a concise data story.

## Dataset

* File: `Ecommerce\_Dataset\_3000.csv`
* Sample size: 3,000 rows and 24 columns.
* Results apply to this sample only, not necessarily the full dataset.

## Visualizations

1. Product-category record counts.
2. Order-status distribution and cancellation share.
3. Order-amount histogram and box plot for distribution/outlier review.
4. Fulfilment method distribution.
5. Shipping service-level distribution.
6. Top 10 shipping states.
7. Mean and median order amount by product category.
8. Order amount by shipping service level using a box plot.
9. Optional Welch t-test for Expedited vs Standard amount comparison.

Each notebook section includes an insight and/or business interpretation.

## How to run

1. Keep the notebook and CSV in the same folder.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `CodeAlpha\_Task3\_Data\_Visualization.ipynb` in Jupyter Notebook.
4. Select **Run → Run All Cells**.

## Notes

Missing amounts are excluded from amount charts. Potential outliers are flags for review, not automatically deleted. The sample is limited to 3,000 records and visual association does not establish causation.

