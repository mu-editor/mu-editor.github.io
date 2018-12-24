---
layout: default
title: How to copy files on and off a micro:bit
i18n: en
---
# How to Copy Files On and Off a micro:bit

MicroPython on the BBC micro:bit has [a very small filesystem](https://microbit-micropython.readthedocs.io/en/latest/tutorials/storage.html).
Often you'll want to copy small files onto the device, or copy them from the
micro:bit onto your own computer for further processing.

Happily, Mu has a visual way to do this by dragging and dropping files. Click
on the button shown below:

<div class="row">
  <img src="/img/en/howto/microbit_files.png" alt="Files button" class="img-responsive center-block img-rounded movie"/>
</div>

The pane shown below will appear at the bottom of Mu's window. Simply click and
drag a file between the list of files on the micro:bit and those on your
computer (as the animation shows). The files on your computer can be found in
the folder Mu uses as your working directory (see the tutorial called
[where are my files?](/en/tutorials/1.0/files)).

<div class="row">
  <img src="/img/en/howto/microbit_files.gif" alt="Moving files with a micro:bit" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title">
    <strong>WARNING:</strong> Don't toggle files off while the micro:bit is
    busy!</h3></div>
    <div class="panel-body"><p>If you click the "Files" button while the
    micro:bit is still reacting to instructions from Mu (such as listing files,
    getting the content of a file, and so on), then you may find that
    afterwards the REPL behaves strangely.</p>
    <p>The solution is simply to press restart on the device while the "Files"
    or "REPL" panes are off.</p>
    <p>If in doubt while using the "Files" pane, just wait for Mu to confirm
    that whatever file related activity is happening, is reported as finished
    (as shown above).</p>
    </div>
</div>
