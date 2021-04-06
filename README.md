# Weather Visualization Dashboard

![Image](https://www.sciencemag.org/sites/default/files/styles/article_main_image_-_1280w__no_aspect_/public/ca_0724NID_Earth_online.jpg?itok=glL-Bgbs)

## Background

Visualization dashboard website will be created  with plotting [weather data](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/cities.csv) from the last project, [Global Weather Analysis](https://github.com/cecileung1208/Global-Weather-Analysis) .<br>

In building this dashboard, individual pages for each plot will be created and the user can navigate between them. These pages will contain the visualizations and their corresponding explanations. There will also have a landing page, a page where the user can see a comparison of all of the plots, and another page that provides the data source.

To accomplish this, HTML, Bootstrap, CSS and Pandas will be used to create the weather visualization dashboard.

## Requirements

The website must consist the following html and style pages:

* **Landing Homepage** that contains a background information on the project, navigation bars to plots, comparison and the original dataset, and a visualization section that links you to the information about the image.

* **Visualization pages** that contains the below 4 scatterplot images and by clicking on them it will describe the weather anlaysis of each plot.
    * Latitude vs. Maximum Temperature
    * Latitude vs. Humidity
    * Latitude vs. Cloudiness
    * Latitude vs. Wind Speed
  
* **Comparisons page** that contains all the scatterplot visualizations on one page.

* **Data page** that contains a table of the original dataset.

* **CSS Style Sheet** that stores the default styles and settings for the html files.

## Datasets

[Cities Climate Dataset](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/Resources/cities.csv)

## Method

**[Landing Page](#landing-page)**

* Create 2 containers using bootstrap that provides:
   *  An explanation on the project
   *  A visualization page (see below) that provides an image of each scatterplot and clicking the image will prompt the user to that visualization.
* Create a navigation bar for the following:
   * Links to each plot
   * Links to the comparison page
   * Links to the data
   
**[Visualization Page](#visualization-page)**
*  Create a container that displays the images in a 2 by 2 view using bootstrap grid.
*  The scatterplots include:
    * Latitude vs. Maximum Temperature
    * Latitude vs. Humidity
    * Latitude vs. Cloudiness
    * Latitude vs. Wind Speed   
* For each scatterplot, include:
   * A descriptive title and heading tag.
   * The plot/visualization itself for the selected comparison.
   * A paragraph describing the plot and its significance.

**[Comparison Page](#comparison-page)**

* Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

**[Data Page](#data-page)**

* Displays a responsive table containing the data used in the visualizations.
  * Using pandas, export the [Cities Climate Dataset](https://github.com/cecileung1208/Web-Design-Web-Visualization-Dashboard/blob/master/Resources/cities.csv) by using the to_html function to covert the pandas DataFrame to an HTML table.
  *  Use the bootstrap table component to create the table from the HTML table.

**[CSS Style Page](#css-style-page)**
* Create formats for fonts, font sizes, background colours, navigation bars, footers, column sizes, conatiners, and image padding for the webpages.
* Ensure all teh images are aligned when resizing the browser.

## Data Visualizations/Scripts 

#### [Landing Page](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/index.html)

![Image](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/Visualizations/Dashboard%20-%20Big%20Screen.png)

#### Visualization Page

* [Maximum Temperature Script](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/max_temp.html)
* [Humidity Script](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/humidity.html)
* [Cloudiness](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/cloudiness.html)
* [Windspeed](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/wind_speed.html)

![Image](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/Visualizations/Visualization%20-%20Big%20Screen.png)

#### [Comparison Page](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/comparisons.html)

![Image](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/Visualizations/Comparison-%20Big%20Screen.png)

#### [Data Page](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/data.html)

* [HTML Table Coversion](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/Resources/Cities%20Table%20HTML%20Coversion.ipynb)

![Image](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/Visualizations/Data%20-%20Big%20Screen.png)

#### [CSS Style Page](https://github.com/cecileung1208/Weather-Visualization-Dashboard/blob/master/style.css)

## Results

**1. Latitude vs Maximum Temperature**

Cities near the equator experience the highest maximum temperature. As the latitude increases , the temperature drops significantly. 

**2. Latitude vs Humidity**

The correlation is almost zero but one noticeable trend is that almost 80% of the cities have a humidity of greater than 60%

**3. Latitude vs Cloudiness**

The correlation is weak but the graphs do show that the majority of the cities have either 0% or 80-100% cloudiness.

**4. Latitude vs Wind Speed**

There is no strong relationship between latitude and wind speed as the correlation is only 0.15. However, as the latitude around 60-90 degress, there are numerous cities with wind speed of more than 20 mph.
