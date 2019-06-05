#Holiday Planner API

This project is an all in one app that allows you to find hotels, eateries and sightseeing places around the island.

#UX

The interface is a clean single page interface with multiple categories on top followed by the map at the bottom which displays the markers based on the category chosen by the user.

#Features

The buttons allow you to display information markers around the map, right click on an area to repopulate markers for that area. Due to google API free limitations, the map only allows the
display of up to 20 at any given time, hence the right click function is necessary to find all possible markers around the island.
Clicking on the markers will give some details on the landmark such as the title, picture and ratings. Pricing is mainly applicable to eateries and hotels and as such there may not be information for certain
marker categories.

#Frameworks Used

The project uses JQuery to simplify DOM manipulation and Javasript to define functions and do callbacks to enable the map to respond accordingly based on user action.
Basic HTML and CSS is used to make the site more visually appealing.

#Testing

I did an LMS example for Jasmine Testing, not entirely sure how to integrate this in the API project, but for this project testing I did them
manually as there were only a few functions to test, clicking on each button and checking to ensure they refresh and correspond accordingly to the category. The right-click function on google maps was also
tested similarly, but this time to ensure the right-click corresponds to the category that is being displayed on the map. Do note that if the map fails to display (map is located at the bottom of the page), try to refresh
again (if screen at the bottom is white), if it doesn't work the key might have expired (displays an exclaimation mark in the center of where the map is suppose to be), it has happened to me before, and so will need to regenerate a new key for the map to work again.

#Deployment

For deployment I used Github to deploy, To run code just extract all the files onto a coding text editor and run the index.html file or use the repo link provided-> https://markwei92.github.io/api-assignment/ 

#Credits

#Content

Markers and display information on map provided by Google Maps API

#Media

The photos used in this site were obtained from:
-https://singapore.concordehotelsresorts.com/wp-content/uploads/2018/03/Concorde-Hotel-Singapore-Standard-Room.jpg
-https://www.furama.com/citycentre/
-https://thehoneycombers.com/singapore/halal-buffets-in-singapore-awesome-dining-spots-for-free-flow-halal-food/

#Acknowledgements
I received inspiration for this project from brainstorming the usage of markers and landmark on Google Maps API.