---
layout: default
title: How to use environment variables to configure GPIOZero in Python3 Mode. 
i18n: en
---
# How to use Environment Variables to Configure GPIOZero in Python3 Mode

Some libraries (such as GPIOZero) look up configuration information in
user-defined settings called environment variables. Mu allows you to define
what these environment variables should be so that whenever you run a script
or use the REPL in Python 3 mode, these settings are available to your code.

If you look at the [documentation for the GPIOZero library](https://gpiozero.readthedocs.io/en/stable/remote_gpio.html#environment-variables),
you'll see that you probably need to set the following environment variables
for it to work properly:

```
GPIOZERO_PIN_FACTORY=pigpio
PIGPIO_ADDR=192.168.1.3
```

The steps to make this happen in Mu are very simple:

Click on the "cog" icon in the bottom right hand corner of Mu's window
(highlighted in red in the image below). This will open up the
"Mu Administration" dialog.

<div class="row">
  <img src="/img/en/howto/cog_button.png" alt="The cog button" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Select the "Python 3 Environment" tab and fill in the environment variables
as shown below. Each environment variable must be on its own line and of the
form NAME=VALUE.

<div class="row">
  <img src="/img/en/howto/envars.png" alt="Environment variables" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

<div class="panel panel-warning">
    <div class="panel-heading"><h3 class="panel-title"><strong>Attention!</strong> The settings shown above are examples</h3></div>
    <div class="panel-body"><p>The correct value of the <code>PGPIO_ADDR</code>
    environment variable for your system will be different from the example
    shown above (highlighted in blue). Please consult the
    <a href="https://gpiozero.readthedocs.io/en/stable/remote_gpio.html#environment-variables">documentation for GPIOZero</a>
    for more information.</p>
    <p>Environment variables are saved and will remain in place when you
    re-start Mu. If you want to delete an environment variable, simply remove
    it from the text area shown above!</p>
    </div>
</div>
