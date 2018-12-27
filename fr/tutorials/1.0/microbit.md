---
layout: default
title: Mu and micro:bit
i18n: en
---

# Mu and micro:bit

The [BBC micro:bit](http://microbit.org/) is a small microcontroller based
computer which was originally created to be handed out to 1 million eleven
year old children in the United Kingdom. The micro:bit runs a special version
of [MicroPython](http://micropython.org/). Mu was originally a contribution by
the [Python Software Foundation](https://www.python.org/psf/) to this endeavour
(along with the browser based editor on the project's website).

Mu's micro:bit mode ensures all the features you can't get from using the
browser based editor are available and easy to use. These are accessed via
four buttons:

<div class="row">
  <img src="/img/en/tutorials/microbit_buttons.png" alt="Buttons from the micro:bit mode" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The "Flash" button puts your Python code onto the connected micro:bit
("flashing" is simply the term for copying code onto a microcontroller). When
you flash the device **all the previous code and data on it is deleted**. If
your code contains an error you'll see a helpful message scroll across the
device's display.

The process of flashing takes about 10 seconds, as shown below:

<div class="row">
  <img src="/img/en/tutorials/microbit_flash.gif" alt="micro:bit flash" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

When a micro:bit has MicroPython flashed onto it, it has a small and simple
file system for storing files. Mu's "Files" button makes it easy to access,
put, get and delete files on your device.

As shown below, clicking on "Files" opens two panes between the text editor and
Mu's footer. The pane on the left lists all the files on the micro:bit, the
pane on the right lists all the files in your `mu_code` directory on your
computer. Drag files between each to copy them. To delete a file on the
micro:bit, right click it and select "Delete".

<div class="row">
  <img src="/img/en/tutorials/microbit_files.gif" alt="micro:bit files" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

**NOTE: this functionality only works if you have MicroPython flashed onto the
device.**

The "REPL" button creates a new pane between the text editor and Mu's footer
which connects to the MicroPython REPL **on the micro:bit device**. The term
"REPL" is an acronym and stands for “Read, Evaluate, Print, Loop”, which
succinctly describes what the panel does for you. It reads interactive lines of
Python which you type, evaluates what these may mean, prints out any result it
has for you and then loops back to wait for your next Python instruction.

<div class="row">
  <img src="/img/en/tutorials/microbit_repl.gif" alt="micro:bit repl" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

As you can see from the example above, using MicroPython's REPL is like having
a conversation with the micro:bit in Python. Anything you can do in a regular
Python script, you can do in the REPL. It's a fun way to playfully explore the
capabilities of MicroPython on the micro:bit. Go on, have a play! (HINT: there
are lots of Easter eggs built into MicroPython on the micro:bit... can you find
them..?)

Finally, the "Plotter" button opens Mu's plotter. If your micro:bit is
outputting tuples of numbers via the serial connection, the plotter will
display them as a graph. This is incredibly useful for visualising any data you
might be measuring via the micro:bit. For more information read the
[tutorial about Mu's plotter](plotter).

<div class="row">
  <img src="/img/en/tutorials/microbit_plotter.gif" alt="micro:bit plotter" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>
