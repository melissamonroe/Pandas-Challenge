# Exploring Pandas

## Heroes of Pymoli

![Fantasy](Images/Fantasy.png)

You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

The [Final Analysis Report](Analysis/Final_Analysis_Report.md) includes each of the following:

### Player Count

- Total Number of Players

### Purchasing Analysis (Total)

- Number of Unique Items
- Average Purchase Price
- Total Number of Purchases
- Total Revenue

### Gender Demographics

- Percentage and Count of Male Players
- Percentage and Count of Female Players
- Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

- The below each broken by gender
  - Purchase Count
  - Average Purchase Price
  - Total Purchase Value
  - Average Purchase Total per Person by Gender

### Age Demographics

- The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  - Numbers and percentages by age group

### Purchasing Analysis (Age)

- The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  - Purchase Count
  - Average Purchase Price
  - Total Purchase Value
  - Average Purchase Total per Person by Age Group

### Top Spenders

- Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  - SN
  - Purchase Count
  - Average Purchase Price
  - Total Purchase Value

### Most Popular Items

- Identify the 5 most popular items by purchase count, then list (in a table):
  - Item ID
  - Item Name
  - Purchase Count
  - Item Price
  - Total Purchase Value

### Most Profitable Items

- Identify the 5 most profitable items by total purchase value, then list (in a table):
  - Item ID
  - Item Name
  - Purchase Count
  - Item Price
  - Total Purchase Value

### Notes

- Pandas Library and the Jupyter Notebook were utilized to analyze this data
- Link to Github repo https://github.com/melissamonroe/Pandas-Challenge
- Jupyter Notebook: HeroesOfPymoli.ipynb

## Observable trends based on the data

- Majority of players are male 84% (484 of 576 players)

- The largest age demographic group (44.79%) are players between 20-24 years old (258 of 576 players)

- Top spenders purchased at least 3 items

- Final Critic was the highest grossing purchase item and the most profitable with 13 total purchases and total purchase value of $59.99
