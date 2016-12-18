# CORS GeoJSON Viewer

A _very_ simple GeoJSON viewer that loads an url from the hash and renders it
with leaflet. The URL of the GeoJSON file must support CORS. If it doesn't you
can just proxy it through https://crossorigin.me/.

## Examples:
 * http://dschep.github.io/geojson-viewer/#https://crossorigin.me/http://eric.clst.org/wupl/Stuff/gz_2010_us_outline_20m.json
 * http://dschep.github.io/geojson-viewer/#https://raw.githubusercontent.com/johan/world.geo.json/master/countries/ALB.geo.json

## Limitations
I whipped this up just to visualize some of my own GeoJSON API endpoints so this
is super janky. Also, it requires modern browser support because I wrote ES6
out of habit and am not transpiling.
