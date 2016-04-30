---
layout: post
title: Metodología
published: true
categories: blog
tags:
  - metodología
comments: true
author: César Canalís
---
![diseñoaccesibele.es.jpg]({{site.baseurl}}/media/diseñoaccesibele.es.jpg)

El objetivo de *Zaragoza Accesible* es mapear las barreras arquitectónicas de la ciudad de Zaragoza con el fin facilitar el día a día de sus habitantes con discapacidad.
Para ello se utilizará [Open Street Map](http://osm.org) como herramienta de trabajo con el fin de que quede en una base de datos abiertos para que todo el mundo tenga acceso tanto para información como para elaborar proyectos futuros.

Aún estando toda la información necesaria en [la wiki de OSM](http://wiki.openstreetmap.org/wiki/Main_Page) vamos a exponer de manera sintética y resumida los aspectos principales con los que trabajar en **Open Street Map**  en el ámbito de la accesiblidad: Primero veremos las principales discapacidades con las que vamos a trabajar, para posteriormente hacer una aplicación práctica de los *tags* que debemos utilizar en OpenStreetMap.


* TOC will be output here
{:toc}

## Discapacidades

Para el proyecto hemos tenido en cuenta dos grandes tipos de discapacidades: disminuidos visuales y ceguera por un lado y disminuidos físicos con movilidad reducida.

### Disminuidos visuales y ceguera

**1.Qué vamos a mapear y cómo lo vamos a hacer.**

Hemos identificado los siguientes items a mapear, con sus correspondientes equivalencias de *tags* (etiquetas) de [OpenStreetMap](http://openstreetmap.org):

  * **Pavimento táctil**:    `Tactile_paving=yes/no/incorrect`
  * **Mapas en relieve**:  `Information=Tactile_Map`
  * **Escritura táctil**: `Information=Braille`
  * **Sonidos (descripciones sonoras)**: `Acoustic=Voice_Description`
  * **Semáforos con sonido**: `Traffic_signals:sound= yes/no`

**2. Lugares y elementos de interés**

* Paradas de transporte público.
* Pasos de peatones.
* Ascensores con *Braille* o letras en relieve.
* Lugares de encuentro u organizaciones para discapacitados visuales.
* Ópticas, doctores y departamenteos sanitarios para discapacitados visuales.
* Puntos que ofrecen productos especiales para los discapacitados visuales.
* Lugares que puedan ofrecer acomodación como:
 * Cines con narración.
 * Museos con narración.
 * Lugares turísticos con guías MP3.

### Disminuidos físicos con movilidad reducida

**1.Qué vamos a mapear y cómo lo vamos a hacer.**

Hemos identificado los siguientes items a mapear, con sus correspondientes equivalencias de *tags* (etiquetas) de [OpenStreetMap](http://openstreetmap.org):

* **Accesible en silla de ruedas**: `Wheelchair=yes/no/limited`
* **Tipo de bordillo**: `Kerb=Lowered/Raised/Flush`
* **Rampa para silla de ruedas**: `Ramp:Wheelchair=yes/no`
  * **Pasamanos**: `Handrail=yes/no`
  * **Situación del pasamanos**: `Handrail=right/center/left`
* **Escaleras**: `Highway=steps`
    * **Número de escalones**: `Step_count= número de escalones`
    * **Anchura de las escaleras**: `Width= anchura`
* **Parking para discapacitados**: `Amenity= Parking` / `Capacity:Disabled=yes/no`
* **Parques adaptados**: `Leisure=Prayground`/ `Wheelchair= yes/no`

**2. Lugares y elementos de interés.**

 * Paradas de transporte público.
 * Pasos de peatones.
 * Ascensores
 * Lugares de encuentro u organizaciones para discapacitados físicos.
 * Departamenteos sanitarios para discapacitados físicos.
 * Edificios públicos accesibles.
 * Gasolineras con servicio.
 * Parques adaptados.


## Aplicación práctica: mapeado accesible

El objetivo del trabajo es identificar las barreras arquitectónicas de la ciudad de Zaragoza, para mapear en *Open Street Map* identificaremos los siguientes elementos:

* **Cruces de peatones**  ``highway=crossing``
 * Si está regulado por **semáforos**  `crossing=traffic_signals`
 * Si está regulado por **señales** `crossing=uncontrolled`
 * **Señal acústica** en los semáforos si/no `traffic_signals_sound=yes/no`
 * **Pavimento táctil** si/no/incorrecto `Tactile_paving=yes/no/incorrect`
 * **Tipo de bordillo** a ras/rebajado/elevado `Kerb_flush/lowered/raised`
 * **Accesible en silla de ruedas** si/no `Wheelchair_yes/no`
 * **Accesible en bicicleta** si/no `Bicycle_yes/no`
 * **Tipo de fuente de información** según hayamos sacado la información en trabajo de campo o mediante otras fuentes de información `Source_survey` (ejemplo para cuando la hemos obtenido, por ejemplo, en trabajo de campo)
 * **Observaciones** para poner cualquier tipo de información adicional que se crea de interés se utilizará la etiqueta "note". En este caso como es dentro del proyecto de Zaccesibilidad se puede optar por poner  `note=#Zaccesibilidad`
 * **Tipo de cruce de peatones**
    * *Open Street Map* establece una categorización de los cruces de peatones según tengan o no semáforos o permitan el paso de bicicletas.
    * Si **tiene semáforos** y **permite el paso de bicicletas** `Crossing_ref=Toucan`
    * Si **tiene semáforos** y **no permite el paso de bicicletas** `Crossing_ref=Pelican`
    * Si **no tiene semáforos** y **permite el paso de bicicletas** `Crossing_ref=Tiger`
    * Si **no tiene semáforos** y **no permite el paso de bicicletas** `Crossing_ref=zebra`


* **Calles Peatonales** `Highway=pedestrian`
 * **Tipo de bordillo** a ras/rebajado/elevado `Kerb_flush/lowered/raised`
 * **Nombre de la vía** `Name=____`
 * **Anchura** `Width=____`
 * **Pavimento** Baldosas/Adoquines planos/Adoquines/Hormigón/Asfalto `Surface=Sett/Paving_stones/Cobblestone/Concrete/Asphalt`
 * **Pavimento táctil** si/no/incorrecto `Tactile_paving=yes/no/incorrect`
 * **Accesible en silla de ruedas** si/no `Wheelchair_yes/no`
 * **Accesible en bicicleta** si/no `Bicycle_yes/no`
 * **Tipo de fuente de información** según hayamos sacado la información en trabajo de campo o mediante otras fuentes de información `Source_survey` (ejemplo para cuando la hemos obtenido, por ejemplo, en trabajo de campo)
  * **Observaciones** para poner cualquier tipo de información adicional que se crea de interés se utilizará la etiqueta "note". En este caso como es dentro del proyecto de Zaccesibilidad se puede optar por poner  `note=#Zaccesibilidad`

* **Calles con vial rodado** `Highway_tertiary`
  * **Pavimento** Baldosas/Adoquines planos/Adoquines/Hormigón/Asfalto `Surface=Sett/Paving_stones/Cobblestone/Concrete/Asphalt`
  * **Accesible en silla de ruedas** si/no `Wheelchair_yes/no`
  * **Accesible en bicicleta** si/no `Bicycle_yes/no`
  * **Aceras** a ambos lados/ a la derecha/ a la izquierda `sidewalk=both/right/left`
  * **Anchura** `Width=____`
  * **Tipo de fuente de información** según hayamos sacado la información en trabajo de campo o mediante otras fuentes de información `Source_survey` (ejemplo para cuando la hemos obtenido, por ejemplo, en trabajo de campo)
  * **Observaciones** para poner cualquier tipo de información adicional que se crea de interés se utilizará la etiqueta "note". En este caso como es dentro del proyecto de Zaccesibilidad se puede optar por poner  `note=#Zaccesibilidad`

* **Escaleras** `Highway=steps`
  * **Número de escalones**: `Step_count= número de escalones`
  * **Anchura de las escaleras**: `Width= anchura`
  * **Rampa para silla de ruedas**: `Ramp:Wheelchair=yes/no`
  * **Pasamanos**: `Handrail=yes/no`
   * **Situación del pasamanos**: `Handrail=right/center/left`

## Consideraciones finales

* Si  se van a añadir puntos, es mejor añadir edificios y poner el punto justo en la entrada. Tratar de no añadir puntos estimados.
* Si se ponen números de portales, poner exactamente el nodo de entrada en el portal.
* Si se mapean calles por primera vez, añadir carriles de estacionamiento, carriles bici y aceras asi como número y ancho de los mismos.
* La exactitud  de los elementos a la hora de mapear es muy **importante**. Si no se sabe seguro la situación de un elemento añadir `FIXME:Position estimated` a la entrada, para que la siguiente persona ponga las coordenadas de manera correcta.
