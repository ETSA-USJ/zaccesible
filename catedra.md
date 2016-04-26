---
layout: page
title: Cátedra Bantierra-Fundación Adecco
permalink: /catedra/
published: true
---
La Cátedra Bantierra-Fundación Adecco de la [Escuela Técnica de Arquitectura](http://etsa.usj.es) de la [Universidad San Jorge](http://usj.es) es una unidad de investigación-acción formada por profesores e investigadores, alumnos y egresados de la ETSA-USJ con el objetivo de trabajar e investigar sobre aspectos relativos a la integración de un colectivo desfavorecido como es el de los discapacitados, y que actualmente cuenta ya con cinco ediciones.

## Breve historia de la Cátedra

En el curso 2010-11, la [Escuela Técnica de Arquitectura](http://etsa.usj.es) y la Fundación Adecco, junto con la Empresa Arcelor Mittal, establecieron un convenio  de colaboración y crearon una cátedra, bajo la dirección de Santiago Carroquino, destinada a generar unidades de diagnóstico sobre movilidad, fundamentadas en en la accesibilidad física en edificios y espacios públicos.

Gracias a esa primera y exitosa experiencia, y tras la incorporación de Bantierra junto la Fundación Adecco, al curso siguiente la cátedra pasa a llamarse *Cátedra Bantierra-Fundación Adecco* y se inicia un segundo ciclo bajo la dirección de Ángel Comeras. Durante los cuatro cursos siguientes, la cátedra estará orientada a trabajar aspectos relativos a la discapacidad intelectual relacionados con la identificación e integración a través de proyectos de aprendizaje-servicio entre alumnos de la ETSA y residentes, con discapacidad intelectual, de los "hogares CEDES" de la fundación homónima. Buena parte de los resultados obtenidos en este segundo ciclo pueden encontrarse en la publicación [Arquitectura y discapacidad intelectual: momentos de coincidencia](http://ediciones.usj.es/?p=847) y en numerosos congresos de innovación docente y arquitectura.

![Portada del libro Arquitectura y discapacidad intelectual: momentos de coincidencia](http://ediciones.usj.es/wp-content/uploads/2014/05/Arquitectura-y-discapacidad-Portada-600px.jpg)

En el curso 2015-16, se inicia un tercer ciclo con el proyecto *[Zaragoza Accesible](/about)*, cambiando la escala (esta vez a escala urbana) y dándole un enfoque en el que las TIC juegan un papel importante. Toda la información del proyecto está [en este enlace](/about)

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
