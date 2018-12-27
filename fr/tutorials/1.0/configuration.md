---
layout: default
title: Advanced Configuration 
i18n: en
---

# Advanced Configuration

There's nothing advanced about configuring Mu -- you just edit a couple of
files. To find the relevant files you need to check the logs and make a note
of the paths to the files: `settings.json` and `session.json` (see the example
shown below).

<div class="row">
  <img src="/img/en/tutorials/settings_location.png" alt="Settings files" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

The `session.json` file contains details of Mu's state when you last quit the
editor. It means you can restart Mu where you left off. Mu always overwrites
the content of this file so it's not particularly useful for configuring Mu.
However, it could be a source of useful information when trying to work out
what Mu thinks it should be doing.

The `settings.json` file is currently used to one "global" setting: the
directory on the user's filesystem in which users should save their files. As
requirements change, more settings may be added to later versions. Each user
of the computer will have their own `settings.json` file.

If no setting is given, Mu defaults to the `mu_code` directory in the current
user's default home directory (as reported by the host operating system).

To change the default to something else, you'll need to update the
`settings.json` file to something like this:

```
{
  "workspace": "/home/ntoll/src"
}
```

The path to the new `workspace` value must be a valid path to a directory that
already exists. Otherwise, Mu will ignore it.
