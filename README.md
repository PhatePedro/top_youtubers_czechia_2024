# Repository of the Czech Top YouTubers (2024)
This workflow outlines the process of downloading, processing, analyzing and visualizing data from YouTube channels using Python, SQL and Power BI. 
By leveraging the YouTube API, Pandas for data manipulation, SQL for data cleaning and organization, and Power BI for analyse and visualization, you can effectively manage and analyze YouTube channel data.

Overview:

1. Data source:
  Download the CSV file (source_czech_rep_youtube.csv) containing information about various Czech YouTube channels.

2. Data update with Pandas (Python):
  Retrieve YouTube channel statistics (number of subscribers, views, and videos) for each YouTube channel and save them in a new CSV file (updated_czech_rep_youtube.csv).
   
4. SQL Data Cleaning:
  Import the updated data into Microsoft SQL Server for further cleaning and standardization. Create a view for easier access to the necessary columns. Export the final file as 'final_czech_rep_youtube.csv'.

5. Create Power BI dashboard:
  Use the cleaned data (you can either access the pre-created view directly from Power BI or import the final file 'final_czech_rep_youtube.csv') to create visualizations and dashboards in Power BI for further analysis.

Note: You can view an image of the dashboard (Top YouTubers CZ 2024-Dashboard Image Overview.png) or download the Power BI file with the original dashboard (TopYoutubersCZ2024.pbix).
