---
layout: default
title: How to install Mu on a Raspberry Pi
i18n: en
---

# How to install Mu on a Raspberry Pi

If you're using the Raspberry Pi Foundation's official
[Raspbian](https://www.raspberrypi.org/downloads/raspbian/)
operating system you can use the **Recommended Software** application to install **mu**.

## Step 1 - Update your Raspberry Pi

+ Open a terminal by selecting Accessories and Terminal from the menu

<div class="row">
  <img src="/img/en/howto/pi_open_terminal.png" alt="pi open terminal" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

+ Enter the following commands to update Raspbian

```bash
sudo apt-get update
sudo apt-get dist-upgrade
```

## Step 2 - Install Mu

+ Open the Recommended Software application from the Preferences menu.

<div class="row">
  <img src="/img/en/howto/pi_rec_software.png" alt="pi open recommended software" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

+ Select Mu from the list of applications to install.

<div class="row">
  <img src="/img/en/howto/pi_rec_software_select_annotated.png" alt="select mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

+ Click OK to start the installation process.

<div class="row">
  <img src="/img/en/howto/pi_rec_software_install.png" alt="click ok" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Step 3 - Start Mu

+ Open Mu by selecting it from the Programming menu.

<div class="row">
  <img src="/img/en/howto/pi_open_mu.png" alt="pi open mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

<div id="admins" class="panel panel-warning">
  <div class="panel-heading"><h3 class="panel-title"><strong>Install from the command line</strong></h3></div>
  <div class="panel-body">
  <p>You can also install Mu from the command line using the command:</p>
  <p><code>sudo apt-get install mu-editor</code></p>
  </div>
</div>
