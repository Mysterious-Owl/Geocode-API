# Google Maps API

This code will take the name of places from where.txt and then use *forward Geocode API* to get the coordinates of that location, then the coordinates are stored in javascript file and the webpage is opened automatically, to show the pin locations on map.<br>
This is a simple use of API.

### Prerequisites

To install configparser ```pip install configparser``` or check [here](https://pypi.org/project/configparser/)<br>
Have [Google Geocode API](https://developers.google.com/maps/documentation/geocoding/overview), so use that, otherwise you can use 
[Open Cage API](https://opencagedata.com/api) (its free, 2500 requests/day).

### How to run the script

Enter the API key and service URL in config file (without qoutes) and the places to be marked in where.txt file, then run the script.

### [Web Page View](webpage.html)

### Screenshot

![Map view](/Screenshot.png)


