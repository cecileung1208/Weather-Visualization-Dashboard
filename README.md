# Weather Visualization Dashboard

![Image](https://www.sciencemag.org/sites/default/files/styles/article_main_image_-_1280w__no_aspect_/public/ca_0724NID_Earth_online.jpg?itok=glL-Bgbs)

## Background

Visualization dashboard website will be created  with plotting [weather data](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/cities.csv) from the last project, [Global Weather Analysis](https://github.com/cecileung1208/Global-Weather-Analysis) .<br>

In building this dashboard, individual pages for each plot will be created and the user can navigate between them. These pages will contain the visualizations and their corresponding explanations. There will also have a landing page, a page where the user can see a comparison of all of the plots, and another page that provides the data source.

## Requirements

The website must consist the following html and style pages:

* **[Landing page](#landing-page)** 
  - An explanation of the project.
  - Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

* **[Visualization pages](#visualizations-page)**
  - 4 visualizations:
    * Latitude vs. Maximum Temperature
    * Latitude vs. Humidity
    * Latitude vs. Cloudiness
    * Latitude vs. Wind Speed
  - A descriptive title and heading tag.
  - The plot/visualization itself for the selected comparison.
  - A paragraph describing the plot and its significance.
  

* **[Comparisons page](#comparisons-page)**

  - Contains all of the visualizations on the same page so we can easily visually compare them.
  - Uses a Bootstrap grid for the visualizations.
  - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

* **[Data page](#data-page)**

  - Displays a responsive table containing the data used in the visualizations.
  - The table must be a bootstrap table component. 
  - The data must come from exporting the [.csv file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/cities.csv) as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called [to_html](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/Cities%20Table%20HTML%20Coversion.ipynb) that allows you to generate a HTML table from a pandas dataframe.
 
**5. Style Sheet**

  - This is to store default settings for the html files.  
  - Settings include fonts, padding, background colour, formats for resizing the browser etc for the header and paragraph text, navigation bar, containers, column sizes, footer.
  - Details are in the [style.css file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/style.css)
  
## Datasets

## Method

## Scripts 

## Results



The website must consist of 7 html pages and 1 style page in total, including:

**1. A [Landing page](#landing-page) containing:**

  - An explanation of the project.
  - Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
  - See the [index.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/index.html) for the html codes.

**2. Four [Visualization pages](#visualizations-page), each with:**

  - A descriptive title and heading tag.
  - The plot/visualization itself for the selected comparison.
  - A paragraph describing the plot and its significance.
  - See the [max_temp.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/max_temp.html), [humidity.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/humidity.html), [cloudiness.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/cloudiness.html), and [wind_speed.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/wind_speed.html) for the html codes.


**3. A [Comparisons page](#comparisons-page) that:**

  - Contains all of the visualizations on the same page so we can easily visually compare them.
  - Uses a Bootstrap grid for the visualizations.
  - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
  - See the [comparisons.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/comparisons.html) for the html codes.


**4. A [Data page](#data-page) that:**

  - Displays a responsive table containing the data used in the visualizations.
  - The table must be a bootstrap table component. 
  - The data must come from exporting the [.csv file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/cities.csv) as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called [to_html](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/Cities%20Table%20HTML%20Coversion.ipynb) that allows you to generate a HTML table from a pandas dataframe.
  - See the [data.html file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/data.html)
 
**5. Style Sheet**

  - This is to store default settings for the html files.  
  - Settings include fonts, padding, background colour, formats for resizing the browser etc for the header and paragraph text, navigation bar, containers, column sizes, footer.
  - Details are in the [style.css file](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/style.css)
### Screenshots

#### Landing Page

Large Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Dashboard%20-%20Big%20Screen.png)

Small Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Dashboard%20-%20Small%20Screen.png)


#### Visualizations Page

Large Screen 

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Visualization%20-%20Big%20Screen.png)

Small Screen 

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Visualization%20-%20Small%20Screen.png)

#### Comparisons Page

Large Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Comparison-%20Big%20Screen.png)

Small Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Comparison-%20Small%20Screen.png)

#### Data Page

Large Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Data%20-%20Big%20Screen.png)

Small Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Data%20-%20Small%20Screen.png)

#### Navigation Bar

Large Screen 

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Navigation%20Bar%20-%20Big%20Screen.png)

Small Screen

![Image](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Visualizations/Navigation%20Bar%20-%20Small%20Screen.png)
