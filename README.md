### Summary
Through this visualization I have facilitated the comparison of the performance of 1157 baseball players in terms of their batting average. You can pick up the players that you want to compare and their batting averages will be displayed in the chart.

### Design
* I decided to use Bar Chart to compare the performance of different baseball players because a clearly drawn bar chart is the best visual encoding to facilitate comparison between absolute measurement values for different categories.
* As the total number of players in the dataset was too large to be displayed altogether, I decided to let the user pick the players that she wants to compare through a drop down selection.
* Based on feedback, I chose to show the performance of three players from the dataset by default, so that the chart doesn't look empty when the page loads for the first time.
* I also added a reset button, so that the viewer can reset the visualisation by emptying the chart, without needing to reload the page.

### Feedback
1. "Even if the viewer can interactively choose the players to compared through the selection box, you should show the data of some players in the chart when the page loads for the first time."
2. "You can put a reset button on the page to quickly reset the display and let the viewer pick all the players from scratch."
3. "Show a compelling reason or finding behind your data visualization by highlighting some relationship between variables."
4. "Try to compare the performance of players by their handedness. You may encounter a surprising pattern there, which you can demonstrate in the plot."
I incorporated all of theses suggestions by making necessary changes in my design.

### Resources
* https://github.com/mbostock/d3/wiki/Selections
* https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart