---
layout: page_en
title: Transport
permalink: /en/transport/
feature-img: img/banner.gif
---
## Getting there

**By train**: the nearest train station is Epernay (1h30 from Paris Gare de l'Est).

**By plane**: the nearest national and international airports are CDG and Orly near Paris (1h30 by car).

**By car**: take the road (see below for map and addresses).

## Plan

<div id='map' style='width: 800px; height: 600px;'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1IjoicHp3c2siLCJhIjoiY2l5c3dmZjZ0MDAxMDJxbzNsYTVicndtbyJ9.9Oi8j_rHrQn_-3ZQ8Psr2g';
var map = new mapboxgl.Map({
    container: 'map',
    style: 'mapbox://styles/pzwsk/ciyswgzbd001s2sudemejhmpg'
});
map.addControl(new mapboxgl.NavigationControl());

map.on('load', function () {

    map.addLayer({
        "id": "points",
        "type": "symbol",
        "source": {
            "type": "geojson",
            "data": {
                "type": "FeatureCollection",
                "features": [{
                    "type": "Feature",
                    "geometry": {
                        "type": "Point",
                        "coordinates": [3.9387011999999686,49.0206378]
                    },
                    "properties": {
                        "title": "Domaine Miltat",
                        "icon" : "marker"
                    }
                },{
                    "type": "Feature",
                    "geometry": {
                        "type": "Point",
                        "coordinates": [4.074055,49.082089]
                    },
                    "properties": {
                        "title": "Mairie de Fontaine sur Aÿ",
                        "icon" : "marker"
                    }
                }]
            }
        },
        "layout": {
            "icon-image": "{icon}-15",
            "text-field": "{title}",
            "text-font": ["Open Sans Semibold", "Arial Unicode MS Bold"],
            "text-offset": [0, 0.6],
            "text-anchor": "top"
        }
    });
});
</script>

## Fontaine sur Aÿ town hall

**Address**: 17 Grande Rue, 51160, Fontaine sur Aÿ, France

<img src="/img/domaine.png" alt="Mairie de Fontaine sur Aÿ" width="600px">

* Photo credit: G.Garitan, CC-BY-SA 3.0, [available on wikipedia] (https://fr.wikipedia.org/wiki/Fontaine-sur-Ay#/media/File:Mairie_06000.JPG "Mairie de Fontaine sur Aÿ") *

The town hall of Fontaine sur Aÿ is located in the heart of the village, close to the family house of the future bridegroom. The town hall building also once housed the municipal school.

Fontaine sur Aÿ is a small village renowned for its quiet and green surroundings. It is known to walkers and nature lovers. It is crossed by two rivers, the Germaine and the Livre, which come to meet near the place of the Town hall.

## Domaine Miltat

**Address**: 6 Rue Carnot, 51530, Pierry, France

<img src="/img/domaine.png" alt="Mairie de Fontaine sur Aÿ" width="600px">

*Photo Credit: Google Street View*

The estate Miltat is part of the house of Champagne Miltat. It is located by the vineyard of Epernay and consists of a big celebration room and two lodgings.