# MAPA-DE-QUITO
MAPA DE QUITO CON DIFERENTES COORDENADAS
var mymap = L.map ('mapid'). setView ([- 0.225219, -78.5248], 13);

L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
	maxZoom: 18,
	attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, ' +
		'<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
		'Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
	id: 'mapbox/streets-v11',
	tileSize: 512,
	zoomOffset: -1
}).addTo(mymap);



var institutoIcon = L.icon({
    iconUrl: 'instituto.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.224962, -78.516919], {icon: institutoIcon}).addTo(mymap);

var damianIcon = L.icon({
    iconUrl: 'damian.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.297729, -78.535831], {icon: damianIcon}).addTo(mymap);

var molinaIcon = L.icon({
    iconUrl: 'molina.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.108161, -78.525267], {icon: molinaIcon}).addTo(mymap);

var santillanIcon = L.icon({
    iconUrl: 'santillan.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.2718950, -78.5677830], {icon: santillanIcon}).addTo(mymap);

var salazarIcon = L.icon({
    iconUrl: 'salazar.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.298549, -78.526138], {icon: salazarIcon}).addTo(mymap);

var defazIcon = L.icon({
    iconUrl: 'defaz.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.2376814, -78.4803202], {icon: defazIcon}).addTo(mymap);

var ortegaIcon = L.icon({
    iconUrl: 'ortega.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.2829487, -78.5415982], {icon: ortegaIcon}).addTo(mymap);

var perezIcon = L.icon({
    iconUrl: 'perez.png',
    iconSize:     [38, 95], 
    shadowSize:   [50, 64], 
    iconAnchor:   [22, 94], 
    shadowAnchor: [4, 62], 
    popupAnchor:  [-3, -76] 
});
var marker = L.marker([-0.273612, -78.538286], {icon: perezIcon}).addTo(mymap);


L.polyline([
	[-0.273612, -78.538286],
	[-0.224920, -78.516932],
]).addTo(mymap);

L.polyline([
	[-0.297729, -78.535831],
	[-0.224920, -78.516932],
]).addTo(mymap);

L.polyline([
	[-0.108161, -78.525267],
	[-0.224920, -78.516932],
]).addTo(mymap);

L.polyline([
	[-0.2718950, -78.5677830],
	[-0.224920, -78.516932],
]).addTo(mymap);

L.polyline([
	[-0.298549, -78.526138],
	[-0.224920, -78.516932],
]).addTo(mymap);

L.polyline([
	[-0.2376814, -78.4803202],
	[-0.224920, -78.516932],
]).addTo(mymap);

L.polyline([
	[-0.2829487, -78.5415982],
	[-0.224920, -78.516932],
