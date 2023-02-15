This project is an exploratory data analysis project that looks at the effectiveness of center mids during the Women's Super League 2018 -2019 season.

This project uses Statsbomb data that only records where players are at when an event occurs (shot, pass, tackle, etc.). This was an interesting restriction on exploring center mids because a lot of impact happens in the lead up to events not just the events themselves. The project had to narrow its scope which proved beneficial in hindsight to just center-mids offensive impact. To determine a large part of the rating basic stats were used that statsbomb recorded over the course of games during the season like goals, errors, and key passes.

I added two composite stats that provide some nuance which was the incomplete backward passes as well as the forward passes completed in zones 5/8. Zones 5 and 8 on a soccer pitch can be seen in the diagram below.

<img src="http://4.bp.blogspot.com/-Xe5BSJEwN30/Ug7Ojj-t-zI/AAAAAAAAA3I/oK-rO8JUgV4/s1600/zone+14+in+18+zones.png" alt="Alt text" title="Optional title">

It's worth noting that while zone 14, highlighted in red, is typically seen as a key area for generating a team's best chances in modern coaching, I made a deliberate choice not to focus on it. This is because the data already captured a wealth of valuable information about the team's performance in this zone, reflected in key passes made and goals scored.

Instead, I turned my attention to zones 5 and 8 on the defensive side of the field. By analyzing completed passes that were both forward and over 10 meters, I was able to gain insight into which players were truly excelling. In today's game, where pressing is a common strategy, being able to beat the opposition's pressure is a crucial skill for any center-mid.

Despite the limited nature of the data available and my basic analysis approach, aggregating all the information together to form my ratings proved highly effective. I was able to accurately identify the top players in the league while also rewarding those who put their team in good positions, even if they didn't necessarily make the final or penultimate pass.

Looking to the future, I plan to revisit this project and explore the more offensive nature of incisive passes that can split open a defense. With increased familiarity with the data and tools like Pandas, I'm confident I can introduce greater nuance and sophistication to my analysis in future iterations.
