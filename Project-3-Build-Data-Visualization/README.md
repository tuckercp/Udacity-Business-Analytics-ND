## Project #3 - Build a Data Visualization Project 🖼️

### Table of Contents
* [Project Summary](#Project Summary)
* [Dataset Used](#Dataset Used)
* [Task](#Task)
* [Visualization #1](#Visualization #1)
* [Visualization #2](#Visualization #2)
* [Visualization #3](#Visualization #3)

### Project Summary
The goal of this project is to create a set of visualizations with Tableau that reveal insights from a dataset. The visualizations should reflect the principles and practices of good data visualization, i.e. visual encodings, design principles, and effective communication.

### Dataset Used
The data comes from [Kaggle](https://www.kaggle.com/datasets/usdot/flight-delays), and tracks the on-time performance of US domestic flights operated by large airline carriers in 2015. There are 3 .csv files in the dataset; _flights.csv, airlines.csv_ and _airports.csv_. The _flights.csv_ file must be used in creating the visualizations while the other two provided files may be used in conjunction with the _flights.csv_ file, but should not be used alone.

### Task
I have been asked to build 3 visualizations for this project. The first must be a dashboard that encompasses several different worksheets. The other two visualizations can include single worksheets, additional dashboards or stories, or any other combination. The visualizations must also meet the following criteria:
* Centered on a specific finding and clearly communicated
* Incorporates interaction or animation, including filters and tool-tips in at least 1 visualization
* Includes a brief summary of the findings and an explanation regarding design choices
* Colours are chosen with accessibility in mind
* 3 different types of visuals have been used (i.e. bar, line, pie chart, histogram, map)

### Visualization #1
[Tableau Dashboard](https://public.tableau.com/app/profile/corey.tucker/viz/2015USFlightDelays_16737435023730/DOMESTICDASHBOARD)

#### Summary
This visualization incorporates a few different visuals for the dashboard. It displays the average delayed minutes for each of the 14 domestic airlines in the United States (including an option to group by all airlines), over a few different representations and parameters. There are 5 total graphs. Starting from the top left in a clockwise rotation:
1) Map showing the average total airline delays (arrivals & departures) by origin airport, whereby the size of the bubble represents the number of minutes delayed.
2) Sorted bar chart which displays the top 10 airports with the longest average departure delays in minutes. The colour spectrum represents the total delayed minutes per airport over the year.
3) Heat map representing the average total number of delayed minutes per day of the week.
4) Histogram demonstrating the average total number of minutes delayed based on flight distance in miles. Each bin represents 500 miles. The colour spectrum represents the total delayed minutes per airport over the year.
5) Line chart that showcases the average number of minutes delayed per month for each airline. The colour spectrum also represents the total delayed minutes per airport.

#### Design
In designing the dashboard, the theme of air travel and flying compelled me to use various shades of blue to represent the sky. I wanted my dashboard to be clean and simple with regards to the colouring, and opted for a light blue background as the theme with darker blues used for highlighting purposes. I didn’t want to clutter nor overload the dashboard with too many charts and graphs or colours, and felt that 5 was the absolute maximum for this dashboard. Finally, I wanted the user to be able to use the filter to focus in on a certain airline or view all of the airlines together for the year.

### Visualization #2
[Tableau Dashboard](
https://public.tableau.com/app/profile/corey.tucker/viz/2015USAirlineDelays/DELAYEDAIRLINES)

#### Summary
This visualization graphs all 14 of the US domestic airlines by the percentage of each carrier’s total flights that had delays of 15 min or more, and delays of 1 hour or more. The bar chart is sorted by the airline with the highest percentage of delayed flights to the lowest percentage. The tool-tip also shows the total number of delays over 15 min and 1 hour respectively. Using Tableau's calcluated fields allowed me to determine the percentage of delayed flights by a given number of minutes. United Airlines had the highest percentage of their flights with departure delays longer than 15 min at 62.6% of flights, while Spirit Airlines had the highest percentage of flights with delays 1 hour or longer. 22.6% of their flights had delays of 1 hour or more.

#### Design
Included in the visualization is a highlight parameter, which functions when a particular airline is selected from the drop-down menu. After a selection has been made, the selected carrier is then highlighted in a darker blue compared to the other 13 airlines, which remain light blue. The idea is to allow the user to easily visualize where the selected carrier falls among the other airlines in the visual.

### Visualization #3
[Tableau Dashboard](https://public.tableau.com/app/profile/corey.tucker/viz/2015USAirlineDepartureDelaysCancellations/AIRLINESCANCEL?publish=yes)

#### Summary
This visualization highlights the average number of minutes in departure delays and total number of cancellations among the 14 US domestic airlines. The first stacked bar chart shows both the average minutes in departure delays and average minutes in taxing out for each carrier. United Airlines has the highest average delay in minutes with an average total departure delay of 32.49 minutes. Hawaiian Airlines has the lowest average at 11.12 minutes in total departure delays. The second stacked bar chart graphs each of the reasons for the cancellations among each carrier, showing the total number of cancellations. Southwest Airlines has the highest number of cancellations with 309 over the year. Atlantic Southeast Airlines has the highest number of cancellations for reasons regarding the National Air System, while American Eagle Airlines has the highest number of cancellations due to weather.

#### Design
In designing the stacked bar charts, I aimed to pick colour schemes that were contrasting to each other, in order to make them accessible for colour-blind users. Contrasting colours allow the user to effectively distinguish each of the different stacks that make up each bar without difficulty.

### Additional Resources
In preparing my visualizatons, I used a font not native to Tableau which I have referenced here: [Skyfont](https://www.1001fonts.com/departure-board-fonts.html)
