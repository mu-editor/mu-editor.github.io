---
layout: default
title: How to try to fix your own broken code
i18n: en
---
# How to try to fix **your own** broken code

<div class="text-center"><h1 class="text-danger" style="font-size: 10em; font-weight: bold;">DON'T PANIC!</h1></div>

**THINGS WILL GO WRONG!**

When starting to learn to code, it doesn't take long to realise that it's very
hard to write software that works. When software doesn't work, we say it has
a bug (see [how to report bugs in Mu](bugs) for the world's very first computer
bug).

To be honest, professional software developers are just as capable of
writing buggy software as a beginner. The only difference is in the type of bug
they create.

Beginner programmers make beginner mistakes like typing the wrong instructions,
setting out code in the wrong way (causing a syntax error) or simply asking
the computer to do something impossible.

Professional programmers know the instructions that will work, understand how
to write their code correctly and appreciate the capabilities of a computer.
However, they often have blind spots, don't think through the full implications
of their code and can over-complicate the way they write software (thus making
it difficult to work out what's gone wrong).

The very best programmers are humble enough to acknowledge their ignorance (and
are fearless to ask questions when something is unclear), pragmatic enough to
accommodate and compromise (if it leads to wider positive progress) and value
simplicity in style, structure and solution (it's extraordinarily hard to
solve problems with simplicity, and is the sign of a great programmer).

With this in mind, there are certain thoughts, habits and processes you can
adopt to help you fix your inevitably broken code (everyone's code has bugs,
and those who claim otherwise are deluded).

## It's Probably Your Fault

Computers try very hard to carry out your instructions and it's very rare that
the computer will have a hardware bug. If your program doesn't work as you
expect it to, it's almost entirely going to be your fault since the computer
is only carrying out exactly what your instructions tell it to do.

So, the most likely cause of the bug is that **you** have done something wrong
in your code.

Upon reflection, this is a good thing, becuase more often than not, **you** can
also fix it by reading your code carefully, working out how what you wrote
isn't what you really meant to write, and then correcting things.

## Don't Just Sit There, Do Something! 

The usual way you'll learn something has gone wrong is with an error message.
Unfortunately, to non-programmers error messages might as well look like this:

<div class="row">
  <img src="/img/en/howto/error_message.png" alt="Silly error message" class="img-responsive center-block"/>
  <br/>
</div>

As a beginner programmer these sorts of message may, at first,
appear intimidating and confusing. Remember, DON'T PANIC! Here's how to make
sense of such messages.

There are different sorts of error and it's helpful to know which one you're
dealing with. Take a little bit of time to read the message. It could be a
*very long message* but you should start at the bottom. Such messages are
called stack traces and it'll look something like this:

```
  File "/home/ntoll/mu_code/bad.py", line 1
  print("Hello)
              ^
  SyntaxError: EOL while scanning string literal
```

In this instance we can see Python complaining about a `SyntaxError`, although
there are many different types of error (in technical parlance these are
called "exceptions"), four of which are listed below:

* If you see a `SyntaxError` you've simply typed code in a way that Python
  can't understand. Check you're not missing any special characters like `"` or
  `:`. It's like putting. a full stop in the middle of a sentence. It's hard
  for Python to understand exactly what you mean.

* A `NameError` probably means you've typed something inaccurately. It's like
  the difference between "Nicholas" and "Nicolas". They're two different people
  but their names look very similar. Make sure you've typed your names
  accurately!

* A `TypeError` indicates you're trying to do impossible things with different
  types of things. For example, how do you expect Python to handle
  `"Hello" + 3`? In this case `"Hello"` is a string of characters and `3` is
  a whole number. How do you add characters to numbers (and vice versa). I
  don't know and you don't know, so how can we expect Python to know too? When
  this happens Python will (legitimately) complain with a `TypeError`.

* A `ValueError` happens when you try to do something with the right sort of
  thing, but the with an unexpected value. For example, you may need to create
  a data containing a year, month and date represented as whole numbers.
  However, if you set the year as `-2018` you'll end up with a `ValueError`
  (since years *are* whole numbers but may not be negative!).

All the various exceptions (remember, that's what we call it when Python
indicates something has gone wrong) built into Python are
[documented on Python's website](https://docs.python.org/3/library/exceptions.html#concrete-exceptions).

## Clearly Define the Problem

So you may have found an exception at the end of the long stack trace. Instead
of putting your hand up, waiting for the teacher and then saying, "I have an
error", why not look up what the exception may mean (use the link above).
Alternatively, why not type "Python" followed by the name of the exception and
the message that comes with it into Google..?

Welcome to programming, where most of your time is spent trying to make sense
of why stuff doesn't work as you expected.

The most important aspect of this exercise is that you build up a picture of
what the program was doing, why it was doing it and how it got into a state
which caused it to fail.

If the exception at the end of your stack trace doesn't help you work out the
answers to these questions then work backwards up the stack trace to learn what
steps Python took to get into the problematic end state. It's a bit like the
computer is presenting you with a list like this:

* First I did this
* Then I did this
* Then I did this other thing
* After which I did this thing over here
* But then I couldn't do the thing you asked so, "ValueError"

As mentioned, starting at the bottom tells you what caused the failure, but
you may need to read backwards to work out what led to the problem.

## Check the Code (Checklist)

Python is trying to be as helpful as possible by giving you **absolutely all
the information you may need** in order to fix the problem. This includes the
type of exception (so you know what the problem actually is), perhaps a helpful
message and then a filename and line number.

These last two pieces of information tell you where, in your code, the problem
was encountered. In order to fix your code you should start where Python tells
you the problem was encountered. Once you're looking at the right line in the
right file you should develop a checklist of tests to make sure you've not
done something silly:

* Is your indentation correct? (A common mistake.)
* Have you mixed up `=` and `==`? (I do this all the time.)
* Are you referring to the right thing? (Don't name things, `x`, `y` or `z`
  and giving objects and variable meaningful names helps avoid this problem.)
* If you're calling a function, are you **sure** you understand what it's
  doing? (If it returns a value, is the value what you were expecting? If not,
  why not? Does your code work if the function encounters a problem?)
* Finally, don't just look at the line Python has given to you, explore the
  lines that lead up to where the problem occured. (Context is important!)

## Talk to the Rubber Duck

If you're still struggling, talk to the rubber duck.

<div class="row">
  <img src="/img/en/howto/debug_duck.png" alt="The PyCon UK Debug Duck" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

[Rubber Duck debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging) is
a great technique for seeing things that may at first not seem obvious. It
simply involves explaining each line of code where the problem is found to
an imaginary programmer represented by a rubber duck (you don't have to use a
rubber duck, and it's probably best if you imagine yourself explaining things
to the duck rather than actually talk to a rubber duck... that would look
weird).

This simple trick is a great way to shift your perspective to allow you to see
things you at first missed. For example, "First I set X to 15, then I loop over
the list X number of times so all the values are added to the total. Dammit.
The total is never reset to zero... no wonder it was so high. Why the hell
didn't I see that earlier..?" is a typical way this sort of thing plays out.

## Ask for Help

So you've looked up the exception, checked the code, rubber ducked for ten
minutes and the damn thing still won't work properly. Now what?

Easy... just ask for help.

Don't be afraid to ask questions - good developers are always asking questions.
Knowing how to ask and what the right questions are is an essential skill to
develop. Asking questions is NOT a sign you don't know what you're doing. To
good developers it's evidence that you're exploring the problem and a signal
that you're engaged and interested.

So, learn to ask questions in the right sort of a way.

"It doesn't work. What do I do?" is not going to be answered (at least in a
polite way).

"I have a ValueError when I try to set the score in my game, but I don't know
why I keep getting negative numbers on line 123 of `my_game.py`" is much more
specific, sets a context and tells people *where* they can help.

If all else fails, there's always this handy flow chart from the comic
[XKCD](https://www.xkcd.com/627/):

<div class="row">
  <img src="/img/en/howto/tech_support_cheat_sheet.png" alt="Flow chart of self help" class="img-responsive center-block"/>
  <br/>
</div>

Debugging code can be frustrating, time consuming and disheartening.
However, once your program works, the elation you will feel is definitely worth
it.

Best of luck! :-)
