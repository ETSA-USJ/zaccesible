---
layout: page
title: Acerca de
permalink: /about/
published: true
---



Zaragoza Accesible es un proyecto de mapeado colaborativo de
aspectos relacionados con la discapacidad y la movilidad en Zaragoza desarrollado en el marco de la **cátedra Bantierra - Fundación Adecco** de la
[Escuela Técnica Superior de Arquitectura](http://etsa.usj.es) de la
[Universidad San Jorge](http://usj.es)

## Miembros de la Cátedra

<ul>
{% for member in site.data.members %}
  <li>
    <a href="{{ member.url }}">{{ member.name }}</a> <br>
    <i>{{ member.job }}</i></br>
  </li>
{% endfor %}
</ul>

 Cursos anteriores

 <ul>
 {% for member in site.data.members-legacy %}
   <li>
     <a href="{{ member.url }}">{{ member.name }}</a> <br>
     <i>{{ member.job }}</i></br>
   </li>
 {% endfor %}
 </ul>

## Agradecimientos

Este proyecto no sería posible sin el soporte de [Bantierra](http://www.bantierra.es/) y la [Fundación Addeco](http://www.fundacionadecco.es),  a la participación desinteresada de la comunidad [OpenStreetMap](htpp://openstretmap.org) de Zaragoza y a los miembros de Zaragoza Activa por su soporte en la consolidación de un grupo de trabajo.

* Fundación Adecco
  * Beatriz Gutiérrez
* Zaragoza Activa
  * Jose Ramon Insa
  * Mapi Gracia Galán
* Comunidad OpenStreetMap
  * Miguel Sevilla-Callejo
  * Alejandro Suárez
  * Contribuidores anónimos de [OpenStreetMap](htpp://openstretmap.org)
