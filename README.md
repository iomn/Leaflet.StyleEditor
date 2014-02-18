Leaflet.StyleEditor
=============

The [Leaflet](http://leafletjs.com/) StyleEditor allows to edit the style of any feature drawn within Leaflet.


Usage
-----


```javascript
//Initialize the StyleEditor
var styleEditor = L.control.styleEditor({
    position: "topleft"
});
map.addControl(styleEditor);
````

It is also possible to specify different color ramps or to specify the set of markers:
```javascript
var styleEditor = L.control.styleEditor({
    position: "topleft",
    colorRamp: ['#1abc9c', '#2ecc71', '#3498db'],
    markers: ['circle-stroked', 'circle', 'square-stroked', 'square']
});
map.addControl(styleEditor);
````


Author
-----
Dennis Wilhelm, 2014