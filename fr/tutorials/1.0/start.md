---
layout: default
title: Start Here! 
i18n: en
---

# Start Here! 

**Welcome to Mu!**

Mu is a Python code editor for beginner programmers. This means Mu makes it
very easy to create, run and revise your Python programs as you learn to code
in Python.

Mu is very simple and easy to understand. Here's what it looks like:

<div class="row">
  <img src="/img/en/tutorials/mu_ui.png" alt="The first bug" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

While there may seem to be lots going on in the picture above, if we break it
down into slices you'll see that Mu is easy to learn.

At the very top of Mu is a title bar (shown in the following picture). This may
look different on your computer, but its function is always the same: to
display the version of Mu that you're using (this is useful if you ever need
to tell us if you've found a problem with Mu) along with the name of the
current Python file that you're editing.

That's it!

<div class="row">
  <img src="/img/en/tutorials/mu_window_top.png" alt="The Mu title bar" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Next comes the button bar:

<div class="row">
  <img src="/img/en/tutorials/mu_buttons.png" alt="The Mu button bar" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

As you can see, it contains round buttons. If you hover your mouse over a
button (without actually clicking it) you'll see a little tool-tip pop up over
the button containing more information about what the button does. Try it!

Most of the buttons remain the same, but some will change depending on what
you're doing at the time.

The buttons are grouped together:

* Mode: This button is so important, it goes in its own group. Click it to
  change Mu's current mode. Each mode has different capabilities depending on
  what it is you want to achieve. If you want to know more about modes, there
  is a [tutorial about modes](modes) for you to read next.

* File system: The "New", "Load" and "Save" buttons in this group allow you to
  interact with files on your computer's hard drive.
  * New: create a new blank file.
  * Load: open a file selector to choose a file to load into Mu.
  * Save: save the file to your computer's hard drive. If the file has no name,
    you'll be asked to give one.

  If files have a name, they are usually auto-saved every 5 seconds.

* Code actions: The next group of buttons can change, depending on
  which mode you're currently using. They give you interesting ways to interact
  with the code you have written. In the example above the "Run", "Debug",
  "REPL" and "Plotter" buttons are part of this group. The buttons for each
  mode are described in the tutorials for each separate mode.

* Display settings: Sometimes it's important to change the way Mu looks. The
  next three buttons ("Zoom-in", "Zoom-out" and "Theme") change how Mu presents
  itself. The "Zoom-In" and "Zoom-Out" buttons make the text bigger or smaller.
  This is very useful if you need help seeing the code. The "Theme" button
  toggles through three different display "themes":
  * Day: a light theme that's easy on the eyes (used in the example images).
  * Night: a dark theme that makes you look like a coder in a Hollywood film.
  * High Contrast: a black and white theme for those who need help seeing Mu's
  user interface.

  Mu remembers which theme you were last using when you restart the editor.

* Editor support: The "Check", "Help" and "Quit" buttons provide ways for Mu to
  help you use Mu.
  * Check: analyses your code and suggests ways to improve it.
  * Help: opens your default browser on Mu's help page.
  * Quit: stops the editor. You may be asked to save your work if you haven't
    done so already.

Underneath the buttons are "tabs" which show you the files you have open and
highlight the one you're currently working on:

<div class="row">
  <img src="/img/en/tutorials/mu_tabs.png" alt="The tabs in Mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

*Click on the tab to change to the file named in the tab*.

To close a file you just click on the cross in the file's tab. You can also
click and drag the tabs from left to right and back again, to re-order them.

If you want to rename a file, double click on its name *in the tab* and you'll
be asked for the new name.

Underneath the tabs comes the largest and most important part of Mu ~ the
text editor:

<div class="row">
  <img src="/img/en/tutorials/mu_editor_widget.png" alt="The text editor in Mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

This displays the code for the currently selected tab. As you change tabs
you'll see that the code in this area changes. If you click on this area and
start typing you'll see your code appear here. As you type code Mu will change
the colour of the text to help you read the code. On the left hand side is a
column containing the line numbers for your file. These are useful for when
Python reports errors (which usually contain line numbers).

Finally, at the bottom is the footer

<div class="row">
  <img src="/img/en/tutorials/mu_footer.png" alt="The footer in Mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The footer contains three things:

* On the left is an area where Mu writes messages to you. In this case Mu is
  saying, "Hurrah! Checker turned up no problems".
* The first item on the right is the name of the current mode. In this case Mu
  is in Python mode.
* The item on the very right hand side is a cog item. If you click it you'll
  see an administration screen which, for most of the time, you can safely
  ignore.

## Hello From Mu!

Let's create your first Python program with Mu.

1. Make sure Mu is in Python 3 mode (check the footer!). If it isn't click on
   the "Mode" button and double click "Python 3" mode.
2. Click the "New" button, then before typing anything, click the "Save" button
   and give your file a name (for example "hello.py").
3. Type the following Python code into the text area:
   ```
   print("Hello from Mu!")
   ```
4. Click the "Run" button and the output of your program will be displayed in
   a new "output" area between the text editor and the footer.
5. Click the "Stop" button to return to editing your code.

Steps 3, 4 and 5 are shown below:

<div class="row">
  <img src="/img/en//mu.gif" alt="Hello from Mu!" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Congratulations! You've just written and run your first Python program using
Mu. Next, why not learn about [modes in Mu](modes)?
