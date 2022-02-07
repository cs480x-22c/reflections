[1] https://observablehq.com/@mbostock/most-popular-programming-languages-2004-2021
[2] https://pypl.github.io/PYPL.html

This vis [1] is a bar race chart dispalying the "Most Popular Programming Languages 2004-2021" based on GitHub's PYPL Data [2]. It shows the 12 Most Popular for each month of each year in the titled time period, with popularity tracked in the data via Google Trends searches of programming tutorials in each language. The vis itself is simple but eye-catching. It utilizes simple animation in order to create a racing-effect in which the bars appear to compete with one another as the data is updated over time. Personally, bar chart races always grab my attention, and I tend to watch to the end while trying to anticipate which set (in this case which programming language) will "win" the race. Competition, moreover the simple thrill of a "race for first", is what gives the bar chart race its effectiveness. However, it is worth noting that bar chart races are less effective in cases where you want to emphasize multiple data points or have a more complex data set, since the race itself really emphasizes the first, second, and maybe third place sets above the rest. Bar race charts also aren't great for displaying relative quantities, since the axis scale, bar sizes, and percentages are constantly changing as the chart progresses through its animation.

Moving on: There are an incredible number of bar chart races located on the internet, both embedded in websites and uploaded in video format on sites such as YouTube. It's by no means a unique or novel idea for a vis: so what makes this one significant? To me, the importance of this vis lies in what the data is representing. In the field of CS, proficiency in commonly-used languages is essential, and knowing more languages means having more work opportunities. Since the data represented in this vis tracks Google Trends searches of a language using "Tutorial" as one of the keywords, it is a great representation of the current popularity and rate at which different languages are growing, with the most important being the top 3: Python, Java, and JavaScript. Staying on top of trends in the field of CS can be difficult since the field is always growing and changing with new innovations and discoveries added onto a massive personal and professional user-base, so I'm always interested when it comes to data visualizations representing these trends.


Note: Apologies for the poor grammar. I am currently very sleep-deprived.



Drawbacks:
Metric may not check out:

"The PYPL PopularitY of Programming Language Index is created by analyzing how often language tutorials are searched on Google : the more a language tutorial is searched, the more popular the language is assumed to be. It is a leading indicator. The raw data comes from Google Trends.

Is very slow, would like coverage sped up OR the implementation of a fast forward option
Only captures the top % of languages. There are few enough programming languages that this is OKAY, but a bar chart race wouldn't work for a lot of other things due to this reason
