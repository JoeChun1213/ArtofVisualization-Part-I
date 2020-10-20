## Project Overview
In this module, we will use Plotly.js, a JavaScript data visualization library, to create an interactive data visualization for the web. The completed work will be displayed in a portfolio we created.  

## Resources  
- **Data Source:** [index.html](/index.html), [samples.json](/samples.json), [plots.js](/plots.js) 
- **Software:** VS Code, Web browser, Command-line interface, GitHub

## Objectives  
By the end of this module, we will be able to:  
- Create basic plots with Plotly, including bar charts, line charts, and pie charts.
- Use D3.json() to fetch external data, such as CSV files and web APIs.
- Parse data in JSON format.
- Use functional programming in JavaScript to manipulate data.
- Use JavaScript’s Math library to manipulate numbers.
- Use event handlers in JavaScript to add interactivity to a data visualization.
- How to use interactivity to enhance your visualizations.
- Deploy an interactive chart to GitHub Pages.  


## Challenge Overview
In this challenge, we have a partially completed dashboard, but need to finish it. We have a completed panel for demographic information and now need to visualize the bacterial data for each volunteer. Specifically, the volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, our volunteers will be able to identify whether that species is found in quantity in their navel.  

## Challenge Objectives  
The goals of this challenge are for us to:
- Create a bar chart of the top ten bacterial species in a volunteer’s navel. Use JavaScript to select only the most populous species.
- Create a bubble chart to visualize the relative frequency of all the bacterial species found in a volunteer’s navel.
- Complete the demographic information panel, if you have not done so.  

## Challenge Summary  
#### Instructions  
Continue working with the samples.json dataset, and complete the following tasks:  

**When an individual’s ID is selected, the top 10 bacterial species (OTUs) should be visualized with a bar chart. Create a horizontal bar chart to display the top 10 OTUs found in that individual.** 
 - Use sample_values as the values for the bar chart.
 - Use otu_ids as the labels for the bar chart.
 - Use otu_labels as the hover text for the chart.  
 
**In the Demographics Info panel,** display all the key-value pairs of the selected individual’s demographic data.  

**Create a bubble chart that displays each sample:**  
Use otu_ids for the x-axis values.  
Use sample_values for the y-axis values.  
Use sample_values for the marker size.  
Use otu_ids for the marker colors.  
Use otu_labels for the text values.


#### Extension
**Adapt the gauge chart from Plotly documentation to plot the weekly washing frequency of the individual.**  
- Modify the example gauge code to account for values ranging from 0 through 9.  
- Update the chart whenever a new sample is selected.  
