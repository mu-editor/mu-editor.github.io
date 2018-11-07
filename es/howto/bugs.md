---
layout: default
title: Como reportar un error en Mu
i18n: es
---
# Como reportar un error en Mu

<div class="row">
  <img src="/img/en/howto/bug.png" alt="El primer 'bug'" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Si alguna vez has escrito alguna línea de código, sabrás que todo software tiene
[errores](https://www.history.navy.mil/our-collections/photography/numerical-list-of-images/nhhc-series/nh-series/NH-96000/NH-96566-KN.html).
Este es el caso con Mu.

Si crees que ha encontrado un error, simplemente haga clic en el botón de abajo
(necesita tener una cuenta en GitHub) y luego haga clic en el botón verde "Nuevo problema"
Se encuentra en la parte superior derecha de la página:

<div class="row text-center">
<p><a class="btn btn-lg btn-danger" href="https://github.com/mu-editor/mu/issues"
        role="button" target="_blank">Reportar un error en Mu</a></p>
</div>

Cuando creas un nuevo problema, se le dará un número y los desarrolladores voluntarios,
que escriben y mantienen el código, serán informados por correo electrónico. Ellos
pueden hacerte preguntas acerca de tu problema, si las cosas no están claras. Puede que lo
cierren inmediatamente y marcandolo como "duplicado" (alguien ya ha reportado el mismo
problema - y harán referencia al problema original). Algunas veces
cerrarán el error y dirán "no se solucionará", porque no están de acuerdo en que es un
error *o* es demasiado trivial para invertir tiempo en el. Por último, ten en cuenta
del famoso error [PEBCAK] (https://en.wiktionary.org/wiki/PEBCAK) (Problema que
existe entre la silla y el teclado). Esto simplemente indica que el usuario ha causado
el problema (en lugar del software): un ordenador mal configurado, un
malentendido, o tal vez una falta de coincidencia con las expectativas. ;-)

En general, hay dos tipos de errores:

* Técnicos: el código tiene un error que hace que el programa no se detenga o deje de funcionar.
* De comportamiento: el código funciona correctamente, pero está haciendo lo incorrecto.

En ambos casos, para que podamos solucionar el error, necesitamos **tanta información
como sea posible**. Cuando creas un nuevo problema debes tratar de incluir, donde sea
posible, los siguientes tipos de información:

* Lo que estabas tratando de hacer,
* ¿Qué pasos has seguido para que esto suceda?,
* Lo que esperabas que sucediera,
* Lo que realmente pasó,
* ¿Por qué esta diferencia es problemática? (puede que no sea un error),
* Detalles técnicos como la versión de Mu que estás utilizando, la versión de tu sistema operativo y
   otros aspectos en el momento en el que se estaba ejecutando Mu.

Por favor, recuerda añadir una copia entera de los [logs de Mu](read_logs).

Usa un lenguaje sencillo y simple para describir el problema y, si es útil, dividelo en pasos simples para que los desarrolladores puedan reproducir el problema fácilmente. Por favor, intenta no suponer que entenderemos lo que intentabas lograr. Honestamente, lo mejor, es imaginar que nosotros (los desarrolladores) somos un grupo de personas con una inteligencia de 5 años.
Trata de explicar *todo* sobre el problema y no asumas que sabemos lo que querias obtener. ¡No nos importará si nos das mas detalles sobre el error! ;-)

Si deseas participar más en el desarrollo de Mu, nos encantaría
darte la bienvenida a través del [sitio web de desarrolladores de Mu](http://mu.rtfd.io/).
