# UFOs

## Overview

The purpose of this analysis was to assist Dana in providing a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time, including date, city, state, country, and shape.

## Results

While the upper section of the webpage with the title, subtitles, and introductory paragraph remained the same, the section containing the table and UFO sightings data was altered.  The "Filter Search" section was updated to include city, state, country, and shape, as well as the initial date filter.  Further, the button to filter the table was removed and replaced with a function to automatically update the table when filters are added.  The "Filter Search" section now looks as follows:

<img width="350" alt="filter_search" src="https://user-images.githubusercontent.com/94088129/163248389-c7d079e3-86f7-4f1e-93e8-2804c1e9883f.png">

The automatic update function also allows the user to input however many filters they want.  If they do not enter any filters, the data simply displays in its entirety.  As each filter is added, the data displayed gets more and more specific.  For example, with no filters activated, the table looks as follows: 

<img width="1483" alt="no_filter_table" src="https://user-images.githubusercontent.com/94088129/163249462-5c68543d-9ec3-4c69-82b7-fadd5259494f.png">

(The values currently residing in the filter text boxes are placeholders and do not affect the displayed data)

If we add two filters, such as "us" for the country and "light" for the shape, we get the following image: 

<img width="1466" alt="us_light_table" src="https://user-images.githubusercontent.com/94088129/163251077-403ce54d-f351-4ae7-a68f-db9203f5b3a1.png">

### Summary

A drawback of the new design is that, while you can further filter the data, there is no way to see what options you have to do so.  A more effective filtering tool might be a dropdown menu populated by the unique values in each category, rather than a textbox that needs to be filled.  

One way to further develop the webpage would be to expand the data source.  Currently, the only data source is a file of sightings from 2010; however, if you were to locate other websites or forums with this type of information, you could use web scraping to extract the data from those websites and populate the table on your website.  Currently, your data is mostly representative of the United States, with a couple of instances from Canada.  Expanding your data pool would also expand your list of sighting locations.

Another idea would be to create a submissions page, where viewers of your website could submit forms filled out with their own experiences.  You could make the filters required inputs, while taking other information without making it a required input or listing that information in the table.  That would add a touch of personalization and interaction to the page which would help engage your audience.
