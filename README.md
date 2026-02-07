📊 Task 1: Media Engagement vs Media Views Analysis
📌 Description

This task analyzes the relationship between media views and media engagements for tweets using a scatter chart in Power BI. The visualization helps identify how media exposure impacts user interaction and highlights high-performing tweets based on engagement criteria.

🔧 Visualization Details

Chart Type: Scatter Chart

X-axis: Media Views

Y-axis: Media Engagements

Legend: High Engagement Indicator (tweets with engagement rate above 5%)

📋 Filters & Business Rules Applied

Included only tweets with more than 10 replies

Highlighted tweets with an engagement rate greater than 5%

Filtered tweets to include only those:

Posted on odd-numbered dates

Having a word count greater than 50

The visualization is dynamically displayed only between 6:00 PM and 11:00 PM IST

Outside this time window, the chart is automatically hidden from the dashboard using a DAX-based control measure

📈 Key Insights

Tweets with higher media views generally tend to receive higher engagement

High-engagement tweets are clearly distinguishable and cluster in specific regions of the chart

Time-based visibility improves dashboard relevance and reduces clutter
