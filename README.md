This is from https://github.com/perrygeo/leaflet-simple-csv
I have just copied the files here as I wanted to play with them a little. This is not a stable release you should go to https://github.com/perrygeo/leaflet-simple-csv if you would like the real copy.


Simple Leaflet map template for putting points on a map.

<img src="https://raw.github.com/perrygeo/leaflet-simple-csv/master/img/screenshot1.png" alt="Leaflet" />

### Features
* Data is in tabular delimited-text (csv, etc.) with two required columns: `lat` and `lng`
* Points are plotted on full-screen [Leaflet](https://github.com/Leaflet/Leaflet) map
* Point markers are clustered dynamically based on zoom level.
* Clicking on a point cluster will zoom into the extent of the underlying features.
* Hovering on the point will display the name. 
* Clicking will display a popup with columns/properties displayed as an html table.
* Full text filtering with typeahead
* Completely client-side javascript with all dependencies included or linked via CDN

### Usage
Download, add your own data csv, copy the `config.js.template` to `config.js`, edit it according to your needs, then load index.html in a browser.

### Thanks to...

* [Leaflet](https://github.com/Leaflet/Leaflet)
* [Leaflet.geoCSV](https://github.com/joker-x/Leaflet.geoCSV)
* [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)
* [Twitter Boostrap](http://twitter.github.io/bootstrap/)
* [jQuery](http://jquery.com/)

