# UFOs

## Overview of the project

For this project we have to build a dynamic webpage that will accept user inputs and visually adjust to reflect that interaction, inserting javascript into an html page to display the data as a table, but as there is so much data, navigate it without any adjustments would be a challenge. 

We use a table to hold and display the data we want to work with, and also with javascript we can add filters in order to manipulate data wich lets user refine their search on more than one level. The table is interted into a html page, using basic html, bootstrap and css to build and style the page.

So, we essentially need to build two things: the webpage that will allow users to view the data (HTML) and a dynamic table (JavaScript). For the project, our webpage will display all of the UFO sightings with the option to filter by Date, City, State, Country and Shape.

## UFOs Results

Webpage view without filters

<img src="https://github.com/Jponce25/UFOs/blob/384fccf7263c0f9464fca55dda21fdba1a557fac/static/images/1.png" width="180">

We can add a filter with one criteria, to filter we have to enter a value in one of the 5 input boxes and click outside the input box or hitting enter to start the filter.

Webpage with one filter

<img src="https://github.com/Jponce25/UFOs/blob/384fccf7263c0f9464fca55dda21fdba1a557fac/static/images/2.png" width="180">

We can also add a filter with multiple criteria, entering the values ​​in each input boxes that we require.

Webpage with multiple filters

<img src="https://github.com/Jponce25/UFOs/blob/384fccf7263c0f9464fca55dda21fdba1a557fac/static/images/3.png" width="180">

To restart the filter we can go to de nav bar button to reload the webpage, or just ereasing the input box.


## UFOs Summary

Although the filters work as they should be, there are several drawbacks, especially with the inputs that the filters receive. Since we do not know the options allowed in each input box, for example, if a filter is not written properly, it will identify that there is no information.

Recommendations:

It is considered that the filter options can be improved, for example, that cases where the user uses capital letters can be automatically corrected internally. Another recommendation would be the use of options in the filters, that is, not using free text option, we could use some drop-down button that consider the possible content of the table.