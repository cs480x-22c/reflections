
This week, I stumbled upon a twitter debate over a New York Times article that used a spiral graph 
to show the spread of covid over time. https://twitter.com/Wattenberger/status/1479276091751768065
Twitter user and developer Amelia Wattenberger made her own twist on the NYT visualization adding 
color and more well defined sample windows to the plot. This remedied the common criticism that the 
spiral plot looked like a pinkish-red tapeworm. She used svelte, a compiled JS framework that I've
played around with before, and her published code to make this plot is quite readable, leaning on
svelte's reactivity. You can see the code and interactive demo here: https://svelte.recipes/components/spiral/

For organizations like the New York Times that need to quickly create interactive visualizations, 
a tool like svelte may be able to help a lot, especially due to it's almost-html level of readability.
Her remix of the original plot allows users to get a feel for each country by contrasting not only the 
shape of the data, but the color plots as well. This use of multiple ways to communicate the same numbers
is quite helpful for the reader/viewer.
