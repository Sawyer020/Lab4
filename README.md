# Lab4
This is a lab that showing how does the dynamic website page working and how to implement automated deployment for the website.

## HTML
This is a html using an external API endpoint to get the data of latitude and longitude to show the location of a satellites, which is "ISS" ("International Space Station"). 
To begin the coding for the html file, there are some preparation steps that need to be followed, and the those steps can be found in https://leafletjs.com/examples/quick-start/ from Leaflet(an open-source JavaScript library). Also, an API link is required: https://api.wheretheiss.at/v1/satellites/25544
After copy and paste the necessary links that import Leaflet.css and Leaflet.js , the JS code for the website can implement the functions of a basic map, which includes mouse-moving, zoom-in and zoom-out,etc. An marker is created as ISS on the map and the called method "setInterval()" is avle to refresh the data by a given time.

## CSS & Yaml(Sawyer020-patch-1)
Style sheet is created for HTML file; By using the Github Action, a new branch called Sawyer020-patch-1 is created and Create github-actions-Lab4.yml successfully.

## Automated Deployment
With the help of Hostman, a Front-end app is automatically deployed and the link is https://lab4.hostman.site/
