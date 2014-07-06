# Sublime Text Preferences

Check out this repository and symlink it to Sublime Text's Application Support folder to get your settings quick and get to work.

## Instructions

1. Check out this repo:

    ```sh
    $ cd ~/Sites/matthewmcvickar
    $ git clone git@github.com:matthewmcvickar/sublime-text-preferences.git
    ```

1. Symlink:

    ```sh
    $ cd /Users/matthewmcvickar/Library/Application\ Support/Sublime\ Text\ 2/Packages
    $ ln -s ~/Sites/matthewmcvickar/sublime-text-preferences/ User
    ```

1. Oh, and to fix SASS highlighting, go into `Application Support/Sublime Text 2/Packages/Rails/Ruby Haml.tmLanguage` and remove line 8: `<string>sass</string>`.
