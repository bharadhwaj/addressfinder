# ADDRESS FINDER #

>This is a web page which could be used to find the address of any places in the  
world. This is web page is developed using maps from **Mapbox** API, **mapbox.js**  
v2.4.0 and with help of **Google Maps** API.  

## How to use? ##
> After making a copy of the repo, open the file **addressfinder.html** and add  
your Mapbox Access token in line 48 and your Google Maps API key in line 85.  
> Here is, [How to get a Google Key](https://developers.google.com/maps/documentation/javascript/get-api-key "Google Maps API Key") and [Creating a Mapbox Access token.](https://www.mapbox.com/help/create-api-access-token/ "Mapbox Access token")



## How to find address? ##
> It's simple, just move the marker to the point of which address needs to be  
found. The corresponding Longitude and Latitude is shown in a box on the bottom  
left of the page and the Address is shown in bottom right of the page.  



## How it works? ##
* Using mapbox.js API the latitude and longitude is obtained.
* Using the coordinates, the JSON file for Google Maps API for that coordinates  
 is obtained.
* If address is found using Google Maps API, it is displayed.
* If Google Maps API can't detect any address, it passes the coordinates to  
Mapbox API for searching address.
* If address is found using Mapbox API, it is displayed.
* If both APIs can't find address, then 'No address found for this location!'  
is displayed.

## Standard Examples for each test cases #
* In order to obtain address from Google Maps API, see the address when page  
is loaded.
* To see address obtained through Mapbox API, drag the marker near to Leh,  
Jammu & Kashmir, India.
* To see 'No address found for this location!', drag the marker to any oceans.
