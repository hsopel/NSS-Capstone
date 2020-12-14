# Wind Energy: Past, Present, and Future
Executive Summary
An analysis of wind turbine installations in the United States since 1980, which will include analyzing how wind turbine height and rated capacity has changed over time using data from the United States Wind Turbine Database. I will also use data of wind speed at various heights above surface level to show heights and areas of the U.S that are ideal for wind turbines. I am using this project to learn more about the energy source that is projected to serve up to 35% of the United State’s end use energy demand by 2050 and to learn more the industry in which my brother works. 

Motivation
My brother has worked as a wind turbine technician for almost three years, but before choosing this topic I didn’t know much about wind turbines and the advances and challenges facing the industry. This past summer my brother showed me his wind turbine work app that displays current wind speed and energy output (among more technical things) for each Vestas turbine. That data, of course, isn’t available to the public, but there are numerous datasets about wind turbine models/installations and energy breakdowns by country/state/county, etc. available online. I didn’t realize how large of a role data analytics plays in every aspect of designing, installing, and maintaining wind turbines. Although wind energy has had a relatively slow and controversial start, wind energy now makes up 6% of the electricity in the United States and that number is projected to increase steadily in the future. I am excited to learn more about the industry that my brother has made his career in and that will become more prevalent in the United States and around the world.
Data Question
How has onshore wind turbine height and rated capacity changed over time? Which manufacturers historically and currently have the largest number of wind turbines installed in the United States?

Article: Shows change in height and capacity from 2006-2016
Article: Wind turbine sizes keep growing as industry consolidation continues

Minimum Viable Product (MVP)
The majority of my analysis will be done in Python and my presentation will be created in Tableau. It will start with a brief overview of how wind turbines work. I would like to create line charts or bar charts to show the change in height and rated capacity over time and a breakdown of number of wind turbines by wind turbine manufacturers over time. I will also use U.S. wind speed data at various heights to show why increasing the height of wind turbines produces more electricity, possible using a map(s) or charts. I’m also interested in creating a time lapse map of the growth of one or a couple specific wind farms showing how wind farm siting regulations have required that wind turbines be spaced farther apart to mitigate risk to wildlife. (Beyond MVP would include showing a comparison over time to other energy sources and how that compares to other countries. Also, there’s a cool data set about current and future U.S. offshore wind turbines…) Generally, my audience is people wanting to learn more about wind energy. The video of the presentation could be used on the American Wind Energy Association’s website’s ‘Wind 101 – History of Wind Turbine’ section. 	
Schedule (through  1/7/2021)
1.	Get the Data (11/25/2020)
2.	Clean & Explore the Data (12/14/2020)
3.	Create Presentation of your Analysis (12/23/2020)
-	Should be a presentation, but could include a Jupyter Notebook or dashboard in Excel, Tableau, or PowerBI
4.	Internal demos (1/4/2021)
5.	Demo Day!! (1/7/2021)

Data Sources
•	US Wind Turbine Database
o	GeoJSON available; could also use the API…
•	US Onshore Turbines Through 2014 – indicates if wind turbine is decommissioned (don’t think I can join with the one above though)
•	NREL: Wind Resource Data – wind speed data (TIF Files)
•	U.S. Energy Information Administration
o	Data for energy sources by country
•	West-Wide Wind Mapping Project (haven’t explored this data yet, but may use to supplement the USWTD)
•	US Offshore Wind Turbines
Known Issues and Challenges
●	There are approximately 5,000 of the 65,000 turbines in the dataset with unknown manufacturers – spanning a variety of years. These will probably have to be excluded from the manufacturer analysis, unless I can find the data from another source
●	One challenge for me will be keeping units of measurements consistent and presenting them in a way that everyone can understand. (meters, megawatts, etc.)
●	The USWTDB includes decommissioned wind turbines so if I decide analyze current megawatt hours produced, would have to figure out a way to determine active. Looking just at installs after 2000 or 2005 could potentially work as well.


Things that I’m interested in that probably won’t be included in the analysis because there isn’t much data available, but including them here will make me feel better:
o	Bat Protection System – using machine learning to detect bat migration and slow down wind turbines individually instead of using blanket curtailment on a whole wind farm to help mitigate the risk of bat collisions and results in less energy loss.
o	Lightening and fire protection systems in wind turbines – lightening strikes can damage turbines and lead to problems down the road. Broken wind turbine blade is probably the only time my brother will make the news. (Fun Fact: Fewer lightening strikes occurring in the world this year…potentially due to changed human behavior because of COVID. And AI is also being used to predict lightening strikes?!).
Approximately 1 in 2,000 turbines will experience a fire. Not much data compiled on this subject since it’s bad for PR.
o	AI BladeBUGs to inspect wind turbine blades are being developed so humans don’t have to take on the risk to do so!
