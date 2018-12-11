---
layout: default
title: Descarga Mu
i18n: es
---

# Descarga Mu
Hay muchas maneras de instalar Mu. La más simple es descargar la version original para Windows o MacOSX. Si no puedes instalar Mu porque 
el ordenador que estas utilizando esta bloqueado, deberias probar PortaMu: un metodo 
para utilizar Mu desde un USB en Windows o MacOSX. Tambien puedes utilizar la  erramienta 
de Python `pip`. Algunas distribuciones de Linux ya vienen con Mu instalado
(y tu deberias utilizar la applicacion para controlar el software para instalarlo). Finalmente,
si estas utilizando Raspbian (La version de Linux para Raspberry Pi) puedes instalar Mu 
como un paquete.

Si eres un desarrollador puedes encontrar el codigo fuente 
[en GitHub](https://github.com/mu-editor/mu).

<div class="media">
  <div class="media-left">
    <img src="/img/windows_logo.png" alt="Windows Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Windows Installer</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win32.exe" class="btn btn-primary" role="button">32-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win64.exe" class="btn btn-primary" role="button">64-bit</a>
    <a href="/en/howto/install_windows" class="btn btn-default" role="button">Instruciones</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/apple_logo.png" alt="Apple Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">MacOSX Installer</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">Download</a>
    <a href="/en/howto/install_macos" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/portamu.png" alt="PortaMu Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">PortaMu - Utiliza Mu desde un USB</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win32.zip" class="btn btn-primary" role="button">Windows 32-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win64.zip" class="btn btn-primary" role="button">Windows 64-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">Mac OSX</a>
    <a href="/en/howto/use_portamu" class="btn btn-default" role="button">Instruciones</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/python_logo.png" alt="Python Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Python</h4>
        <p><a href="/en/howto/install_with_python" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/rpi_logo.png" alt="Raspberry Pi Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Raspbian</h4>
        <p><a href="/en/howto/install_raspberry_pi" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<br/>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title>¡ATENCION LOS USUARIOS DE LINUX!</h3></div>
    <div class="panel-body">
    <p>En Linux, para hacer que Mu funcione con MicroPython en tu dispositivo 
    tienes que asegurarte tu mismo de darle los permisos de grupo correctos
    (normalmente los <code>dialout</code> o <code>uucp</code>). Tambien debes asegurarte de que se monten correctamente los 
     USB o pendrives (Automaticamente). Sino asegurate de que lo hagas manualmente</p>
    </div>
</div>
