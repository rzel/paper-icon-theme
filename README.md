Paper Icon Theme
================

Paper is a modern freedesktop icon theme whose design is based around the use of bold colours and simple geometric shapes to compose icons. Each icon has been meticulously designed for pixel-perfect viewing.

While it does take some inspiration from the icons in Google's Material Design, some aspects have been adjusted to better suit a desktop environment.

###Copying or Reusing

Paper is licenced under the terms of the [Creative Commons Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/). When reusing this work be sure to include a proper attribution:

"[Paper Icons](http://snwh.org/paper/icons)" by [Sam Hewitt](http://samuelhewitt.com/) is licensed under [CC-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/)

Software that is included is free software; you can redistribute it and/or modify it under the terms of the [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.txt)

###Downloading Paper

Download instructions and options are available on the [official site](https://snwh.org/paper/download).

###Install

You can install or update Paper on-demand via the provided `.desktop` file. Moving it to your local applications folder will allow it to appear in your applications menu.

	cp -r org.snwh.paper.icons.desktop ~/.local/share/applications

###Build From Source

You can build and install the Paper icon themes from source:

    ./autogen.sh
    make
    sudo make install

This procedure requires ```autotools``` on your system.

##Missing Icons & Requests

When filing an icon request or reporting a missing icon, please take care in providing the following useful information: 

 - A screenshot of your issue or an image of the original icon you are requesting to be themed
 - The file name for the missing icon or the requested icon, for example `gimp.png` or `system-shutdown.svg`
 - A short description of the application or software that you are requesting an icon for.

Note: some software ships hardcoded icons, meaning when you install icons are not placed in the system-wide directory `/usr/share/icons` which makes them unthemeable.

##Help & Support

You can visit the support channel `#Paper-Chat` on Freenode for questions and discussion.
