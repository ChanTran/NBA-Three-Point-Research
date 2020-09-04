# NBA-Three-Pointer-Research
Data Analysis on the trend of three point shots in today's NBA game.

View the dashboards and data here: https://chantran.github.io/NBA-Three-Point-Research/

# Key Takeaways

* Data was taken from https://www.basketball-reference.com/

* It is worth noting the spike in the 94-95 season; teams started to notice the value of the three point shot after the NBA reduced the line from 23 feet to 22 feet, and as a result the amount of 3PA (three points attempted) has never gone down to the 93-94 values ever since. It is also worth noting that the change was reverted after the 96-97 season, so that is why 3PA dipped down after that season.

* Teams took 22% of their shots in the 16-3PT% zone. Looking at the 18-19 season however, we see that teams now only take 9% of their shots at that territory. That difference of 13% actually has shifted to how many three point shots teams are taking. In the 09-10 season, teams also took 22% of their shots at the three point line. Now in the 18-19 season, teams have taken 36% of their shots at the three point line. The percentage of combined mid range shots (10ft to the three point line) has also changed, and this shift means that teams are telling their players to either get closer to the basket, or to take a few steps back from that long midrange shot in favor for the three point shot.

![Mid Range](https://i.imgur.com/ppL9SpW.png)

* The data scraped provided various zones of shots (0-3 ft, 3-10 ft, etc), and we can use this to see which zones are the most efficient. I used the 18-19 NBA season particularly because it is the most recent completed season and showcases very well why teams are favoring three point shots:

![Zones](https://i.imgur.com/5tf1L2a.png)
 
* These visualizations answer the question whether or not the three pointer is better than the two point shot: it depends. If you can drive to the paint and get a shot off, typically that shot on average will get you more points than any other zone. If you can’t get a shot off though, it is better to kick it out to the three point line and forego mid range shots. If we weren’t particularly interested in the different two point zones, then the previous graph plotting PPS of 2 pointers and 3 pointers without the zones show that three pointers edges out two pointers. This is not reality however, and teams should be striving to get the ball near the basket as much as possible. 
