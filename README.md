# Analyzing-Netflix-Content-Trends
# Data-Visualization MSDS 670
## Project Overview
The Week 8 Project showcases data taken from Netflix’s public domains between the years 2008 and 2022. Netflix could use this data on multiple points; to determine success of content released, where categories of content are most popular, and where Netflix focuses on their content releases. The research questions to this end are: is Netflix releasing more content in some countries then others? Does Netflix focus on releasing movies or TV shows? Has there been a year between 2008 and 2022 where Netflix has released more content? 

## Data
#### Source: 
The data was sourced from Netflix’s public domains and outlying websites that collect the applicable contents. The author of the csv file used was Shivam Bansal, and is linked in the reference section. The data is updated every thirty days. •	https://www.kaggle.com/shivamb/netflix-shows
#### Scope: 
 The records involved in the netflix_titles.csv hold over 8,000 records of Netflix content. 
## Process
This process was completed on a Windows 10 system, with  Python 3.9.0, Jupyter Notebook and Spyder IDE. 
#### 1.	Retrieving, cleaning and organizing the data. 
This involved downloading the data from the link provided and importing it into Spyder IDE for cleaning and testing with matplotlib. Columns with irrelevant data were dropped and N/A values were dropped. Data before the year 2008 was filtered out to increase the focal point of analysis trends for Netflix's content releases. Categories of data were placed into specific dataframes for analysis; for example "directors" were value counted and placed under the dataframe "directors". Dates were also formatted into a pandas dataframe for easier analysis. The following dataframes were used to group data. 
- Director - directors involved in content creation with Netflix
- Category - content categories used for Netflix content 
- Country - the parts of the world where Netflix released content 
- Year_r - the year that content was released 
- Rating - the rating given to Netflix content upon release

#### 2.	Completing basic analysis of the data with the package matplotlib.
Comparisons plotted involved visual analysis of the top thirteen countries where Netflix had released content, the timeline of Netflix content releases between 2008 and 2022, and where Netflix focused its content creation with regard to the category the content was placed in, the rating it was given upon release, and whether the content was a movie or television show. 

## Visualizations (these descriptions will be edited in next week when presentations are finalized)
- Figure 1; The Top 13 Countries where Netflix released Content 
- Figure 2; Netflix Content Releases from 2008 to 2022 
- Figure 3; Netflix's Most Productive Years
- Figure 4; Type of Netflix Content Released from 2008 to 2022 
- Figure 5; Netflix Content Ratings
- Figure 6; The Thirty Most Popular Categories of Netflix Content



