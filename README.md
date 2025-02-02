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
  Jupyter Notebook

Project Workflow
 Web Scraping:
  Use BeautifulSoup to scrape the Spotify Global Daily Charts on provided website.
  Extract relevant data (song title, artist, streams, position, etc.) and store it in a structured format.
 
 Data Cleaning and Processing:
  Handle missing or inconsistent data using Pandas. 
  Rows with missing values are either filled
  Convert data types (e.g., streams to integers) and remove unnecessary columns.
  Export the semi-cleaned data to Excel for further cleaning.

 Data Analysis:
  Use Excel to calculate metrics like:
   Top 10 songs by streams.
   Top 5 most and least recurring artist.
   Bottom 5 songs by streams.
   Artist most featured on songs.
   Biggest position changes (up/down). 
   Average streams per artist.
   
Data Visualization:
  Create charts and graphs to visualize trends.
  Excel Charts:
   Bar charts for top 10 songs by streams.
   Line graphs for position changes over time.
   Pie charts for artist market share.

License
See the LICENSE file for details.
