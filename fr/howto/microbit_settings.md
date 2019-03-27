---
layout: default
title: How to minify your MicroPython scripts and use a custom runtime on the BBC micro:bit
i18n: en
---
# How to minify your MicroPython scripts and use a custom runtime on the BBC micro:bit

Being small is one of the strengths of the BBC micro:bit. However, small
also applies to the amount of storage space on the device which can be
problematic if you have MicroPython scripts that are simply too long to fit
onto the micro:bit.

Happily, there is a way to "minify" (remove the comments and compress the
white-space in your source code) so that the program remains unchanged but the
source code takes up less room.

Sometimes, if you're an advanced user, you want to try out a version of the
MicroPython runtime for the micro:bit that's different to the one already
included in Mu.

Happily there's a way to tell Mu which runtime `.hex` file to use instead of
the default.

Such settings for the micro:bit are found in the "Mu Administration" dialog
which you can see by clicking on the "cog" icon in the bottom right hand
corner of Mu's window (highlighted in red in the image below).

<div class="row">
  <img src="/img/en/howto/cog_button.png" alt="The cog button" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

As shown below, select the "BBC micro:bit Settings" tab and toggle the "minify"
checkbox to switch minification on or off. Use the text box to enter the *full
path* to the custom MicroPython runtime.

<div class="row">
  <img src="/img/en/howto/microbit_settings.png" alt="BBC micro:bit settings" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

<div class="panel panel-warning">
    <div class="panel-heading"><h3 class="panel-title"><strong>Attention!</strong> Ensure the runtime exists!</h3></div>
    <div class="panel-body"><p>Mu will complain if the file path to the custom
    MicroPython runtime doesn't exist. In this instance the default runtime
    will be used.</p>
    <p>These settings will remain in place when you re-start Mu. If you wish to
    revert back to the default runtime, simply delete the path.</p>
    </div>
</div>
