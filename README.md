# web-design-challenge

The goal of this project is to create a visualization dashboard website using visualizations from https://github.com/aaronlee28/python-api-challenge/tree/main/WeatherPy. 

In building this dashboard, I created individual pages for each plot and a means by which to navigate between them. These pages will contain the visualizations and their corresponding explanations. I also have a landing page, a page where users can see a comparison of all of the plots, and another page where users can view the data used to build them. 

This dashboard consist of 7 pages total, including: 
A landing page containing:
An explanation of the project.
Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.
Four visualization pages, each with:
A descriptive title and heading tag.
The plot/visualization itself for the selected comparison.
A paragraph describing the plot and its significance.
A "Comparisons" page that:
Contains all of the visualizations on the same page so users can easily visually compare them.
Uses a Bootstrap grid for the visualizations.
The grid is two visualizations across on screens medium and larger, and one across on extra-small and small screens.
A "Data" page that:
Displays a responsive table containing the data used in the visualizations.
The table uses a bootstrap table component.
The data comes from converting the CSV file to HTML using panda dataframe.

