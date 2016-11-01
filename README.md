####Google Maps multiple Markers 
=================================

1. index.html has a **div** to show Map
2. map_script.js - javascript to draw multiple markers on Google Map
3. Link to Google Map API

>Automatically center the map fitting all markers on the screen

**NOTE**

Please put your Google console API key in index.html 
```html
<script src="https://maps.googleapis.com/maps/api/js?key=GOOGLE_API_KEYcallback=initiateMap" 
async defer></script>`
```

Get your lat, long list and pass it to var locations in map_script.js 

```javascript
var locations = [
                   [31.5546, 74.3572],
                   [34.0150, 71.5805],
                   [30.1830, 66.9987],
		                …
		                …		
                    ];
```

For more details, read this [post](http://sparkanswers.com/google-maps-multiple-markers/)

Cheers! 
