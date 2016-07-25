---
layout: page
title: Mapa
permalink: /mapa/
published: true
---

Estamos trabajando en la confección de un mapa colaborativo sobre accesibilidad y discapacidad en Zaragoza. Puedes leer acerca de las particularidades en [este enlace](/about#acerca-del-mapa), o si lo prefieres,  mientras tanto puedes ver estos mapas provisionales:

## Mapa de discapacidad visual

<iframe width="100%" height="520" frameborder="0" src="https://ccamara.carto.com/viz/472c495c-6238-4fb5-851e-93b844bc647c/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Este mapa consta de 4 capas:

1. `Semáforos acústicos` muestra información de los cruces de peatones respecto a la existencia o no de semáforos acústicos. También se incluyen aquellos pasos de peatones que tienen semáforos pero no se especifica si son acústicos o no.
1. `Pavimento táctil` muestra información sobre los cruces de peatones respecto a la existencia o no de pavimento táctil. También se incluyen aquellos pavimentos rugosos que, sin ser específicos para ese fin, pueden ayudar a personas con discapacidad visual (ejemplo: pavimentos rugosos con fines ornamentales, cambios de pavimento...) así como cruces de de peatones sin información al respecto.
1. `Pavimento táctil lineal` muestra aquellas calles que tienen un pavimento táctil longitudinal.
1. `Equipamientos y comercios`

## Mapa de discapacidad motriz

<iframe width="100%" height="520" frameborder="0" src="https://ccamara.carto.com/viz/a11856af-f34f-4862-9607-0486ac106fa6/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Este mapa consta de tres capas:

1. `Silla de ruedas (cruces)` refleja la accesibilidad en silla de ruedas en pasos de peatones en función de sus bordillos. También se han incorporado cruces de peatones existentes pero de los que no se dispone de información al respecto;
1. `Silla de ruedas (calles)` muestra información sobre la accesibilidad en silla de ruedas en calles en función de su anchura, existencia o no de obstáculos, pendientes...;
1. `Comercios y equipamientos` muestra información de comercios y equipamiento que cuentan con información de accesibilidad en silla de ruedas. La accesibilidad puede ser total (sí), parcial o inaccesible (no).
1. `Rugosidad del pavimento` muestra información sobre la calidad del pavimento desde el punto de vista de facilitar o dificultar la movilidad en silla de ruedas. Más información sobre el criterio utilizado [en esta wiki de OSM (en inglés)](http://wiki.openstreetmap.org/wiki/Key:smoothness#Smoothnessh)

## Recogida de datos en tiempo real:

<iframe src="http://overpass-turbo.eu/map.html?Q=%2F*%0AThis%20has%20been%20generated%20by%20the%20overpass-turbo%20wizard.%0AThe%20original%20search%20was%3A%0A%E2%80%9Cnote%3D%22%23Zaccesibilidad%22%E2%80%9D%0A*%2F%0A[out%3Ajson][timeout%3A25]%3B%0A%2F%2F%20gather%20results%0A%28%0A%20%20%2F%2F%20query%20part%20for%3A%20%E2%80%9Cnote%3D%22%23Zaccesibilidad%22%E2%80%9D%0A%20%20node[%22note%22%3D%22%23Zaccesibilidad%22]%2841.62371955114677%2C-0.9344387054443359%2C41.68143807852198%2C-0.8141040802001953%29%3B%0A%20%20way[%22note%22%3D%22%23Zaccesibilidad%22]%2841.62371955114677%2C-0.9344387054443359%2C41.68143807852198%2C-0.8141040802001953%29%3B%0A%20%20relation[%22note%22%3D%22%23Zaccesibilidad%22]%2841.62371955114677%2C-0.9344387054443359%2C41.68143807852198%2C-0.8141040802001953%29%3B%0A%29%3B%0A%2F%2F%20print%20results%0Aout%20body%3B%0A%3E%3B%0Aout%20skel%20qt%3B" width="100%" height="400" frameborder="0">
  <p>Your browser does not support iframes.</p>
</iframe>
