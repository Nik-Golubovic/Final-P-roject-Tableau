# Final-Project-Tableau

## Project/Goals
The goal for this project is to gain an understanding of the current playerbase around the world and create a visual dashboard that can be used to look for players based on position, overall attribute score, and marketvalue.  

## Process
### Upload the database and create visualizations

Insert the datebase into Tableau. Filter the data and remove null values and incoherent outliers. Create various visualization charts to compare the the overall score for each player with the determined value of the player. From here, graphs can be made to further filter the players by age, nation, and position.

### Create Dashboard and Set Filters

Once the above charts have been made, the dashboard can be created to add additional filters to the database. Individual players can be filtered for based on their Overall score, position, age etc. Players can be selected based on the needs of the team, and it can be determined if those players would be a good deal in the current market. Nations can also be selected to determine the average skill level, per position, per nation and this is how a more accurate scouting network can be created to search out lesser known players for cheaper.

## Results

The chosen database was the Fifa 2018 player stats database. 

The first visualization was an overall rating vs player value. This plotted out all of the players in the database and allowed us to see which were some of the best players in the rankings. 

The second visualization is the average overall rating per country. This shows us what nations have the best talent globally. As to be expected, the south american and southern european nations tended to fare better in terms of overall scoring.

From there we plotted the average market value per nation and saw some interesting results. Gabon was one of the highest value nations, but this is mostly due to a small sample size of players and one player being amongst the most expensive in the world, which tended to raise the overall average. In terms of value for rating the best bang for you buck comes from Croatia and Chile. 

Next we visualized the potential rating versus the market value but only amongst the younger players. Players under 22 were plotted and a regression line was created. Players on the bottom of the regression line tended to be "overhyped" which meant their value was much higher than their overall rating would suggest it should be. The players on the top of the regression line are cosidered better options for purchasing. These players have a value that is lower than their overall score would indicate, so teams would be getting a relative deal on a value per rating metric.

Finally we plotted all of this data to a dashboard and added a positional filter as well as a nationality filter. If the team knows what position a player needs to be, they can filter the data and return a list of players that could seek to sign. By only looking for players that match thier positional needs, they can look at the regression curve and determine if they are getting a good transfer deal. 

The question that we tried to answer was: can we find a young Goalkeeper, that has large amount of potential, and could be signed for relatively cheap?
Using the dashboard that I created, we can filter all goalies, by potential and looking on the top part of the regression line we see that there is one player named: Lafont, with a current rating of 77 and a potential to get up to 89, and he could be had for about 11.5 million Euros. There is also another choice, named: Farinez with a current rating of 73, but with a potential of 87 that could be had for less than a million Euros. This is a fantastic deal, but slightly more risky than the other player. 


## Challenges 

Challenges for this project were few. The majority of the issues aroze from having too many options to choose from. I tried to keep it simple and only focus on a few stats like ratings, value, and potential. Having to narrow down what it is that I was trying to accomplish was the largest issue.

## Future Goals
If I had more time I would add further filters to the dashboard to have more advanced metric analysis.
Being able to search for not only positions, but also individual stats that are more important for specific positions would be the next step, (eg. passing for midfielders, or strength for defenders).
