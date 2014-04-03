python-geocode
==============

Python module and command-line tool to get location coordinates from address using Google Maps API

## Requirements
- Requests (pip install requests)
- Google Maps API Key (https://developers.google.com/maps/documentation/geocoding/)


## Usage (Module)
```
>>> from geocode import Geocoder
>>> geo = Geocoder('MY_API_KEY')
>>> geo.findCoordinates('piazza risorgimento 12 milano')
(45.4673798, 9.211271499999999, u'Piazza Risorgimento, 12, 20129 Milan, Italy')
```

## Usage (Command line)
```
python geocode.py MY_API_KEY "piazza risorgimento 12 milano"
Latitude: 45.467380
Longitude: 9.211271
Full Address: Piazza Risorgimento, 12, 20129 Milan, Italy
```
