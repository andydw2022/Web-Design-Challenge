# Web Design Challenge : Latitude Weather Analysis

url= https://andydw2022.github.io/

This homework is composed of the following folders and files:

WebVisualisations Folder
    cloudiness.html
    comparisons.html
    convert_cities_to_html.ipynb
    data.html
    humidity.html
    Images
    landing_page.html
    README.md
    reset.css
    styles.css
    temperature.html
    windspeed.html
|
    Images Folder
       comparison-lg.png
       comparison-sm.png
       data-lg.png
       data-sm.png
       landing-sm.png
       landingResize.png
       nav-lg.png
       nav-sm.png
       visualize-lg.png
       visualize-sm.png
    Resources Folder
   

    assets Folder
      cities.csv
      cities_data.html
      
      Images Folder
        cloudiness.png
        humidity.png
        temperature.png
        windspeed.png

|
1. Juypter Notebook : convert_cities_to_html.ipynb which contains code to read in the file Resources\cities.csv 
   in csv format, convert it to a pandas dataframe , list it to check for missing data then create a html file 
   Resources\cities_data.html file from the dataframe. This file will then be read into the data.html page to display all
   the cities data. Doing it this way means not having to paste all the html cities table data into the data.html page
   Makes for easier maintenance.

2. HMTL files. Web site starts with the landing page then the user can navigate from there to see the various graphs 
   and data

3. Images of graphs made from Matplotlib.

4. Raw data file in .csv and .html format

