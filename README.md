Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.

Requirements
------------

1) Install a C compiler.

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action).

2) Set zsh as your login shell.

    chsh -s /bin/zsh

Install
-------

Run the script:

    zsh < <(curl -s https://raw.github.com/brighbit/laptop/master/mac)

What it sets up
---------------

* Ack for finding things in files
* Bundler gem for managing Ruby libraries
* Heroku gem for interacting with the Heroku API
* Homebrew for managing operating system libraries
* ImageMagick for cropping and resizing images
* Memcache for testing caching
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Ruby stable for writing general-purpose code
* SSH public key for authenticating with Github and Heroku
* Tmux for saving project state and switching between projects

It should take less than 15 minutes to install (depends on your machine).

Credits
-------
Original script by thoughtbot at: [thoughtbot/laptop](http://github.com/thoughtbot/laptop).
