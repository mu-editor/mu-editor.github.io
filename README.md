# codewith.mu

** THIS PROJECT IS ARCHIVED AND NO LONGER MAINTAINED **

This is the repository that generates the website https://codewith.mu

It uses the GitHub pages functionality to build a Jekyll (a static site generator) project that gets published on each commit on master.

For local development you can follow these instructions to install the toolchain required for Jekyll: https://jekyllrb.com/docs/installation/

Since Jekyll requires Ruby, RubyGems, GCC, Make, and it is not officially supported on Windows, a Vagrant image can be used for simplicity.
Assuming you have Vagrant installed:

```
git clone https://github.com/lcreid/rails-5-jade.git
cd rails-5-jade
vagrant up
vagrant ssh
git clone https://github.com/mu-editor/mu-editor.github.io.git mu-website
cd mu-website
git submodule update --init --recursive
bundle install
jekyll serve --host 0.0.0.0 --force_polling
```

You can then see the output pages at `http://127.0.0.1:4000`:

```
bundle exec jekyll serve
```

The "nortonsw" file is to ensure that the product is accepted by the Norton virus scanner.
