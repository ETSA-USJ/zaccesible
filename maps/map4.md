---
layout: map
title: Mapa4
permalink: /map4/
---

<script type="text/javascript" src="https://stamen-maps.a.ssl.fastly.net/js/tile.stamen.js"></script>
<script>
function start() {
        window.setTimeout(panzoom, 4000)
};
var map = new L.map('map', {
scrollWheelZoom: false
});
map.on('load', start);
map.setView([39, -82], 9);
var cdb = L.tileLayer('http://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}.png', {
                attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a> &copy; <a href="http://cartodb.com/attributions">CartoDB</a>',
                subdomains: 'abcd',
                minZoom: 0,
                maxZoom: 20,
                maxNativeZoom: 18
});
var terrain = new L.StamenTileLayer("toner");
terrain.addTo(map);
var marker1 = L.marker([39.5, -83.5]).bindPopup('This is an animated map!').addTo(map);
var delay1 = 0, 
        delay2 = 1000, 
        delay3 = 8000;
function panzoom(){
        map.panTo(marker1.getLatLng(), {animate: true, duration: 1});
        marker1.openPopup();
};
</script>