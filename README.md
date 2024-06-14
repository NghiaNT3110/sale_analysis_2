# Project Case no 2: Sale Analysis

- Data source: datadad.io

- Transformed Dataset Link (After transform): [Dataset Link](https://docs.google.com/spreadsheets/d/1aNPMBCc8HfnI0tA7yR0WR3jT2vYIoLhch4J_iWvUiZA/edit#gid=1956311044)

- Dashboard Link: [Looker Studio Dashboard Link](https://lookerstudio.google.com/u/0/reporting/7126c72d-bc91-4c1e-a7ec-739a99b8d745/page/U3qoD) 

===

- Data Cleaning Process:

1 - Define data fileds and context from the dataset 

2 - Format date data & business data to the correct format (B column formatted to YYYY-MM-DD + L & M Columns formatted to $ US Dollar).

3 - Add new calculation fields for Revenue (Revenue = Unit Price * Quantity), Cost (Cost = Unit Cost * Quantity), Profit (Profit = Revenue - Cost), and format them in $ US Dollar currency.

4 - Add new calculation fields for AOV (AOV = Revenue / Quantity) and Profit Margin (Profit Margin = Profit / Revenue * 100%), formatted in $ US Dollar. 

5 - Round only 2 decimal places for the columns related to revenue, cost, and profit.
