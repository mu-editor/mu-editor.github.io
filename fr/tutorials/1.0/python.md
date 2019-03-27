---
layout: default
title: Using Standard Python 3
i18n: en
---

# Using Standard Python 3

Python 3 is one of the most popular professional programming languages in the
world. It's also very easy to learn. Mu's Python 3 mode aims to make learning
Python 3 a stress free experience.

The functionality provided by Python 3 mode is contained in the following four
buttons:

<div class="row">
  <img src="/img/en/tutorials/python3_buttons.png" alt="Buttons from the Python 3 mode" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Taking each button in turn:

The "Run" button does exactly what you'd expect. It runs the current script.
When this happens the textual input and output of the program is displayed in
a panel between the text editor and Mu's footer.

When the code is running the "Run" button turns into a "Stop" button. Click
"Stop" to force your code to exit in a clean way. If your code finishes running
before you click "Stop" then you'll be presented with a Python prompt that
allows you to type Python commands to check the end state of your program. If
in doubt, just click "Stop".

<div class="row">
  <img src="/img/en/tutorials/python3_run.gif" alt="Python 3 mode run" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Clicking "Debug" will start Mu's visual debugger. The debugger starts running
your code (just like the "Run" button) but does so in a special way that
allows you to pause it, look at the state of things in your program and
step through your code so you can follow how Python is interpreting your
program. This is extraordinarily useful if your code has bugs in it.

<div class="row">
  <img src="/img/en/tutorials/python3_debug.gif" alt="Python 3 mode debug" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Read the [tutorial about how to use the visual debugger](debugger) for more
information.

The "REPL" button opens a new panel between the text editor and Mu's footer.
The term "REPL" is an acronym and stands for "Read, Evaluate, Print, Loop",
which succinctly describes what the panel does for you. It reads interactive
lines of Python which you type, evaluates what these may mean, prints out any
result it has for you and then loops back to wait for your next Python
instruction.

<div class="row">
  <img src="/img/en/tutorials/python3_repl.gif" alt="Python 3 mode REPL" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Put simply, it's like having a chat with your computer in
Python, it's a fabulously useful tool to use for testing things and "playing
around in code" and, because it is in a question and answer form, is a great
way to tell a story in code. The Python 3 REPL is also very powerful with
lots of interesting features to help you poke around. For more information
please read the [tutorial about how to use the REPL](repl).

Finally, the "Plotter" button opens the plotter pane between the text editor
and Mu's footer. This is an easy way to visualise numeric data that your
program may produce.

If you're running a program that prints numbers in a Python
tuple (i.e. the output looks like this: `(1, 2, 3)`) then the plotter will
display these numbers as a graph.

<div class="row">
  <img src="/img/en/tutorials/python3_plotter.gif" alt="Python 3 mode plotter" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The number of lines in the graph reflect the number of items in the tuple your
program outputs. **Always remember to put a short pause between writing your
Python tuples** (for example, `time.sleep(0.1)`). For more information, please
read the [tutorial about Mu's plotter](plotter).
