---
layout: page
title: The Location
permalink: /location/
menu-rank: 4
---

<style>
      #map {
			width: 300px;
			height: 200px;
			float:right
      }
</style>
<script src="https://maps.googleapis.com/maps/api/js"></script>
<script>
  function initialize() {
	var mapCanvas = document.getElementById('map');
	var mapOptions = {
	  center: new google.maps.LatLng(44.5403, -78.5463),
	  zoom: 8,
	  mapTypeId: google.maps.MapTypeId.ROADMAP
	}
	var map = new google.maps.Map(mapCanvas, mapOptions)
  }
  google.maps.event.addDomListener(window, 'load', initialize);
</script>

<div id="map"></div>
The location will be BARCELONA – Real Club Náutico de Barcelona. The harbour is located just at the very heart of the town, at walking distance from the "Barrio Gotico" the oldest district of BCN. Ramblas is also in walking distance. The area is crowded with restaurants and hotels.

## Barcelona

Barcelona is the capital city of the autonomous community of Catalonia in Spain and Spain's second most populated city. Its urban area extends beyond the administrative city limits with a population of around 4.7 million people, being the sixth-most populous urban area in the European Union and the largest metropolis on the Mediterranean Sea.

The city is one of the world's leading tourist, economic, trade fair and cultural centers, and its influence in commerce, education, entertainment, media, fashion, science, and the arts all contribute to its status as one of the world's major global cities.

Founded as a Roman city, Barcelona has a rich cultural heritage and is today an important cultural center and a major tourist destination. Particularly renowned are the architectural works of Antoni Gaudí and Lluís Domènech i Montaner, which have been designated UNESCO World Heritage Sites. The city is known for hosting the 1992 Summer Olympics and many other international sport tournaments.
