# California Music Festival Analysis
## Authors:
Brent Young and Sam Hubler

## Project Description
As fans of music in the Bay Area, our goal is to create a platform that can visualize patterns in trends between venues, artists and genres. We will take music venue data including events, setlists, and attendance data to analyze patterns among human-music interaction. We will also analyze music genre data in order to visualize music trends across California, comparing both the Northern and Southern California music scene. By hosting an interactive website, users will be able to see this analysis in real time and visualize trend they find interesting. 

## Project Outline
### Interface Plan
- Website that shows trends in EDM set lists and venues across California, comparing northern and southern California
- Interactive sliders showing trends over time
- Genre selection allowing users to focus on one subset of the music scene
- Search mechanism to focus on individual artists or genres
### Data Collection and Storage Plan (Sam Hubler)
- Data Upload through API
- Data completeness analysis
- Data formatting through Pandas Python package
- Add useful data to MySQL relational database for easy accession
- Uploading to web-hosted MySQL database for access for website
- Create pathways for data access in website hosting platform
### Data Analysis and Visualization Plan (Brent Young)
- Clean and merge event, artist, and venue data using Pandas
- Compare Northern vs. Southern California by number of events, top artists, and genre mix
- Track artist popularity and booking frequency over time to identify rising artists
- Interactive map of events and venues across California using Plotly
- Bar charts ranking the most active venues and most-booked artists in each region
- Line charts showing event and genre trends over time
- Network graph of artists who frequently appear on the same lineups
