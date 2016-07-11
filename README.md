# ADDRESS FINDER #

>This is a web page which could be used to find the address of any places in the  
world. This is web page is developed using maps from **Mapbox** API, **mapbox.js**  
v2.4.0 and with help of **Google Maps** API.  

## How to find address? ##
> It's simple, just move the marker to the point of which address needs to be  
found. The corresponding Longitude and Latitude is shown in a box on the bottom  
left of the page and the Address is shown in bottom right of the page.  

## How it works? ##
* Using mapbox.js API the latitude and longitude is obtained.
* Using the coordinates, the JSON file for Google Maps API for that coordinates  
 is obtained.
* From the JSON file required address is obtained.
