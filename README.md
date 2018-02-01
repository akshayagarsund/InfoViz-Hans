# InfoViz-Hans
Have recreated the GapMinder World visualisation using d3.js 
•	Bubble chart representing countries of the world where
o	Countries of the world are described by GDP and Life Expectancy on X and Y axis respectively
o	The population of each country mapped to bubble area
•	Appropriate labels and axis
•	Appropriate use of color where we have used harmonious color combination from the ColorWheel, which seem to be more pleasing to the eyes.
•	Country name labels- Since the visualisation looked clumsy when the labels were displayed we are displaying the country when the mouse is hovered on a particular bubble.  
•	Ability to view data for a particular year- When we shift the slider to a particular position and play, the corresponding data from that particular year can be viewed
•	Ability to animate the change in country statistics from year to year(1900-2016) using play button.
The data required to drive this visualisation was found in Gap_Minder_All_Time.csv filw which includes the following fields:
• Country: The country name
• Year: The year for this data observation
• Population: The population of the country in this year
• LifeExp: Average life expectancy in years
• GDP: Average GDP in inflation adjusted dollars
• Code: The country code
• Region : The region in which the country belongs (similar to continent)
• Area: The area of the country in square kilometres
• Coastline: the number of kilometres of coastline belonging to the country
• Government: The type of government in the country


