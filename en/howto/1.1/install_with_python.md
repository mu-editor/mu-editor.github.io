---
layout: default
title: How to install Mu with Python packaging on Windows, OSX and Linux.
i18n: en
---
# How to install Mu with Python packaging on Windows, OSX and Linux

If you already have [Python3](https://python.org/) installed on your Windows,
OSX or Linux machine then it is easy to install Mu with Python's
built-in package manager, [`pip`](https://pip.pypa.io/en/stable/installing/).
**Please note: this method does not currently work on Raspberry Pi** (use
[these instructions instead](/en/howto/1.1/install_raspberry_pi)).
If you're on Windows and would rather not type commands you should use the
[Windows installer for Mu](install_windows) instead. If you're using OSX on a
Mac and want to use the simple drag-and-drop installer instead, you should use
the [OSX installer for Mu](install_macos).

We recommend you run the following commands in a
[virtualenv](https://pypi.org/project/virtualenv/)
or other means of isolating your Python environment.

At your OS's command prompt (see below) type the following command:

```
pip3 install mu-editor==1.1.0b4
```

You'll see a bunch of things downloading from the internet. These are the other
Python libraries Mu needs to work. If it's worked the final message from `pip`
will be something like, "Successfully installed..." followed by a list of all
the packages upon which Mu depends.

To run Mu, still in the command prompt, type:

```
mu-editor
```

Press return and the editor should launch.

<div class="panel panel-danger">
    <div class="panel-heading"><strong>Warning</strong></div>
    <div class="panel-body"><p>Depending on how <strong>your</strong> machine
    is set up, you may encounter errors. The most common are:</p>
    <ul>
        <li>You don't have permission to use <code>pip</code> to install
        packages, in which case, talk to whoever administers your computer and
        ask them to install Mu for you (just point them to this website).</li>
        <li>You're using the wrong or and old version of <code>pip</code>. If
        you have Python 2 installed on your machine, you <strong>must</strong>
        make sure you're using <code>pip3</code>. If <code>pip</code> complains
        it is out of date, follow these
        <a href="https://pip.pypa.io/en/stable/installing/">instructions for
        updating pip</a>.</li>
        <li>You can't even run <code>pip</code>, in which case check you have
        Python 3 installed and that when Python was installed, you clicked the
        option that asks you if you'd like Python added to your path (you
        do).</li>
        <li>You have a 32-bit system. Some of Mu's dependencies will not run on a
        32-bit system, so you will need to upgrade your system or use a different
        editor.</li>
    </ul>
    <p>If you're still facing problems, perhaps try using another installation
    method (HINT: if you're on Windows or using OSX on a Mac, use the installer
    for the appropriate platform instead).
    As a last resort why not see if anyone can help you in the
    <a href="/en/discuss">discussions</a>.</p>
    </div>
</div>

## What is a Command Prompt?

Most people use a graphical user interface (GUI) on their computer: basically,
windows and icons controlled with a mouse and pointer. However, it's also
possible to control your computer by typing commands into a prompt. Once you
know the commands, this is often the most powerful way to use a computer.
However, it can feel a bit like casting spells with incomprehensible
incantations so may, at first, appear frightening.

Find your computer's command prompt depends upon which operating system you're
using:

* Windows: in the search area of your start menu, type `cmd` and
  press enter.
* Mac OSX: use the finder to go to the Applications folder and then the
  Utilities folder. Open the "Terminal" app.
* Linux: look for the "Terminal" app in your desktop's menu.

## I Want a Shortcut!

When `pip` installs software it doesn't automatically create a shortcut or menu
item for you. Happily, someone has created a utility called `shortcut` to do
this for you if you've not isolated Mu in a virtualenv.

Simply use `pip` to install `shortcut` and then use `shortcut` on Mu:

```
pip3 install shortcut
shortcut mu-editor
```
