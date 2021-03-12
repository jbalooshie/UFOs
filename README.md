# UFOs

## Overview of Project
The purpose of this analysis is to build an easy to read and filter table. The table contains information about UFO sightings around the world, and can then be filtered to a specific Date, City, State, Country, or UFO shape. The table is presented on a tidy HTML page that can be shared with other UFO enthusiasts. In addition to the table, the page contains a title, banner image, and short article containing comments from various sources. 

The page itself is built in an html file. An app is created using JavaScript that will pull information on UFO sightings from a source file, display the data, and filter it as various parameters are entered. Finally, Bootstrap was used to make the page pleasing to the eyes, and also scale depending on the type of device you are using to view it. 

## Results
To use the webpage, start by opening the index.html file. Scroll down until you see the start of the table. You will see the filter options to the left of the table. To filter the table, simply enter the desired criteria you would like to see results for. Placeholder values have been provided if you are unsure of what to enter. Below are two images. The first shows the table with the filters, with only the placeholder values. The second shows the table filtered to show UFO sightings in the city of el cajon. 

![Filter Options](tree/main/static/images/image_1.png)
![Filtered Table](tree/main/static/images/image_2.png)

## Summary
To close out the report, we will review one of the drawbacks of this page, and provide two recommendations for how it could be improved in the future. 
###Drawbacks
Right now, the fitlers will only accept lowercase value to correctly filter. For example, entering "benton" into the city filter will bring up a sighting that occured in Benton, CA. However, entering "Benton" will not bring up this sighting. This might be confusing for users looking for a specific sighting. It is normal to capitalize city, state, and country names. There are a couple of ways we can fix this. We can add a note that reminds the user to enter their search criteria in all lowercase. Or we could refind the code to look for close matches instead of an exact match. The latter would be preferable, since it doesn't rely on the user following special instructions to use the table. 

###Recommendations
1. Currently there is no way to search the duration and comments fields on the table. This would be helpful if someone was looking for sightings of a certain length, or just to find sightings with common descriptions. Both of these would be more difficult to implement, since the data is not as uniform. For example, some of the sightings have exact durations listed (6 minutes), while others are less precise (dawn until dusk). 

2. Having a "state" column does not make a lot of sense when another column is labled "country". There a few sightings in Canada. It would be helpful to update this filter to be called "Enter State/Province". 
