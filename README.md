# Final-Project-Tableau

## Project/Goals
### The goal of this project is to find the correlation between the altidude, number of strikes, total cost of damages, and species that were most affected. My hypothesis on the given files are that the hight correlates with the amount of strikes, specifically around the take-off and landing area. Most of the colisions would occur during landing, while the plane is descending. For the season, I suggest during peak travelling time, which is the summer period of the year. Winter should have the least amount, due to low travelling demands, and weather conditions. Also, states that have high tourism and a high population should experience the most strikes and costs for fixing demages. My assumption would be that Los Angeles would have the most amount of strikes and costs of fixing damaged planes.

## Process
### Select an option and file that was chosen for this project.
### Perform EDA: Data starts in the year 2000 and ends in May, 2015. Coordinates was off, this was meant for US but when I tried pulling maps, there was no results. Found out the setting was in Canada, once I placed it back to United States, my results showed up. Also, the date setting was in string format, placed it into a date format.
### Create your questions and how you will answer them.
### Find the correlation between the columns
### List the challenges within the project.
### Lastly, describe your future goals.

## Results

### Option 2, FAA WildLife Strikes was selected for this project.

### Which season did accidents occur most frequently? Used a bar graph to show the correlation between the months and amount of strikes. The results show that the months of July, August, September had the highest amount of strikes.

### What caused the huge surge of accidents after 2009? Used a bar graph which gave me insights on the amount of planes running after 2009. The engine amount increased after 2008, might be due to the travel demand after the 2008 recession. This shows that the demand for travelling increased thus causing more strikes after 2009. More commercial planes increases the strikes in total.

### Are the number of strikes correlated with the altitude? A line graph was used to show the correlation between dates/altitude/strikes, and a forecast was also used to adjust for the outliar year 2015 to prevent distorted drops. 2015 only had half of the year in results, specifically, up to May. As for the graphs, it does show a correlation, both line graphs show a similar direction they follow, as average feet increases, number of strikes also increases. 

### Which states were affected the most in terms of damage/strikes? A map was used with a parameter of Number of Strikes and Total Costs. This shows the states that had the most amount of strikes and also the states that had the highest cost in repairs. My hypothesis was off, although I was right about California having the highest amount of strikes, New York beat out every state in terms of costs. New York had 15% ($50 million) of the total costs in the US (total over $300 million), which almost doubled California. Then came surprisingly, Colorado with $30 million, California came 3rd with $29 million. This caught be surprise because New York was in 4th place with the highest amount of strikes but first place in costs.

### Lastly, when did the accidents occur (Approach/Landing Roll/ Takeoff run)? A bar graph with phase of flight and number of strikes was used to find out at which points the accidents was happening. My assumption was arounding the landing time, the plane would have the most amount of strikes. With the bar graph, it visually shows that the approach had the most amount of strikes (9625), then landing roll came second with 7527. My assumption was correct, during the landing time, the approach and landing roll, takes the most amount of damage.

### A table of the top 10 species with the highest number of strikes was provided on the side. Also, cost per damage table was provided to give an understanding on the amount spent for minor to major repairs.

## Tableau Public Dashboard Link: https://public.tableau.com/app/profile/mohamed.aden8701/viz/LHL-FAAWildLifeStrikesMADEN/Dashboard1?publish=yes

## Challenges 
### Biggest challange was the incomplete data, we didn't get a full year in 2015. Data stopped during May, which was less than half the year, a forecast was used to fix this outliar. Also, playing around with the parameters, I tried adding the number one species that had the most strikes within the map sheet where there was already a parameter for strikes and costs. I wanted to see if I can show the states and which species were affected the most within that state. It was hard trying to get around the error Tableau gives you on adding aggregate and non-aggregate functions within the calculated field. Sure I could of just did it on another map sheet, but that would of been a waste of space within the dashboard, it would of been far more affective within the parameter.

## Future Goals
### Have a complete understanding to get around such errors within the calculated field, and find better shortcuts within Tableau.
