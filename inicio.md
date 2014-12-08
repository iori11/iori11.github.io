---
layout: page
title: Inicio
permalink: /
---

<h1 class="page-heading">Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>


El Software Libre implica que los usuarios tienen las cuatro libertades esenciales: (0) ejecutar el programa, (1) estudiar y modificar el código fuente del programa, (2) redistribuir copias exactas y (3) distribuir versiones modificadas.

LA ACTITUD DEL HACKER  

Los hackers resuelven problemas y construyen cosas, y creen en la libertad y la ayuda voluntaria mutua. Para ser aceptado como hacker, deberás comportarte como si tuvieras esta actitud en tu interior. Y para comportarte como si tuvieras esta actitud, deberás creerte de verdad dicha actitud.

Pero si piensas en cultivar las actitudes de hacker solo como una forma de ganar aceptación en esta cultura, te estás equivocando. Transformarse en la clase de persona que cree estas cosas es importante para ti —para ayudarte a aprender y mantenerte motivado. Como en todas las artes creativas, el modo más efectivo de transformarse en un maestro es imitar la mentalidad de los maestros —no sólo intelectualmente, sino también emocionalmente.

O como dice el siguiente poema zen moderno:

    Para seguir la trayectoria:
    mira al maestro,
    sigue al maestro,
    camina junto con el maestro,
    mira a través del maestro,
    conviértete en el maestro.

<a href="http://biblioweb.sindominio.net/telematica/hacker-como.html" target="_blank">
<br> Tomado de..
<a/>



  
  <p class="rss-subscribe">Inscripcion <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
<p></p>

