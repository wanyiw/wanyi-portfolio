### Visualisation of Government Debt from OECD Website

<iframe src="https://data.oecd.org/chart/6syG" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6syG" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

### Using Flourish to Create Dataviz (Grid of line charts)

Using Flourish to create a sparkline chart (or small multiples) we see that the government debt-to-GDP ratio has increased over time for most countries. Unfortunately, I did not know how to change individual charts to a different line. If I did, I would have coloured it such that the countries that showed large increase of debt-to-GDP ratios over time would be coloured red while others were coloured gray. 

<div class="flourish-embed flourish-chart" data-src="visualisation/7244259"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Playing around with Flourish, I also re-created the same data into small multiples but instead of lines, it's an area graph. I feel that this chart makes it easier to compare between countries, and in paticular, highlight which countries gave data at a later date. 

<div class="flourish-embed flourish-chart" data-src="visualisation/7244564"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Using Flourish to Highlight Insight 

This graph uses the same dataset but zooms in on a single narrative which is to highlight how much Greece's debt-to-GDP ratio has increased over time in comparison to other countries. Looking at the dataset through the different chart-types available on Flourish, I felt that there was just too much data to process on one chart if each country were to be highlighted. While small multiples is a great way of visualising all countries in the same graphic, I felt there was no good way of putting all countries on the same chart without overwhelming the reader. As such, I chose to keep the visualisation simple by highlighting only one country, particularly a country that appears to be an outlier. Not having each line labelled was also a conscious design decision. Since most lines are gray, having labels wouldn't help the reader. Instead, through the title and subtitle, I made it clear that the red line referred to Greece. The selection of gray and red colours were done using Colorbrewer, it was very handy to have the # colours available for easy input into Flourish. 

<div class="flourish-embed flourish-chart" data-src="visualisation/7244954"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Discussion of Visualisations

As mentioned above, I think the small multiples dataviz and the line chart dataviz serve different purposes. The small multiples is a great way to compare many countries at once, especially if the intent is to allow the reader to do the comparisons for themselves rather than direct them to a specific country. The line chart dataviz (with highlighted line or lines) is more effective in pointing the reader to a specific point that the designer (me) is trying to make. For both visualisations however, I have tried to make the title as informative as possible rather than a mere description of the chart. 

One comment I have is that I had to manipulate the format of the original dataset to fit into a lot of the Flourish chart types. I'm wondering whether Flourish has an easy way of formatting data that I'm not aware of. Also figuring out the chart formatting "e.g. which column to apply as row filter" was not an intuitive process. 

[Return to Main Page](/README.md)
