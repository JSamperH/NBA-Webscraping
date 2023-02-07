# NBA-Webscraping Project

This project was done in collaboration with Yacine Ouldchikh and Justin Louie. The code used is shown in 20220816_NBAWebscrapingProject_FinalNotebook.ipynb, and NBA Webscraping Project.pdf is a short presentation of the project. <br> 
The objective was to have a go at webscraping, using libraries such as BeautifulSoup and Selenium, but in addition to that we also did some data analysis, as shown in the final project structure below:
<br>

### Project Structure
1. Data webscraping and filtering
2. Search for the best players
3. Search for most improved players
4. Search for over- and undervalued players
5. Building an optimized starting lineup

### 1. Data webscraping and filtering
The main data was scraped from the official NBA stats website. <br>
Two seasons (2020-21 and 2021-22) worth of player stats were taken.<br>
Player salaries were also scraped, in this case from the HoopsHype website, and all of the data was joint into one master dataframe and cleaned for its analysis.

### 2. Search for best players
In order to find the most valuable players in the league, a series of KPIs were designed by position, using the most relevant stats and calculating a weighted average.<br>
This was done over the stats' percentile scores in order for them to be comparable.<br>
A series of visualizations were made, including some scatter plots that show the best players on different aspects of the game.<br>
After that, the top 3 players by position (according to the custom KPIs) were displayed using radar charts.

### 3. Search for most improved players
Using the custom KPIs, we found the highest rate of change by position, between the 2020-21 and 2021-22 seasons.<br>
Once again, radar charts were used to visualize the player's stats. In this case, to compare the different seasons performance from each player and have a visual of the evolution that the KPI's ROC suggested.

### 4. Search for over- and undervalued players
For this section, the custom performance KPI percentiles were compared to the salry percentiles. <br>
To have a quick visual representation of the results, a scatter plot was shown.<br>
Using a simple difference between KPI and Salary percentiles, the most over and undervalued players were ranked.

### 5. Building an optimized starting lineup
Lastly, an optimized lineup was built. To do that, a budget of $95Mn was given, after finding out that the average starting lineup salaries for the last two seasons in the NBA were $89Mn and $92Mn, respectively.<br>
After that, the most valuable players according to the custom-made KPIs were compared and their salaries were taken into account to hand-pick a lineup that would work for the given budget.<br>
This step could have been done with a more elaborated algorithm to try and oprtimize the cost/performance, but it exceeded the objectives of the project, so it can be left as a future next step to the process.

