---
layout: post
title: "Kamidori battle animation glitches"
date: 2017-11-27 00:00:00
img: 2017-11-27-kamidori-battle-animation-glitches.png
description: Weird audio/video corruption that happens during attack sequences.
hidden: false
---
Symptoms
--------
- When you hit someone or if you are being hit, you see some graphical corruption,
mainly during and after some kind of particles are shown.
- Sometimes, like during preemptive strike, game freezes and some seemingly
unrelated sound effects play before eventually the game speeds-up to catch up.

Cause
-----
Most likely this happens due to 3rd-party video filters.  
In my case the culprit is LAVFilters (most recent ones, vanilla) and I will be
explaining how to deal with them. In case you use anything else (which you
shouldn't), you will have to figure out the solution yourself. I recommend
uninstalling whatever codec ~~craps~~ packs you may have and clean-up whatever
they could leave behind as a first step.

Solution
--------
Add the following to your windows registry:
```php
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\LAV\Audio\Blacklist]
"AGE.EXE"=dword:00000001
"Kamidori English.exe"=dword:00000001

[HKEY_CURRENT_USER\Software\LAV\Splitter\Blacklist]
"AGE.EXE"=dword:00000001
"Kamidori English.exe"=dword:00000001
```

Alternatively, you can disable `MPEG-PS`, `MPEG-TS` and `MP2` formats in LAV settings.
