# **Deliverable 1: Create a Horizontal Bar Chart (35 points)


## **Deliverable 1 Instructions**

Using your knowledge of JavaScript, Plotly, and D3.js, create a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart will display the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart.

Your bar chart should look like the following image:
![This is an image](/Users/ruiminma/Documents/UCB/Module_12_Data_visualization_in_JavaScript/plotly_deploment.io/data-Module-12-Challenge-1-horizontal-bar-chart-of-the-top-10-utos.png)

## **REWIND**

### ***For this deliverable, you’ve already done the following in this module:***

Lesson 12.1.3: Create a bar chart
Lesson 12.2.1: Use JavaScript functions and methods: map(), filter(), reverse(), and slice().
Lesson 12.2.2: Create a bar chart with filtered arrays
Lesson 12.3.2: Load a JSON file with d3.json()
Lesson 12.4.3: Create a function that reads in json data
Lesson 12.4.3: Write code to use the ID number to create the sample’s information on a panel or chart
Lesson 12.5.1: Deploy your project to GitHub Pages

Download the BellyButton_bar_chart_starter_code.js, add it to the js folder of your GitHub pages (GitHub.io) folder, and rename the file charts.js. Use the instructions below to add code where indicated by the numbered-step comments in the starter code file.

In Steps 3-6, you’ll initialize variables that hold arrays for the sample that is selected from the dropdown menu on the webpage.


### ***IMPORTANT***

Make sure that you use console.log() to help debug any issues.

In Step 1, we’ve provided the code for the buildCharts(); function that contains the argument sample, which is the sample that is selected from the dropdown menu.
In Step 2, we’ve provided the code to retrieve the samples.json file using the d3.json().then() method.
In Step 3, create a variable that has the array for all the samples.
In Step 4, create a variable that will hold an array that contains all the data from the new sample that is chosen from the dropdown menu. To retrieve the data from the new sample, filter the variable created in Step 3 for the sample id that matches the new sample id chosen from the dropdown menu and passed into the buildCharts() function as the argument.
In Step 5, create a variable that holds the first sample in the array.
You can combine Steps 4 and 5 as one line of code, but make sure you use the correct variable name for Step 6 when retrieving the array data.

In Step 6, create variables that have arrays for otu_ids, otu_labels, and sample_values.

In Step 7, create the yticks for the bar chart.



## **HINT**

In Steps 8-10, create the trace object, the layout, and Plotly.newPlot() function for the horizontal bar chart.

In Step 8, create the trace object for the bar chart, where the x values are the sample_values and the hover text for the bars are the otu_labels in descending order.
In Step 9, create the layout for the bar chart that includes a title.
In Step 10, use the Plotly.newPlot() function to plot the trace object with the layout.



