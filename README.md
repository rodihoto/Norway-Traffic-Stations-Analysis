# Norway-Traffic-Stations-Analysis
Project Description:
The purpose of this analysis is to explore and visualize traffic station data from Statens Vegvesen (Norwegian Public Roads Administration). The dataset includes traffic station locations, opening hours, and contact information. Using Python, the project cleans and preprocesses the data, clusters traffic stations by geographic location, and visualizes the distribution across Norway. This analysis aims to provide insights into the spatial distribution of traffic stations, helping identify regional groupings and road coverage.

Installation Instructions
To run this project, ensure you have Python installed. You can then set up the required environment by installing the dependencies listed below.

Dependencies
Python 3.7+
pandas: Data manipulation and analysis
matplotlib: Data visualization
seaborn: Statistical data visualization
plotly: Interactive maps and plots
scikit-learn: Machine learning (for clustering)
geopandas: Geospatial data manipulation (optional, for extended mapping)

Usage
This project contains scripts for data cleaning, clustering, and visualization.

Scripts and Commands
Data Cleaning: Cleans the dataset, removes missing values, and extracts latitude and longitude from the GEOMETRI field.

Clustering: Groups traffic stations into regions based on latitude and longitude using KMeans clustering.


Visualization: Generates bar charts, pie charts, and interactive maps to visualize the distribution of traffic stations by region and category.



Results
The analysis yields several insights:

Distribution by County: A bar chart showing the count of traffic stations by county.
Road Category Breakdown: A pie chart displaying the distribution of stations across different road categories.
Geographical Clustering: An interactive map visualizing traffic stations across Norway, clustered into regional groups.
