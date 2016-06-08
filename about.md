---
layout: page
title: Sobre el proyecto
permalink: /about/
published: true
---

**Zaragoza Accesible** es un proyecto de mapeado colaborativo de
aspectos relacionados con la discapacidad y la movilidad en Zaragoza desarrollado en el marco de la **[cátedra Bantierra - Fundación Adecco](/catedra)** de la
[Escuela Técnica Superior de Arquitectura](http://etsa.usj.es) de la
[Universidad San Jorge](http://usj.es) y desarrollado gracias a la colaboración desinteresada de [Zaragoza Activa](http://www.zaragoza.es/ciudad/sectores/activa/) y la comunidad de OpenStreetMap ([ver agradecimientos](#agradecimientos)).

**Tabla de contenidos**

* TOC will be output here
{:toc}

## Justificación

Para garantizar una correcta inserción laboral de los colectivos afectados con algún tipo de discapacidad es necesario garantizar que dichas personas sean capaces de desplazarse de forma autónoma a sus puestos de trabajo, una tarea que a menudo no resulta trivial debido a que la morfología de las ciudades y el tipo y disposición de mobiliario urbano e infraestructuras a menudo no han tenido en mente a estos usuarios. Así pues, elementos aparentemente tan inocuos como el tipo de pavimento, bordillos o semáforos pueden llegar a suponer, en algunos casos, auténticas barreras arquitectónicas y urbanísticas que dificultan o impiden la movilidad de estos colectivos.

Por otra parte, el sector de las TIC, y más concretamente las aplicaciones y servicios que usan una componente geoespacial ha experimentado un auge considerable y se encuentra en la mayoría de facetas de la vida: desde la planificación de rutas y desplazamientos, hasta la forma en que practicamos deporte o compartimos fotografías, pasando por la elección de hoteles, restaurantes, o destinos turísticos. Sin embargo, una vez más, se ha dado la espalda a un sector, como el de la discapacidad, a pesar de que el uso de estas tecnologías en su día a día permitiría dotarles de una mayor autonomía y, por tanto, una mejor integración y calidad de vida.

Por este motivo, en el marco de colaboración de la Cátedra BANTIERRA-FUNDACIÓN ADECCO, se plantea el proyecto **Zaragoza Accesible** – *#Zaccesible* con la finalidad de realizar un mapa online y con datos abiertos, que sirva por un lado para realizar un primer diagnóstico del estado la accesibilidad desde el punto de vista de la movilidad de Zaragoza y por otro, para sentar las bases para la creación de futuras aplicaciones y servicios basados en los datos recopilados que sirvan para mejorar la integración de los colectivos con discapacidad.

## Objetivos

Durante el curso 2015-16 se plantea una primera fase de **prueba piloto** del proyecto con el objetivo de sentar las bases metodológicas y tecnológicas para la creación posterior de un mapa online, colaborativo y con datos abiertos de la ciudad de Zaragoza. Dicho mapa servirá a dos propósitos distintos: el primero y más inmediato es proporcionar un diagnóstico de la autonomía e independencia de las personas discapacitadas en su movilidad diaria en el espacio urbano, concretamente en la ciudad de Zaragoza; el segundo, de más recorrido, consiste en la creación posterior de servicios y aplicaciones (tanto por parte de la cátedra como por terceros) basados en los datos recopilados en el estudio con la finalidad de ayudar, a través de las TIC, a la movilidad de las personas con discpacidad y, en última instancia, mejorar su integración en el mundo laboral.

A nivel particular se establecen los siguientes objetivos:

1. Elaboración de un **protocolo** que sirva para la toma de datos relacionados con la discapacidad y la movilidad para la confección posterior de un mapa.
1. Elaboración de un **prototipo del mapa** funcional y con las características que se detallan [a continuación](#acerca-del-mapa). Debido a limitaciones de tiempo y recursos, el prototipo estará limitado a determinados barrios de Zaragoza (El Gancho y Actur).
1. Puesta a prueba y consolidación de la **infraestructura tecnológica** necesaria para la publicación del mapa y la posterior utilización de los datos recopilados en el trabajo de campo.
1. Establecer **sinergias** con entidades y personas interesadas en participar en un proyecto de integración de un colectivo desfavorecido mediante la utilización de TICs y basada en el conocimiento local de la ciudad a través de la creación de una **red de colaboración**.

## Acerca del mapa

El mapa en el que estamos trabajando tiene las siguientes características:

1. **Online:** El mapa será accesible a través de la web, lo cual permite interacciones que no son posibles en papel y permite que se comparta y se inserte en otras webs, mejorando por tanto la difusión y visibilidad del proyecto.
1. **Basado en observaciones**: los datos reflejados en el mapa provienen de un minucioso y sistemático estudio de campo realizado por el [equipo del proyecto](#miembros-del-proyecto) y por voluntarios de OpenStreetMap, lo cual permite disponer de datos actualizados y que no constan en ningún otro mapa o servicio (lo cual exigiría disponer de una licencia para poder utilizarlos).
1. **Colaborativo**: dada la naturaleza del proyecto, es necesario darle un enfoque colaborativo en el que cualquier persona interesada, y con unos mínimos conocimientos tecnológicos y del entorno local, pueda añadir datos al mapa. Esto no solo permite aspirar a poder mapear una ciudad entera (algo impensable para un equipo pequeño de investigadores) sino que permite disponer de datos actualizados constantemente.
1. **Datos abiertos** ([Open Data](https://es.wikipedia.org/wiki/Datos_abiertos)): todos los datos recopilados en el estudio de campo (así como todos los que se encuentran en OpenStreetMap) son abiertos, es decir, cualquier persona puede utilizar los datos recopilados en el estudio para cualquier fin, siempre que se cite la fuente.
1. **OpenStreetMap** ([OSM](http://openstreetmap.org)) es el mapa colaborativo más importante a nivel mundial. Buena parte del proyecto *Zaragoza Accesible* utiliza la infraestructura, datos y comunidad de OSM para almacenar, gestionar y visualizar los datos recopilados.
1. **Agnóstico/Neutral**: a diferencia de actividades similares que se centran en identificar barreras arquitectónicas (algo eminentemente negativo), el enfoque de Zaragoza Accesible es el de mapear la accesibilidad a partir del análisis de unas categorías predeterminadas lo cual ofrece una mirada agnóstica y objetiva del estado actual de la movilidad accesible.

## Miembros del proyecto

<ul>
{% for member in site.data.members %}
  <li>
    <a href="{{ member.url }}">{{ member.name }}</a> <br>
    <i>{{ member.job }}</i></br>
  </li>
{% endfor %}
</ul>

## Agradecimientos

Este proyecto no sería posible sin el soporte de [Bantierra](http://www.bantierra.es/) y la [Fundación Addeco](http://www.fundacionadecco.es),  a la participación desinteresada de la comunidad [OpenStreetMap](htpp://openstretmap.org) de Zaragoza y a los miembros de [Zaragoza Activa](http://www.zaragoza.es/ciudad/sectores/activa/) por su soporte en la consolidación del grupo de trabajo *Mapeado colaborativo*.

* Fundación Adecco
  * Beatriz Gutiérrez
* Zaragoza Activa
  * Jose Ramon Insa
  * Mapi Gracia Galán
* Comunidad OpenStreetMap
  * Miguel Sevilla-Callejo
  * Alejandro Suárez
  * Miembros del grupo "[Mapeado Colaborativo](/blog/2016/04/07/mapeado-colaborativo-zac.html)"
  * Contribuidores anónimos de [OpenStreetMap](htpp://openstretmap.org)
