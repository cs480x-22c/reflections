<h1> Reflection 5: League of Legends Champion Pick Rates </h1>

For this week's reflection, I tried looking for some interesting visualizations pertaining to a popular Esport I follow, League of Legends.

I came across this data science project by Pratt Institute student, Yang Cong. For a final project, Cong (and possibly a partner, he references a "we" a lot but no partner is specifically named) used datasets consisting of game match data from various ESports games, including the NA and EU LCS, LCK, LMS, and more.

The visualizations, hosted on a very nice dashboard on Tableau public, consist of...
<ul>
  <li>A stacked-bar chart for champion pick and ban rates (All champion rates represented by a %, so each bar adds up to 100%, making a square).</li>
  <li>A bar chart displaying how many times a certain champion has lost to another champion.</li>
  <li>A line chart of champion average KDA (Kills/Deaths/Assists) by time</li>
  <li>A Champion Network</li>
</ul>
For the sake of this reflection, I'm going to focus on the stacked-bar charts.

![alt text](https://github.com/MFaria27/reflections/blob/master/Images/League%20Pick%20Rates.PNG?raw=true)

<h2> Reflection </h2>

With over 140 champions in the game, a graph like this looks like an absolute mess when you first look at it. There are pretty much repeating colors for some champions, so reading the legend is a nightmare. Thankfully, each segment on a bar is sorted alphabetically ascending as you go from top to bottom. The numbers on the Y-axis are also somewhat misleading, as the percentages don't mean anything until you look at a specific segment; all you need to know is that every segment will add up to 100%.

Despite these criticisms, the interactable aspect of this visual 100% makes up for it. Hovering over each segment reveals the champion, what quarter it was played it, and its pick or ban rate. You can also select specific champions or quarters, graying out every other champion. This makes analyzing specific champion rates very easy to compare throughout the different quarters. You can also select specific game locations to see what champs were played most where.

This, in my opinion, is a great example of using interaction in a visual to make it better. I heavily recommend anyone reading this to click the link below to check it out (Especially if you play the game).

<h2> Links </h2>
<a href="https://public.tableau.com/app/profile/yang3651/viz/LeagueofLegendsDataviz/LeagueofLegendsDataVisualization">Interactable Visualization (Tableau Public)</a>

<a href="https://studentwork.prattsi.org/infovis/projects/league-of-legends-data-visualization/">Cong's Final Project WriteUp</a>

<h3> - Mattheus Faria </h3>
