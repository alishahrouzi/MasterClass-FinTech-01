# Assignment

## **1. California cities (Water area leaders)**

**Folder:** `session_1/2.california_cities/`

Find the 5 California cities with the largest water area.

Your notebook should:

- Load and inspect `california_cities.csv`.
- Check the data types and missing values in the water-area columns.
- Rank the cities by `area_water_km2` and display the top five.
- Create a clearly labeled horizontal bar chart of the 5 cities and their water areas.

## 2. Billionaires (Other **industries**)

**Folder:** `session_1/3.billionaires/`

In section **6 · Compare industries**, show the 10 most common industries separately and group all industries from the 11th position onward into **Other.**

**💡Hint**

Follow the approach used in **Lionel Messi: Goals analysis**
in file `session_1/4.lionel_messi/lionel_messi_goals_analysis.ipynb`
in section **6 · How were the goals scored?**

Your notebook should:

- Load and inspect `Billionaire.csv`.
- Count the number of billionaires in each industry and sort the results from largest to smallest.
- Keep the first 10 industries as separate categories.
- Add an `Other` category containing the combined count of all remaining industries.
- Display the final result in a clearly labeled pie chart.

## **3. Online retail (Monthly Retention Rate)**

**Folder:** `session_1/5.online_retail/`

Calculate how many UK customers returned in each month after purchasing in the previous month. Then visualize the monthly retention rate. Compute the retention rate using:

$$
Monthly Retention Rate = Retained Customers from Previous Month / Total Active Customers
$$

**💡Hint**

[Know Your Metrics](https://medium.com/data-science/data-driven-growth-with-python-part-1-know-your-metrics-812781e66a5b)

Your notebook should:

- Use the prepared UK customer-purchase data and inspect the relevant columns.
- Create a customer-by-month activity table with `pd.crosstab()`.
- Calculate the total active customers for each month.
- Calculate the customers who were active both in the current month and in the previous month.
- Store the results in a DataFrame with the month, total customers, retained customers, and retention rate.
- Create a clearly labeled line chart of the monthly retention rate. Exclude December 2011 from the final comparison because the dataset is incomplete for that month.

## **Submission checklist**

Before submitting, make sure that:

- [ ]  Each assignment is completed in its matching notebook.
- [ ]  Every chart has a title, axis labels, and readable category labels.
- [ ]  Calculations are visible in code and results are explained in Markdown.
- [ ]  Missing values and unusual records are checked where relevant.
- [ ]  The original datasets remain unchanged.
