# Tornado Archive

Site: https://tornadoarchive.com/explorer/1.0/

<img width="640" alt="Screenshot_20220131_115303" src="https://user-images.githubusercontent.com/33555592/151840764-324daec2-c299-4de1-a976-4fd2803e840a.png">

There are lots of interactive weather visualization tools, and the Tornado Archive's historical map is no exception. Functionally, the map appears to work well, and the color scheme (redder colors are more intense tornadoes) works well across the color vision/blindness spectrum. To test the site for color blindness accessibility, I uploaded a screenshot of the map with all tornadoes enabled (for maximum color spread) to an online color blindness simulator and cycled through various color blindness filters.

<img width="388" alt="Screenshot_20220131_115808" src="https://user-images.githubusercontent.com/33555592/151840857-9be2c29d-a492-40fe-9756-decf6050db10.png">

In addition to being able to filter out tornadoes by date (it shows chronologically recent tornadoes first), it's also possible to filter tornadoes by intensity. Double clicking on a tornado path yields more information about the tornado itself - specific coordinates, time active, and even fatality/injury count. Critically, it's possible to use this visualization as a sort of browser, to discover more information about tornadoes, instead of merely as a trend display. There's also the option to share the current view by taking a screenshot, which is nice for quality-of-life and can be used to help share speicfic information online. Unfortunately, the screenshot feature did not work for me in Firefox on Ubuntu 20.

While the information displayed and the interactive opportunities in this visualization are great, several accessibility/style issues remain. First, there is little padding around buttons and text, most apparent in the number/fatalities/injuries display in the top right side of the screen. This overall compactness can make texts and graphs difficult to read, when there isn't any real need. The map can be zoomed in and out of, so decreasing the relative size of the map would allow for more supporting information without compromising the actual visual data display.
