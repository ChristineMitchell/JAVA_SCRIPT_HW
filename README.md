# JAVA_SCRIPT_HW_UFO Sightings!

## Overview 
Creating webpages is like the icing on the cake for data analysts who want to present the data that they have worked so hard to extract, clean, store, and analyze. So, not only does it make sense to learn HTML, CSS, and Bootstrap to allow a large population of users to visualize their data, but it the cherry on top to make the data dynamic where a user can interact with the data. The latter can be achieved by incorporating the complimentary front-end development language, JavaScript, into an HTML page along with the d3.js library.

![modTop](https://user-images.githubusercontent.com/82008319/126075429-3b44278d-70ba-418d-840e-158889aea2dd.JPG)

So, my assignment was to follow Dana’s experience with creating a fun interactive webpage showcasing UFO sightings in a dynamic data table where the table updated based on the date the user inputs with the click of a ("Filter Table") button. See below:

![modTable](https://user-images.githubusercontent.com/82008319/126075437-9346a3c9-bd16-422c-bd25-a2d560ca4ccb.JPG)

Dana was interested in enriching the user’s experience further to slice the data in different ways for a more in-depth analysis. Following Dana’s code, I simultaneously built the table using the data stored in the JavaScript array. It gave me the foundation to enhance the table further. Not only does it return the sightings by a particular date, but it layers additional filters such as the city, state, country, and shape.  The table simply updates as the user enters their interested criteria with no button necessary. Pretty slick! 

![cTable](https://user-images.githubusercontent.com/82008319/126075460-888568db-05c3-4a53-9bd3-74837d5fee08.JPG)

## Result
As a result, the user can not only parse UFO sighting by date, but they can also input a specific state and see how many sightings were found on a particular day in that state without even pushing a button. The user can also drill down further and include a city and a shape. The user can even backspace to clear the date and find the number of sightings for just a particular shape in that city for the entire date range, or back up some more by clearing the city and state to find the number of sightings of the chosen shape across the country for the entire date range. In my playful exploration of the data, I was super excited to find that there was one sighting in my hometown of <a href=https://www.cityoflompoc.com/>Lompoc, CA.</a> 

![srchCity](https://user-images.githubusercontent.com/82008319/126075477-3fe537a4-d0f0-4485-ab04-a3ff55941c6a.JPG)

Let me demonstrate how to use the table. A user would simply input the fields they are interested in filtering and press enter after each entry. If they want to clear a particular field, they need to backspace to the beginning of the field. It is imperative to enter the filter criteria to match the data in the table because it is case sensitive. I included a sample placeholder to guide the user to enter the data properly.

![cTableTips](https://user-images.githubusercontent.com/82008319/126075500-830f3fee-882f-406d-b2ac-bc4094e6ddce.JPG)

## Summary
A few drawbacks are that I did not set up the filters for a date range, as well as a data reset button. At this point, a user would need to go to the Navigation Bar and select the UFO Sightings link to refresh the table. Lastly, the user must input the data precisely as the data is presented in the table. For example, the input is case sensitive, and the user must type in “ca”, not even “CA”, for the state of California. As well, the input field does not limit the number of characters you can type into the input field. Ideally the code would account for this by restricting the number of characters entered as well as make it so that it is not case sensitive. Perhaps, a drop-down menu would strengthen the user experience. I would need to research this more. Anyways, as I continue to build on my skills, I would love to enhance the site to address those interactive opportunities, as well as incorporate some of the items on my development wish list:
1)	I would like to move away from a small static dataset, it would be ideal to find a large global dataset for a global analysis. Considering it would be unlikely to find a world-wide data source, I would like to explore the data and its validity provided by <a href=http://www.nuforc.org/index.html>The National UFO Reporting Center</a> for sightings in the United States. While their site no longer provides a working API, at least they provide monthly reports approximately 60 days old. 
2)	I would like to improve the data analytic experience by using the Plotly library to create charts that complement the data table as the user interacts with the input filters. The charts would help the user identify trends. For example, there is a cluster of sightings reported on January 1, 2010, in California but that is hard to recognize without a chart. As well, there are more reports describing the shape to be a light or triangle rather than a circle or disk and that would be easier to identify with a chart. 
3)	Another fun one, would be to find a library to create a U.S. heat map of the UFO sightings. The size and color of the circle could be similar to a bubble chart where it can be indicative to the number of sightings reported in a particular area.

![UFOCartoon](https://user-images.githubusercontent.com/82008319/126075538-aa5effee-b786-419c-b032-a3e06e0828d6.png)
<p align="center">
  (cartoon stock - compliments to https://www.pngaaa.com)
</p>



