# Plotly_Deploy / Belly Button Biodiversity 

## Overview:

Belly Button Biodiversity is the study of finding if a bacteria species in participants human navel can be synthesized into a protein and can be taste like beef. 

The project was developed as an interactive webpage by clicking a drop-down menu and choosing participant Test Subject ID. With the data gathered from participants all over the county, it will display participant demographic information, bar chart of top 10 bacteria cultures found in the sample, bubble chart of bacteria species per sample and gauge chart for belly button washing frequency. System used are JavaScript, HTML and Plotly.

## Results:

###	Deliverable 1: Create a Horizontal Bar Chart

  -Code is written to create the arrays when a sample is selected from the dropdown menu 
  
  -Code is written to create the trace object in the buildCharts() function, and it contains the following:
  
      o	The y values are the otu_ids in descending order
      o	The x values are the sample_values in descending order
      o	The hover text is the otu_labels in descending order.
      
  -Code is written to create the layout array in the buildCharts() function that creates a title for the chart 
  
  ![deliv1-code.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/deliv1-code.png)


  -When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following: 
      
      o	The top 10 sample_values are sorted in descending order
      o	The top 10 sample_values as values
      o	The otu_ids as the labels
      
  ![deliv1-bar_chart.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/deliv1-bar_chart.png)
  
  
  ###	Deliverable 2: Create a Bubble Chart

  -The code for the trace object in the buildCharts(); function does the following: 
  
      o	Sets the otu_ids as the x-axis values
      o	Sets the sample_values as the y-axis values
      o	Sets the otu_labels as the hover-text values
      o	Sets the sample_values as the marker size
      o	Sets the otu_ids as the marker colors
      
-The code for the layout in the buildCharts(); function does the following: 

      o	Creates a title
      o	Creates a label for the x-axis
      o	The text for a bubble is shown when hovered over
      
      
 ![deliv2-code.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/deliv2-code.png)
 
 
-When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu 

![deliv2-bubble_chart.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/deliv2-bubble_chart.png)


 ###	Deliverable 3: Create a Gauge Chart

-The code to build the gauge chart does the following: 

    o	Creates a title for the chart.
    o	Creates the ranges for the gauge in increments of two, with a different color for each increment.
    o	Adds the washing frequency value on the gauge chart.
    o	The indicator shows the level for the washing frequency on the gauge.
    o	The gauge is added to the dashboard.
    o	The gauge fits in the margin of the <div> element.
    
![deliv3-code.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/deliv3-code.png)


-When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable


![deliv3-gauge.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/deliv3-gauge.png)


 ###	Deliverable 4: Customize the Dashboard
 
 -The webpage has three customizations.
 
 -When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu 



![webpage-screen_shotv2.png](https://github.com/OPahunang/Belly_Button_Biodiversity/blob/main/resources/webpage-screen_shotv2.png)


