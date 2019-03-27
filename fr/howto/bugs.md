---
layout: default
title: How to report a bug in Mu
i18n: en
---
# How to report a bug in Mu

<div class="row">
  <img src="/img/en/howto/bug.png" alt="The first bug" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

If you've ever written a line of code, you'll know that
[all software has bugs](https://www.history.navy.mil/our-collections/photography/numerical-list-of-images/nhhc-series/nh-series/NH-96000/NH-96566-KN.html).
This will be the case with Mu.

If you think you have found a bug, simply click on the button below (you'll
need to have an account on GitHub) and then click the green "New Issue" button
found at the top right hand side of the page:

<div class="row text-center">
<p><a class="btn btn-lg btn-danger" href="https://github.com/mu-editor/mu/issues"
        role="button" target="_blank">Report a Bug in Mu</a></p>
</div>

When you create a new issue it will be given a number and the volunteer
developers, who write and maintain the code, will be informed by email. They
may annotate questions to your issue, if things are not clear. They may
immediately close it and mark it as "duplicate" (someone else has already
reported the bug -- and they'll reference the original issue). Sometimes
they'll close the bug and say "won't fix", because they disagree that it's a
bug *or* it's too trivial in order to invest any time. Finally, please be aware
of the famous [PEBCAK](https://en.wiktionary.org/wiki/PEBCAK) bug (Problem
Exists Between Chair and Keyboard). This simply indicates the user has caused
the problem (rather than the software): a misconfigured computer, a
misunderstanding, or perhaps a mismatch of expectation. ;-)

There are generally two sorts of bugs:

* Technical: the code has a mistake in it which causes the program to break.
* Behavioural: the code works correctly, but is doing the wrong thing.

In both cases, for us to be able to fix the bug, we need **as much information
as possible**. When you create a new issue you should try to include, where
relevant, the following sorts of information:

* What you were trying to do,
* What steps you took to make this happen,
* What you expected to happen,
* What actually happened,
* Why this difference is problematic (it may not be a bug!),
* Technical details like the version of Mu you're using, your OS version and
  other aspects of the context in which Mu was running. 

Please remember to attach a [copy of the full log files for Mu](read_logs).

Use plain and simple language to describe the problem and, if helpful, break
it down into steps so developers can easily recreate the issue. Please don't
assume we'll understand what you were trying to achieve -- honestly, it's best
if you try to imagine we (the developers) are a bunch of clever 5-year-olds. 
Try to explain *everything* about the problem and don't assume we know what you
mean. We won't mind! ;-)

If you would like to get more involved in the development of Mu, we'd love to
welcome you via the [Mu developer's website](http://mu.rtfd.io/).
