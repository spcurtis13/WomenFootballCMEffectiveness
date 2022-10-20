This project is an exploratory data analysis project that looks at the effectiveness of center mids during the Women's Super League 2019-2020 season.

This project uses Statsbomb data that only records where players are at when an event occurs (shot, pass, tackle, etc.). This was an interesting restriction on exploring center mids because a lot of impact happens in the lead up to events not just the events themselves. The project had to narrow its scope which proved beneficial in hindsight to just center-mids offensive impact. To determine a large part of the rating basic stats were used that statsbomb recorded over the course of games during the season like goals, errors, and key passes.

I added two composite stats that provide some nuance which was the incomplete backward passes as well as the forward passes completed in zones 5/8. Zones 5 and 8 on a soccer pitch can be seen in the diagram below.

<img src="http://4.bp.blogspot.com/-Xe5BSJEwN30/Ug7Ojj-t-zI/AAAAAAAAA3I/oK-rO8JUgV4/s1600/zone+14+in+18+zones.png" alt="Alt text" title="Optional title">

Important to note is zone 14 which is circled in red is something that I chose not to focus on. Traditionally in modern coaching getting the ball in zone 14 is understood to generate the team's best chances. I chose not to aggregate the data there because I found that so many good things were already being reflected in the data when the ball is in zone 14. The information was being reflected in the basic stats like key_passes made and goals scored.

Zone 5 and 8 are on the defensive side of the field but by limiting passes completed that were forward as well as over 10 meters the statistic correlated fairly well with my perception of who the best players in the league are. By making the passes the stats was a good indication that the center-mid was beating the pressure which is more important than ever in modern pressing game that is widespread across the European top flight. 

Aggregating all the information together to form the rating worked out as well as I could of hoped with the limited nature of the data present and the basic way I was analyzing the behavior of the players. My ratings reflect the top players in the league well while still showing players who put their team in good spots are rewarded by my system even if they themselves do not make the final pass or even the pass previous to that.

I will revisit this project in the future to flesh out the more offensive nature of the incisive passes that can split open a defence. I can introduce a lot more nuance in the next iterations becasue of increased familiarity with the data as well as Pandas.
