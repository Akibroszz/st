# st

This is my heavily patched and customised version of the simple terminal (st).

## What is st

ST is a terminal emulator created by the folks at [Suckless](https://suckless.org) created in very few lines meaning that there is very little bloat.
One of the core principles of Suckless programs is that config files are not required, instead requiring you to modify the source code and compile the program.
Luckily a lot of features that are "missing" from st can be added using patches which can be downloaded on the suckless website.

## Patches used

A list of patches used can be found here:

* st-anysize
* st-alpha
* st-font2
* st-ligatures-alpha-scrollback
* st-vertcenter
* st-scrollback
* st-scrollback-mouse
* st-scrollback-mouse-altscreen
* st-scrollback-mouse-increment
* st-dracula (favorite theme)
* st-nordtheme (alternate theme)

## Installing my version of st

Clone the repo to your pc and run ``sudo make clean install``

## Keybinds

All keybinds can be found in the config.def.h file, some of the most important keybinds can be found below.

| Modifier        | Key       | Result                           |
|-----------------|-----------|----------------------------------|
| None            | Scroll    | Scroll trough history            |
| Control         | Scroll    | Zoom in/out                      |
| Control & Shift | -/+       | Zoom in/out                      |
| Control         | =         | Set back to default zoom level   |
| Control & Shift | c         | Copy to clipboard                |
| Control & Shift | v         | Paste                            |
| Shift           | Page Up   | Scroll to top of history         |
| Shift           | Page Down | Scroll down to bottom of history |
