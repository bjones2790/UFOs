# UFOs

**Overview of Project:**
This project creates an interactive data visualization of UFO sightings using plotly.js. Through a webpage and dynamic table we provided our client with a more in-depth analysis of UFO sightings by allowing them to filter for multiple criteria at the same time. Filters for the city, state, country, and shape can be applied to search through the data table and pull relevant info related to UFO sightings throughout the country.

**Results:** 
To use the database the user can type in text as suggested in the placeholder boxes. For instance, to search by specific date, the user can type in the date to see if it exists within the table. The user can also type in the city name, two letter state abbreviation, two letter country code, or shape. It is important to note that, with the exception of the date filter, all text must be typed in lower cased format in order for the results to filter/display correctly. See the below images for examples of how the filter works.

**Homepage**
<img width="953" alt="Website" src="https://user-images.githubusercontent.com/112994018/205180697-1a3cda39-231f-4890-9ccc-4359554b1348.png">


**Filtered example**
<img width="953" alt="Filter" src="https://user-images.githubusercontent.com/112994018/205180718-1858569a-5bab-4eda-abd1-dd24325437c2.png">


**Drawback**
A major drawback or limitation of the site lies in the limited ability to filter through the data unless you know what you're specifically searching for. For example, typing in a date range that doesn't exist will turn up blank results. Same goes for any other filtered text. Also any mispellings, typos or upper cased text will fail to produce results.

**Recommended Fixes**
1. To address the limitations with text formatting, one could implement a drop down menu that contains all of the values within a specific field. Another solution could be a feature that automatically populates the text once a user begins to input it. This could help resolve any issues with formatting as well, such as typing in capital letters
2. Incorporating a date range in the suggested text could also help a user avoid typing in a date that doesn't exist in the database. For instance, dates seem to range between 1/1/2010 and 1/13/2010. The suggested text in the box could read as "Enter date between 1/1/2010 and 1/13/2010"
