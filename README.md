# hacker-news-post-analysis

📰** Hacker News Post Analysis System**
A data analysis project that explores engagement patterns on Hacker News to uncover the best times and days to post, and to compare engagement across different post types.

📌 **Overview**

This project performs end-to-end data cleaning and exploratory analysis on a Hacker News dataset using Python. It identifies which post types drive the most community engagement, determines the optimal posting hours and days, and visualizes key trends through a series of informative charts.

🔍** Key Findings**

Ask HN posts consistently receive more comments than Show HN posts
The best hours to post Ask HN questions are: 2 AM, 3 PM, 4 PM, 8 PM, and 9 PM
Sunday yields the highest average comment engagement for Ask HN posts
A heatmap analysis reveals the correlation between upvotes (points) and comments across posting hours

🛠️ **Tech Stack**

Python --> Core programming language

Pandas --> Data loading, cleaning, and transformation

Matplotlib --> Base plotting and chart rendering

Seaborn --> Statistical visualizations

Datetime --> Timestamp parsing and time-based analysis

📊 **Visualizations Included**

Pie Chart — Distribution of post types (Ask HN, Show HN, Other)

Bar Chart — Average comments: Ask HN vs Show HN

Bar Chart — Average Ask HN comments by hour of day

Line Chart — Engagement trend across all hours of the day

Line Chart — Top 5 best hours to post Ask HN

Heatmap — Correlation between comments, points, and posting hour

Bar Chart — Average Ask HN comments by day of the week

🗂️ **Project Structure**

hacker-news-analysis/

├── hacker_news.ipynb       # Main Jupyter Notebook

├── hacker_news.csv         # Raw dataset (input)

└── Hacker.csv              # Cleaned dataset (output)

