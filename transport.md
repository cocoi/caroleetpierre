---
layout: page
title: Transport
permalink: /transport/
feature-img: img/banner.gif
---
## Venir au mariage

**En train** : la gare la plus proche est Épernay (1h30 depuis Paris Gare de l'Est). 

**En avion** : les aéroports nationaux et internationaux les plus proches sont CDG et Orly. 

**En voiture** : par la route (voir ci-dessous pour le plan et les adresses).

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

## Mairie de Fontaine sur Aÿ

**Adresse** : 17 Grande Rue, 51160, Fontaine sur Aÿ, France

<img src="/img/mairie.jpg" alt="Mairie de Fontaine sur Aÿ" width="600px">

*Crédit photo : G.Garitan, CC-BY-SA 3.0, [disponible sur wikipédia](https://fr.wikipedia.org/wiki/Fontaine-sur-Ay#/media/File:Mairie_06000.JPG "Mairie de Fontaine sur Aÿ")*

La Mairie de Fontaine sur Aÿ se situe au coeur du village, à un terrain de tennis de la maison familliale du futur marié.
Le bâtiment de la mairie abritait également autrefois l'école municipale.

Fontaine sur Aÿ est un petit village réputé pour son calme et son cadre de verdure. Il est connu des promeneurs et amoureux de la nature. Il est traversé par deux rivières, la Germaine et la Livre, qui viennent se rejoindre près de la place de la Mairie.

## Domaine Miltat

**Adresse** : 6 Rue Carnot, 51530, Pierry, France

<img src="/img/domaine.png" alt="Mairie de Fontaine sur Aÿ" width="600px">

*Crédit photo : Google Street View*

Le domaine Miltat fait partie de la maison de Champagne Miltat. Il se situe au pied du vignoble d'Épernay et se compose d'un cellier et de deux gîtes.
