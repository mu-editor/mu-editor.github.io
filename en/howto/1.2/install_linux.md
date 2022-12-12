---
layout: default
title: How to install Mu on Linux 
i18n: en
---

# How to install Mu on Linux

Packaging on Linux is a complicated scenario. We've tried to find a solution
that will work on as many flavours of Linux as possible (x86_64) while making
it as easy to install as possible for beginner coders. As a result, we're
currently using the [AppImage](https://appimage.org/) standard for package distribution.


## Step 1 - Download the AppImage

* [Download the AppImage TAR archive](/en/download) and put it somewhere safe
  (such as your home directory, or Downloads directory).


## Step 2 - Update User Permissions

On Linux, in order for Mu to work with the MicroPython based devices
you need to ensure you add yourself to the correct permissions group
(usually the `dialout` or `uucp` groups).

* Open a terminal (press `CTRL` + `ALT` + `T`).
* Type the following to add your user (identified by `$USER`) to the `dialout` group:

```
sudo adduser $USER dialout
```
* You will need to enter your password for this to work.
* You should reboot your machine for this change to take effect.

On some specialised Linux distributions (i.e. **not** the most popular / common
ones), flash drives may not be automatically detected and mounted. Since many
MicroPython and CircuitPython based devices appear as flash devices by default,
please consult your distribution's documentation for how to automatically
mount such devices when they are plugged in.


## Step 3 - Untar Mu

* In the file explorer, find the AppImage TAR archive you downloaded in the
  first step, and right click to display the context menu.

<div class="row">
  <img src="/img/en/howto/extract_here.png" alt="Right click TAR file" class="img-responsive center-block img-rounded "/>
  <br/>
</div>

* Select the "Extract here" entry. A new directory will appear.

<div class="row">
  <img src="/img/en/howto/extract_here2.png" alt="New directory containing AppImage" class="img-responsive center-block img-rounded "/>
  <br/>
</div>

* Inside the new directory is the AppImage containing Mu.


<div class="row">
  <img src="/img/en/howto/extract_here3.png" alt="The Mu AppImage, to run." class="img-responsive center-block img-rounded "/>
  <br/>
</div>

## Step 4 - Install Dependencies

On these Linux distributions you need to install additional software packages.
Bring up a terminal window and run the following commands:

**Arch Linux**

```
pacman -S libxcript-compat
```

**Ubuntu 22.04 LTS (Jammy Jellyfish)**

```
apt install libfuse2
```


## Step 5 - Launch Mu

On most Linux distributions, double click Mu's AppImage to start it.
A few, however, require using the terminal to do it:

**Arch Linux**

As of Mu 1.1.1 running Mu requires using the Wayland display server.
Other than that, double clicking Mu's AppImage works nicely.
