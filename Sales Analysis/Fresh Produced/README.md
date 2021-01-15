# Sales-Analysis

Workflow:
===========
1. To find the average sales recorded in every month for a given year.
display(df.groupby(["year", "Month"])["Sales"].mean().to_frame())

2. To find which region sold the item the most.
results_region = df.groupby("region").sum()

3. To compare the average price of each type of item using boxplot.

4. To find the highest sales recorded for each type of item.
display(df.groupby("type")["Sales"].mean().to_frame())

5. To analyze the effect of fluctuating average price of an item to the sales recorded in every month for a given year.
![pict](/image/sales.png)

6. To find which size of items sold the most.

Reference
=========
**Dataset:** https://www.kaggle.com/neuromusic/avocado-prices

