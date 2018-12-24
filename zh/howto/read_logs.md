---
layout: default
title: How to read the logs in Mu.
i18n: en
---
# How to read the logs in Mu

Log files are a way for Mu to keep track of what it has been doing. These is
**very** useful when trying to work out why Mu has behaved in a certain way or
if Mu has encountered an error. Logs also help work out how students may have
got Mu into a certain undesirable state.

Mu keeps up to 5 days worth of logs in a special directory the
operating system defines for such things. Since this directory changes from
system to system and may even depend on the way in which a computer is
configured (for example, user data is stored on a network drive), Mu provides a
shortcut to the *current log file*: click on the small cog icon in the bottom
right hand side of Mu, right next to the name of the current mode (highlighted
in red below):

<div class="row">
  <img src="/img/en/howto/cog_button.png" alt="The cog button" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The "Mu Administration" window will open with the "Current Log" tab selected
(this is the one you need). It should look something like this:

<div class="row">
  <img src="/img/en/howto/log_window.png" alt="The log window" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

Mu **appends** lines to the log file, so the most recent line is at the end of
the logs.

If you ever find a bug in Mu, please attach a **complete** copy of the log file
for the day when you discovered the bug (and it'd be helpful if you point out
the lines in the log for when the bug was encountered).

<div class="panel panel-info">
    <div class="panel-heading"><h3 class="panel-title">Copying the Log is Easy</h3></div>
    <div class="panel-body">
        <p>Copying the contents of the log file takes just three steps:</p>
        <ol>
            <li>Click on the content of the log file to bring it into focus,
            then either drag your mouse to highlight specific lines, or press
            CTRL-A (CMD-A on a Mac) to "select all".</li>
            <li>Press CTRL-C (CMD-C on a Mac) to "copy" the contents of the
            log file into your clipboard.</li>
            <li>Click to move focus onto a web form or other target for the
            contents of the log and press CTRL-V (CMD-V on a Mac) to
            "paste" the contents of the log from your clipboard into the
            desired location.</li>
        </ol>
    </div>
</div>

Every time Mu starts it logs details about the system, including the paths to
the various places it stores things such as log files, settings and sessions.
It looks something like:

```
-----------------

Starting Mu 1.0.0.beta.15
2018-03-19 16:51:22,385 - root:95(run) INFO: uname_result(system='Linux', node='heraclitus', release='4.13.0-36-generic', version='#40-Ubuntu SMP Fri Feb 16 20:07:48 UTC 2018', machine='x86_64', processor='x86_64')
2018-03-19 16:51:22,448 - mu.logic:499(__init__) INFO: Setting up editor.
2018-03-19 16:51:22,449 - mu.logic:510(__init__) INFO: Settings path: /home/ntoll/.local/share/mu/settings.json
2018-03-19 16:51:22,449 - mu.logic:511(__init__) INFO: Session path: /home/ntoll/.local/share/mu/session.json
2018-03-19 16:51:22,449 - mu.logic:512(__init__) INFO: Log directory: /home/ntoll/.cache/mu/log
2018-03-19 16:51:22,449 - mu.logic:513(__init__) INFO: Data directory: /home/ntoll/.local/share/mu
2018-03-19 16:51:22,467 - mu.logic:521(setup) INFO: Available modes: python, adafruit, microbit, debugger, pygamezero
2018-03-19 16:51:22,518 - mu.logic:856(change_mode) INFO: Workspace directory: /home/ntoll/mu_code
2018-03-19 16:51:22,519 - mu.logic:560(restore_session) INFO: Restoring session from: /home/ntoll/.local/share/mu/session.json
```

Each time Mu restarts it emits a line of dashes: `-----------------`. This
makes it easy to visually find restarts in the log file.

Each line in the log file follows a pattern:

* It starts with the date and time of the log entry, YYYY-MM-DD HH:MM:SS
* Next comes the name of the file and the line number that generated the log
  entry.
* Following this, in parenthesis, is the name of the function being evaluated
  when the log entry was created.
* Next comes an indication of the type of log entry this is. This will be one
  of the following values: `DEBUG`, `INFO`, `WARNING`, `ERROR` or `CRITICAL`.
  See the [Python documentation on logging](https://docs.python.org/3.6/library/logging.html#logging-levels) for what they mean.
* Finally, you'll see some sort of textual output, often a helpful message
  explaining why the log was written, or perhaps a copy of some data which Mu
  was processing at the time of the log entry.
