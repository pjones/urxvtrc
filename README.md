# rxvt-unicode: Configuration and Plugins

Peter's urxvt configuration file and scripts (plugins).

## Installation

  1. Replace `@plugins_dir@` in the `config/resources` file with the
     path to the directory where you are going to install the Perl
     scripts from the `plugins` directory.

  2. Either add the contents of the updated `config/resources` file to
     your `~/.Xresources` file, or pass it as an argument to the
     `xrdb` command.

  3. Place all of the files from the `plugins` directory into the
     directory you set in the `config/resources` file.

## Infrequently Asked Questions

  * Q: Why is `saveLines` set to such a small number, are you crazy?

    A: Because I always have `tmux` running in my terminal and it
       handles the scroll-back feature.
