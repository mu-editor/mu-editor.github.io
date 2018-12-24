---
layout: zh
title: 下载 Mu
i18n: zh
---

# 下载 Mu

安装Mu有很多种方法。 最简单的是下载适用于 Windows 或 macOS 的官方安装程序。
如果你发现因为你正在使用的计算机被限制权限而无法安装 Mu 的话，你应该试试 PortaMu ，这是一种在 Windows 或 macOS 上从U盘运行 Mu 的办法。
你也可以使用 Python 的内置`pip`工具来安装。
一些 Linux 发行版已经有 Mu 的包了（你应该使用你的系统的包管理器来安装它）。 
最后，如果您使用的是 Raspbian（适用于 Raspberry Pi 的Linux 版本），则可以作为一个软件包来安装Mu。

如果你是一个专业的开发者，你可以在[GitHub](https://github.com/mu-editor/mu)上找到源代码。

<div class="media">
  <div class="media-left">
    <img src="/img/windows_logo.png" alt="Windows Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Windows 安装包</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win32.exe" class="btn btn-primary" role="button">32位</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_win64.exe" class="btn btn-primary" role="button">64位</a>
    <a href="/en/howto/install_windows" class="btn btn-default" role="button">安装指南</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/apple_logo.png" alt="Apple Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">macOS 安装包</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">下载</a>
    <a href="/en/howto/install_macos" class="btn btn-default" role="button">安装指南</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/portamu.png" alt="PortaMu Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">PortaMu - 从U盘运行Mu</h4>
    <p><a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win32.zip" class="btn btn-primary" role="button">Windows 32位</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/portamu_1.0.1_win64.zip" class="btn btn-primary" role="button">Windows 64位</a>
    <a href="https://github.com/mu-editor/mu/releases/download/1.0.1/mu-editor_1.0.1_osx.dmg" class="btn btn-primary" role="button">macOS</a>
    <a href="/en/howto/use_portamu" class="btn btn-default" role="button">安装指南</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/python_logo.png" alt="Python Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Python 包</h4>
        <p><a href="/en/howto/install_with_python" class="btn btn-default" role="button">安装指南</a></p>
  </div>
</div>

<hr/>

<div class="media">
  <div class="media-left">
    <img src="/img/rpi_logo.png" alt="Raspberry Pi Logo" class="media-object">
  </div>
  <div class="media-body">
    <h4 class="media-heading">Raspbian</h4>
        <p><a href="/en/howto/install_raspberry_pi" class="btn btn-default" role="button">安装指南</a></p>
  </div>
</div>

<br/>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title">Linux 用户请注意！</h3></div>
    <div class="panel-body">
    <p>在Linux上，为了使Mu能够与基于MicroPython的设备一起工作，
    您需要确保将自己添加到正确的权限组
    (通常是 <code>dialout</code> 或者 <code>uucp</code> 权限组). Also make
    同时也请确保您的系统会自动挂载这些设备，或者记得手动挂载。</p>
    </div>
</div>
