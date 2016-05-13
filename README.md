#Make Effective Data Visualization

This is project 6 of Udacity's Data Analyst Nanodegree, connected to the course DATA VISUALIZATION WITH D3.JS.

###Summary
I represented survival rate among Titanic passengers through a grouped bar chart in Dimple js. 
I wanted to show whether being a woman or a passenger of higher class resulted in higher survival
rates. My chart shows that both these things are true: women survived more than men, but higher
classes survived more than lower classes overall.

###Data Selection and Exploration
My visualization draws from project 2 of the Data Analyst Nanodegree: Investigate the Titanic Dataset.
The original iPython Notebook with the analysis and the raw data are included in my project 2
[Github repository](https://github.com/robertozanchi/titanic-data). The full report is also included 
here as ```titanic_analysis.html```. 

### Visualization Design
####1. Sketch on paper
I started the visualization process by drawing a sketch by hand, here included as ```sketch.jpg```.
The initial idea was to represent the data as a vertical bar chart, where the categories on the x axis
were passenger classes (1st, 2nd and 3rd) and each category had bars for female and male passengers.  

####2. Version 1 of the chart
I translated the initial sketch into the first version of the chart in Dimple js: ```index_1.html```.

####3. Version 2 of the chart
In response to the initial feedback received - reported below - I produced ```index_2.html``` with a
changed classification on the x axis. The passengers are now grouped by sex and then class. This results
in more clarity in showing the different survival rates and the declining survival rate between women and
men, and first to third class.

####4. Final version of the chart
In the final version of the chart, ```index_final.html```, I added further details for clarity and more 
effective communication:
- Separated bars for males and females with a vertical line in the background;
- Changed ration to percentage on the y axis;
- Renamed titles of both axes;
- Added a title to the graph;
- Added a legend and a legend title.

To do so, I used both methods in Dimple js and D3 code.

###Feedback
I collected feedback from 5 people among family members and friends, at all stages of visualization design
outlined above.

The most useful comments/suggestions were:
- Aggregate data by sex first and then class, to show different survival rates more clearly;
- Add a vertical line of separation in the background of the graph, between female and male categories; 
- Use more clear and detailed titles and data formats for the x and y axes;
- Add a legend and a title for the legend;
- Use an expressive title that guides the reader in exploring the data and drawing conclusions.

###Resources
- http://dimplejs.org/examples_viewer.html?id=bars_vertical_grouped
- http://jsfiddle.net/farrukhsubhani/S6FLv/7/
- http://stackoverflow.com/questions/25416063/title-for-charts-and-axes-in-dimple-js-charts