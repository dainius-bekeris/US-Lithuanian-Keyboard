# Lithuanian U.S. Keyboard<br>Lietuviškos raidės U.S. klaviatūros išdėstyme

Why?
====

Switching between US and Lithuanian keyboards is pain. Especially when you need to type numbers, etc.

In Ubuntu there's a keyboard layout named Lithuanian (US keyboard with Lithuanian letters).
The layout works by assigning Lithuanian letters to upper row (numbers) with Alt key.
It is also possible to type Lithuanian letters using macOS "press and hold" feature.

Kodėl?
======

Perjungti tarp JAV ir Lietuvos klaviatūrų yra skausmas. Ypač kai reikia rašyti skaičius ir pan.

Ubuntu yra klaviatūros išdėstymas pavadinimu Lithuanian (JAV klaviatūra su lietuviškomis raidėmis).
Išdėstymas veikia priskiriant lietuviškas raides viršutinei eilutei (skaičiams) su Alt klavišu.
Taip pat galima rašyti lietuviškas raides naudojant macOS "paspausk ir laikyk" funkciją.

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

Then install for all users:

    unzip -o ~/Downloads/Lithuanian.US.bundle.zip -d /Library/Keyboard\ Layouts/

or for current user:

    unzip -o ~/Downloads/Lithuanian.US.bundle.zip -d ~/Library/Keyboard\ Layouts/


Įdiegimas
=========

Įdiegimas:
- Atsisiųskite naujausią versiją
- Išpakuokite paketą (du kartus spustelėkite jį Finder)
- Perkelkite Lithuanian US.bundle paketą į "Keyboard Layouts" aplanką /Library (visiems vartotojams)
  arba ~/Library (tik dabartiniam vartotojui);
- Įjunkite per Input Sources skirtuką Language & Text modulyje System Preferences.

Alternatyva per terminalą:

    wget -O ~/Downloads/Lithuanian.US.bundle.zip https://github.com/dainius-bekeris/US-Lithuanian-Keyboard/releases/download/v1.0.0/Lithuanian.US.bundle.zip

Tada įdiekite visiems vartotojams:

    unzip -o ~/Downloads/Lithuanian.US.bundle.zip -d /Library/Keyboard\ Layouts/

arba dabartiniam vartotojui:

    unzip -o ~/Downloads/Lithuanian.US.bundle.zip -d ~/Library/Keyboard\ Layouts/

