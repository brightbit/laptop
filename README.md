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

    zsh < <(curl -s https://raw.github.com/brightbit/laptop/master/mac)

What it sets up
---------------
* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Heroku Config plugin for local ENV variables
* Heroku Toolbelt for interacting with Heroku apps
* Hub gem for interacting with the GitHub API
* Homebrew for managing operating system libraries (OS X only)
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Rails gem for writing web applications
* Ruby stable for writing general-purpose code
* SSH public key for authenticating with Github and Heroku
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* Watch for periodically executing a program and displaying the output

It should take less than 15 minutes to install (depends on your machine).

Credits
-------
Original script by thoughtbot at: [thoughtbot/laptop](http://github.com/thoughtbot/laptop).
