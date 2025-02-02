# Top200-SpotifyDailyMusicStreams-Web Scraping Project

This project involves scraping, cleaning, and analyzing data from the Spotify Global Daily Charts website (https://kworb.net/spotify/country/global_daily.html). The goal is to extract song performance metrics, clean and process the data, and visualize insights using Python and Excel.

Table of Contents
Project Overview
Technologies Used
Setup and Installation
Project Workflow
Data Cleaning and Processing
Data Visualization
Contributing
License

Project Overview
This project scrapes daily Spotify chart data from the global top 200 songs, including metrics like:

Song Title
Artist
Streams
Position
Change in Position

The scraped data is cleaned, processed, and analyzed to uncover trends and insights about song performance on Spotify. The final output is visualized in Excel for easy interpretation.

Technologies Used
Python Libraries:
BeautifulSoup (Web Scraping)
Pandas (Data Manipulation and Cleaning)
NumPy (Numerical Operations)
Requests (HTTP Requests)

Data Visualization:
Microsoft Excel (Charts and Graphs)

Version Control:
Git and GitHub



Setup and Installation
Clone the Repository: bash Copy  git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name 
Install Required Libraries: bash Copy  pip install beautifulsoup4 pandas numpy requests 
Run the Script: bash Copy  python scrape_spotify_charts.py 
Open the Output File:
The cleaned data will be saved as spotify_charts_cleaned.csv.
Use Excel to open and visualize the data.

Project Workflow
Web Scraping:
Use BeautifulSoup to scrape the Spotify Global Daily Charts website.
Extract relevant data (song title, artist, streams, position, etc.) and store it in a structured format.
Data Cleaning:
Handle missing or inconsistent data using Pandas.
Convert data types (e.g., streams to integers) and remove unnecessary columns.
Data Analysis:
Use Pandas and NumPy to calculate metrics like:
Top 10 songs by streams.
Biggest position changes (up/down).
Average streams per artist.
Data Visualization:
Export the cleaned data to Excel.
Create charts and graphs to visualize trends (e.g., top songs, artist performance).

Data Cleaning and Processing
Handling Missing Data: Rows with missing values are either filled or dropped.
Data Type Conversion: Streams and positions are converted to integers for analysis.
Filtering: Only relevant columns are retained for analysis.

Data Visualization
Excel Charts:
Bar charts for top 10 songs by streams.
Line graphs for position changes over time.
Pie charts for artist market share.

License
This project is licensed under the MIT License. See the LICENSE file for details.
