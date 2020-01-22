## Leaflet

### Side by side
Creating a new Leaflet Control for comparing two layers and display a GeoJSON in map

Usage
```js
L.control.sideBySide(layer01, layer02).addTo(map);
```

To include the plugin, just use leaflet-heat.js from the plugins folder:
```html
<script src="leaflet-side-by-side.js"></script>
```
### Heat Map

Usage
```js
L.control.sideBySide(layer01, layer02).addTo(map);
```

To include the plugin, just use leaflet-heat.js from the plugins folder:
```html
var heat = L.heatLayer([
	[50.5, 30.5, 0.2], // lat, lng, intensity
	[50.6, 30.4, 0.5],
	...
]
```



### Target
Implements a target on the map  
[demo](https://codepen.io/monteiroluana/pen/gObqbMg)

#### Links references
https://leafletjs.com/reference-1.6.0.html  
https://github.com/digidem/leaflet-side-by-side  
https://github.com/tbrugz/geodata-br/blob/master/geojson/geojs-53-mun.json  
https://scihub.copernicus.eu/dhus/#/home
https://github.com/Leaflet/Leaflet.heat
