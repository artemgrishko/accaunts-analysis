# Social Media Data Analysis

This project aims to analyze data from social media accounts, posts, and followers. It involves data merging, missing values analysis, data type inspection, statistical summary generation, and date range determination for posts. The results are visualized using bar charts and descriptive statistics.

## Installing using GitHub

```shell
git clone https://github.com/artemgrishko/accaunts-analysis.git
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txе

Then you should run jupiter
```

## The project uses three datasets:

<ul>
  <li>accounts.csv: Contains information about social media accounts.</li>
  <li>posts.csv: Contains information about posts made by the accounts.</li>
  <li>sources_for_followers.csv: Contains information about the sources of followers.</li>
</ul>

## Data Analysis Steps

1. **Data Import and Merging**
   - Import the datasets using pandas.
   - Merge the datasets to create a comprehensive DataFrame containing information from all three sources.

2. **Missing Values Analysis**
   - Calculate the number of missing values for each column.
   - Visualize the missing values using a bar chart.

3. **Data Type Inspection**
   - Inspect the data types of each column in the merged DataFrame.

4. **Statistical Summary**
   - Generate a statistical summary for numerical columns in the merged DataFrame.

5. **Date Range Determination**
   - Determine the earliest and latest dates in the `created_time` column.
