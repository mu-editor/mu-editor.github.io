---
layout: default
title: ESP Boards and Mu
i18n: en
---

# ESP8266 and ESP32 boards and Mu

ESP8266 and ESP32 boards are small, cheap and connect to the Internet.  
These boards are capable of running 
[MicroPython](https://www.raspberrypi.com/documentation/microcontrollers/micropython.html).

The extra functionality provided by ESP MicroPython mode is contained in the following
buttons:

<div class="row">
  <img src="/img/en/tutorials/rp2040_buttons.png" alt="Buttons for rp2040 mode" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The "Run" button runs your Python code and opens the REPL pane to display any output.

The "Files" button opens two panes below the code editor.  The left pane lists files stored
on your microcontroller and the right pane lists files stored on your computer.

The "REPL" button opens a serial data connection to the Raspberry Pi Pico board you
may have connected to your computer. This will result in a new pane between the
text editor and Mu's footer. Any serial data emitted from the device will
appear here. You can interact with the MicroPython REPL by clicking in the REPL pane 
to have focus.

You can only have Files or REPL open at a time.

The "Plotter" button opens Mu's plotter. If your device is outputting tuples
of numbers via the serial connection, the plotter will display them as a
graph. This is incredibly useful for visualising any data you might be
measuring via the device. For more information read the
[tutorial about Mu's plotter](plotter).

