---
layout: default
title: How to install Mu on Windows with the Official Installer
i18n: en
---

# How to install Mu on Windows with the Official Installer 

Installing Mu in Windows is super easy (if you are a network administrator we
recommend you [read the instructions at the bottom of the page](#admins)).

<div class="row">
  <img src="/img/en/howto/windows_mu_installer.gif" alt="mu windows installer" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Mu works on Window 7, 8 and 10 in 32 bit and 64 bit. It's a good idea to make sure your system to up-to-date with all Windows updates.

If you are in an educational setting you may need to get your system administrator to run the installer for you.

## Step 1 - Download Mu Installer

[Download](/en/download) the correct 32 bit or 64 bit installer for your operating system.

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

# Step 2 - Run the installer

+ Find the installer you just downloaded (it's probably in your Downloads folder)

<div class="row">
  <img src="/img/en/howto/beta/win7.1.png" alt="Windows 7 - Find the installer" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

<div class="row">
  <img src="/img/en/howto/beta/win10.1.png" alt="Windows 10 -Find the installer" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

+ Double-click the installer to run it.

<div class="alert alert-warning" role="alert">
    <h3>THIS IS SOFTWARE FROM THE INTERNET!</h3>
    
    <p>Windows complains about Mu coming from the internet.</p>

    <p>As a result, we've outlined the extra steps needed to help Windows
    install Mu for both Windows 7 and Windows 10 (other versions of Windows
    will be similar).</p>

    <h3>Windows 7</h3>
    <p>"User Account Control" will ask you if you want to allow this program to make changes to your computer.
    Click "Yes"</p>
    <img src="/img/en/howto/beta/win7.2.png" alt="Click Yes" class="img-responsive center-block img-rounded movie"/><br/>
    <h3>Windows 10</h3>
    <p>Windows Defender will pop up with a warning message. You should click on the "More info" link.</p>
    <img src="/img/en/howto/beta/win10.2_annotated.png" alt="Click More Info" class="img-responsive center-block img-rounded movie"/><br/>
    <p>The message will change giving you more information about the installer and display a "Run anyway" button. Click
    "Run anyway".</p>
    <img src="/img/en/howto/beta/win10.3.png" alt="Click Run Anyway" class="img-responsive center-block img-rounded movie"/><br/>
</div>

## Step 3 - Start the install

Confirm the version of Mu you'll be installing and click "Next".

<div class="row">
  <img src="/img/en/howto/winstall1.png" alt="Windows installer step 1" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The version number will likely be different from the one shown.

## Step 4 - License Agreement

Review the license and click "Agree".

<div class="row">
  <img src="/img/en/howto/winstall2.png" alt="Windows installer step 2" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Step 5 - Choose Users

Select if you want to install Mu for all users, or just yourself and click "Next".

Please note, if your user account does not have administrative rights this step might not appear on your installation process.
If it does, the installer might only work if you select the "Install just for me" option.

<div class="row">
  <img src="/img/en/howto/winstall3.png" alt="Windows installer step 3" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Step 6 - Choose Install Location

Select the installation destination (you can usually leave this as the default) and click "Install".

<div class="row">
  <img src="/img/en/howto/winstall4.png" alt="Windows installer step 4" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Step 7 - Installing

Go make a cup of coffee as Mu installs on your computer.

<div class="row">
  <img src="/img/en/howto/winstall5.png" alt="Windows installer step 5" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Step 8 - Complete

The installation has completed successfully, click "Finish" to close the installer.

<div class="row">
  <img src="/img/en/howto/winstall6.png" alt="Windows installer step 6" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

## Step 9 - Start Mu

You can start Mu by clicking on the icon in the Start menu.

<div class="row">
  <img src="/img/en/howto/windows_start_mu.png" alt="Windows start mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

<div id="admins" class="panel panel-warning">
    <div class="panel-heading"><h3 class="panel-title"><strong>ATTENTION NETWORK ADMINISTRATORS</strong></h3></div>
    <div class="panel-body">
    <p>If you are a network administrator who needs to install Mu on
    many machines we'd like to answer a couple of common queries and provide
    some technical context and information:</p>

    <dl>
        <dt>Why is the installer a <code>.exe</code> rather than an MSI?</dt>
        <dd>In 2015 Microsoft announced that, while MSI won't go away any time
        soon, they want developers to move onto other, more modern, packaging
        solutions. We use a simple and easy to use
        <a href="https://pynsist.readthedocs.io/en/latest/">packaging
        system</a> which allows us to automatically and reliably create 
        installers with zero manual intervention.</dd>
        <dt>Why is the default install per-user rather than system wide?</dt>
        <dd>Engineers at Microsoft have
        <a href="https://twitter.com/zooba/status/1013445957290061824">advised
        us</a> that per-user is the preferred for the following reasons:
            <ul>
                <li>Non-admin users can use the installer.</li>
                <li>Such installations keep users isolated from each other.</li>
                <li>Per-user installation means security and reliability
                problems encountered by running as admin are avoided.</li>
            </ul>
        For more information about installation contexts, please see
        <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd765197(v=vs.85).aspx">this article on Microsoft's website</a>.
        </dd>

    </dl>
    <p><strong>We understand that, as a system administrator, you know what
    you're doing and simply want to install Mu, system wide, on all the
    machines under your control.</strong> In this case, you need
    to run the installer with the following flags:
    <code>mu-editor_win64.exe /S /AllUsers</code></p>

    <p>The <code>/S</code> flag tells the installer to work in "silent" mode
    (i.e. you won't see the windows shown in the screenshots above) and the
    <code>/AllUsers</code> flag makes Mu available to all users of the system 
    (i.e. it's installed "system wide").</p>
    <p>If you encounter problems or wish to give feedback, please
    <a href="/en/discuss">get in touch</a>.</p>
    </div>
</div>
