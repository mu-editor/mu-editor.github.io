---
layout: default
title: Descargar Mu
i18n: es
---

# Descargar Mu

Hay muchas maneras de instalar Mu. Lo más sencillo es descargar la versión oficial
del instalador para Windows o Mac OSX. Si encuentra que no puede instalar Mu porque el
ordenador que está utilizando está bloqueado, debe probar PortaMu: un método que permite
ejecutar Mu desde un pendrive en Windows u OSX. También puedes usar la
herramienta `pip` incorporada de Python. Algunas distribuciones de Linux vienen con Mu empaquetado
ya (y debe usar el administrador de paquetes de su sistema operativo para instalarlo). Finalmente,
si está en Raspbian (la versión de Linux para Raspberry Pi) puede instalar Mu como un paquete.

Si eres un desarrollador, puedes encontrar el código fuente.
[on GitHub](https://github.com/mu-editor/mu).

<div class="media">
  <div class="media-left">
    <img src="/img/windows_logo.png" alt="Windows Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Instalador de Windows</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win32.exe" class="btn btn-primary" role="button">32-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win64.exe" class="btn btn-primary" role="button">64-bit</a>
    <a href="/en/howto/install_windows" class="btn btn-default" role="button">Instrucciones</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/apple_logo.png" alt="Apple Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Instalador para Mac OSX</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">Descargar</a>
    <a href="/en/howto/install_macos" class="btn btn-default" role="button">Instrucciones</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/portamu.png" alt="PortaMu Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">PortaMu - Ejecutar Mu desde un Pendrive</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win32.zip" class="btn btn-primary" role="button">Windows 32-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win64.zip" class="btn btn-primary" role="button">Windows 64-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">Mac OSX</a>
    <a href="/en/howto/use_portamu" class="btn btn-default" role="button">Instrucciones</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/python_logo.png" alt="Python Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Python Package</h4>
        <p><a href="/en/howto/install_with_python" class="btn btn-default" role="button">Instrucciones</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/rpi_logo.png" alt="Raspberry Pi Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Raspbian</h4>
        <p><a href="/en/howto/install_raspberry_pi" class="btn btn-default" role="button">Instrucciones</a></p>
  </div>
</div>

<br/>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title">ATENCIÓN A LOS USUARIOS DE LINUX!</h3></div>
    <div class="panel-body">
    <p>En Linux, para que Mu funcione con los dispositivos basados en MicroPython
     debe asegurarse de agregar al grupo de permisos correcto (por lo general,
     los grupos <code> dialout </code> o <code> uucp </code>). También hay que
     asegurarse de que su distribución monta automáticamente dispositivos flash, o
     Asegúrate de montarlos manualmente.</p>
    </div>
</div>
