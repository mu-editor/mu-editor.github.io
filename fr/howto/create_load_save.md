---
layout: default
title: How to create, load and save files in Mu.
i18n: en
---
# How to create, load and save files in Mu

You need to understand what each of the following three buttons do:

<div class="row">
  <img src="/img/en/howto/create_load_save.png" alt="New, Load and Save buttons" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

* **New** - Click on this button to create a new empty file. Before you can run
  your code you'll need to save it (i.e. give it a filename).
* **Load** - When you click this button a file selector dialog box pops up and
  you should click on the Python file you'd like to load into Mu (or press
  cancel).
* **Save** - Clicking this button saves the file in the currently selected tab.
  If the file was newly created then Mu will ask you for a name for the file.

<div class="panel panel-info">
    <div class="panel-heading"><h3 class="panel-title">Copy/Rename Files</h3></div>
    <div class="panel-body">
        <p>If you want to create a newly named copy of the current file you
        can rename it by clicking on the filename in the file's tab in Mu.</p>
    </div>
</div>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title">Don't Use Python Module Names</h3></div>
    <div class="panel-body">
        <p>It's tempting to name your new file that uses the <code>turtle</code>
        module as "turtle.py". <strong>Don't do this!</strong> If you name
        your file after a module you're using <strong>in your code</strong>
        then Python will break because it's trying to import
        <strong>your</strong> code rather than the code from Python's standard
        library!</p>
    </div>
</div>
