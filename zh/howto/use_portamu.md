---
layout: default
title: How to Use PortaMu to run Mu Anywhere 
i18n: en
---

# How to use PortaMu to run Mu anywhere

<div class="row">
  <img src="/img/portamu.png" alt="PortaMu Logo" class="img-responsive center-block img-rounded"/>
  <br/>
</div>

Sometimes it's not possible to install Mu because the computers you have
available are locked down by somebody else.

Perhaps you find yourself running a workshop in a library or your school's
network administrator is more likely to say "get off my lawn" than "let me help
you with that".

Don't worry, thanks to the remarkable work of 14 year old
[Josh Lowe](http://allaboutcode.co.uk/), you can run Mu from a pendrive
(those dongle-thingamabobs for storing files that you plug into the computer's
USB port).

This technique should work on both Windows and OSX.

<div class="alert alert-warning" role="alert">
    <h3>Running Mu from a pendrive is <strong>SLOW</strong>!</h3>
    <p>When you launch an application it needs to be read into the computer's
    memory in order to run. The hard drives of computers are many times faster
    than pendrives when it comes to this. As a result, it may take many
    seconds for Mu to start up after you try to launch it. Precisely how long
    depends upon the quality of your pendrive and perhaps the age of your
    computer.</p>
    <p>In any case, patience is the name of the game here. Once Mu is up and
    running, it should work as fast as if it were installed in a more
    conventional manner.</p>
    <p>It'll be worth the wait!</p>
</div>

## Windows

[Download](/en/download) the correct 32 bit or 64 bit version of PortaMu for
your operating system.

To find out whether you need a 32 bit or 64 bit installer:

+ Opening Explorer, right click "This PC" and select properties.

<div class="row">
  <img src="/img/en/howto/windows_open_pc_properties_annotated.png" alt="open pc properties" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

+ The operating system type will be shown under System, System Type.

<div class="row">
  <img src="/img/en/howto/windows_system_properties_annotated.png" alt="system type" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

There is also [advice on Microsoft's website](https://support.microsoft.com/en-us/help/15056/windows-7-32-64-bit-faq) for finding whether you are using 32 or 64 bit Windows.

Once you've downloaded the correct zip file, extract it (right click, then
select extract) onto the already attached pendrive. When you plug the pendrive
into a locked-down computer, navigate to the folder on the pendrive where you
extracted Mu and double click on the `Launch Mu.bat` file to start. **It may
take some time for Mu to launch** because of the relative slowness of
pendrives.

Sometimes, depending upon the machine you're using, Windows may say that it is
protecting your PC from an unrecognised application.

<div class="row">
  <img src="/img/en/howto/beta/win10.2.png" alt="Windows protector" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The solution is to click on the "More info" link:

<div class="row">
  <img src="/img/en/howto/beta/win10.2_annotated.png" alt="Windows protector" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Then click on the "Run anyway" button.

<div class="row">
  <img src="/img/en/howto/beta/win10.3.png" alt="Windows protector" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Mac OSX

You simply need to [download](/en/download) the existing OSX installer, copy it
onto the pen drive and double click it on the pendrive. However, instead of
copying the `mu-editor` icon to the "Applications" folder, you should simply
double click it and Mu should launch. As mentioned before, this may take some
time and, when run for the first time, OSX may ask you to confirm you want to
run it.

That's it!
