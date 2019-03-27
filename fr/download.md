---
layout: default
title: Télécharger Mu
i18n: fr
---

# Télécharger Mu

Il y a plusieurs manières d'installer Mu. La plus simple est de télécharger
le programme d'installation officiel pour Windows ou Mac OSX. Si vous vous
rendez compte que l'ordinateur est verrouillé, vous pouvez essayer PortaMu :
une méthode pour utiliser Mu depuis une clé USB sous Windows ou Mac OSX. Vous
pouvez aussi utiliser l'outil `pip` inclus avec Python. Certaines distributions
Linux ont un paquet disponible pour Mu (et vous devriez utiliser le gestionnaire
de paquets de votre OS pour l'installer). Enfin, si vous êtes sous Raspbian (la 
distribution Linux pour Raspberry Pi) vous pouvez installer le paquet Mu.

Si vous êtes un développeur, vous trouverez le code source
[sur GitHub](https://github.com/mu-editor/mu).

<div class="media">
  <div class="media-left">
    <img src="/img/windows_logo.png" alt="Windows Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Installation Windows</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win32.exe" class="btn btn-primary" role="button">32-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win64.exe" class="btn btn-primary" role="button">64-bit</a>
    <a href="/fr/howto/install_windows" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/apple_logo.png" alt="Apple Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Installation Mac OSX</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">Télécharger</a>
    <a href="/fr/howto/install_macos" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/portamu.png" alt="PortaMu Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">PortaMu - Utilisez Mu depuis une clé USB</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win32.zip" class="btn btn-primary" role="button">Windows 32-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win64.zip" class="btn btn-primary" role="button">Windows 64-bit</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">Mac OSX</a>
    <a href="/fr/howto/use_portamu" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/python_logo.png" alt="Python Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Package Python</h4>
        <p><a href="/fr/howto/install_with_python" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/rpi_logo.png" alt="Raspberry Pi Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Raspbian</h4>
        <p><a href="/fr/howto/install_raspberry_pi" class="btn btn-default" role="button">Instructions</a></p>
  </div>
</div>

<br/>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title">UTILISATEURS LINUX, ATTENTION !</h3></div>
    <div class="panel-body">
    <p>Sous Linux, pour que Mu fonctionne avec des appareils basés sur MicroPython vous devez
    vous assurer d'ajouter votre utilisateur au bon groupe d'autorisations (il s'agit généralement du groupe 
    <code>dialout</code> ou <code>uucp</code>). Faites également attention à ce que votre distribution monte bien
    de manière automatique les appareils USB avec mémoire flash ou bien assurez vous de le faire manuellement.</p>
    </div>
</div>
