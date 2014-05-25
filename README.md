gedit-repl
==========

A simple extension of Gedit Terminal to support REPL commands. Use `<Ctrl><Return>` to send the current selection or row to the terminal in the bottom tab.

Currently this uses the classes of the Terminal plugin, so both plugins can not be activated at the same time (drop-in replacement).

Installation
------------

* Copy gedit-repl.py and gedit-repl.plugin to ~/.local/share/gedit/plugins

* In Gedit Preferences: Deactivate Terminal plugin and activate 'REPL'

Usage
-----

`<Ctrl><Return>` sends the currently selected text to the bottom terminal. If no text is selected the whole line is sent.

FAQs
----

#### Indentation in IPython does not work

Call IPython with --no-autoindent.
