# Lithuanian US Keyboard

Why?
====

Switching between US and Lithuanian keyboards is pain. Especially when you need to type numbers, etc.

In Ubuntu there's a keyboard layout named Lithuanian (US keyboard with Lithuanian letters).
The layout works by assigning Lithuanian letters to upper row (numbers) with Alt key.
It is also possible to type Lithuanian letters using macOS "press and hold" feature.

Installation
============

Installation:
- Download latest release
- Unzip package (double click on it in Finder)
- Move Lithuanian US.bundle bundle to the "Keyboard Layouts" folder within /Library (for all users)
  or ~/Library (for current user only);
- Enable via the Input Sources tab of the Language & Text module within System Preferences.

Alternative via shell:

    wget -O ~/Downloads/Lithuanian.US.bundle.zip https://github.com/dainius-bekeris/US-Lithuanian-Keyboard/releases/download/v1.0.0/Lithuanian.US.bundle.zip

Then install for all users

    unzip -o ~/Downloads/Lithuanian.US.bundle.zip -d /Library/Keyboard\ Layouts/

or for current user:

    unzip -o ~/Downloads/Lithuanian.US.bundle.zip -d ~/Library/Keyboard\ Layouts/

