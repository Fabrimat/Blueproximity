# 1.2.5
`double kill, multi kill, monster kill, rampage!` 2008.02.28
* info: This is an unstable release preparing 1.2.6 - it has incomplete translations too
* fixed: No runtime errors on scanning while still connecting (Bug #1892724)
* fixed: correct inheriting of classes from 'object' (Bug #1892724)
* fixed: you are now told if your config files are broken (at least on the console) (Bug #1781957)
* fixed: commands not ending will now not make blueproximity hang
* added: french translation is back, thanks Claude
* added: log file notice on hanging commands
* added: support for multiple config files via *.conf files in ~/.blueproximity
* added: new configurations can be added, deleted, renamed via gui
* added: new locale hu - thanks Kami
* modified: old config file is gone, it should now reside in directory ~/.blueproximity
* modified: much more Doxygen documentation in the source
* modified: proximity command has moved into Proximity class

# 1.2.4
`keep releasing` 2008.02.09
* added: support for russian language - thanks Alexey

# 1.2.3
`do it the ubuntu way` 2008.02.09
* modified: many small thnigs to get upstream compliance to all ubuntu policies
* modified; changed source to support the old and the newer pybluez _bluetooth import variants

# 1.2.2
`fix it, fix it, fix it` released 2008.01.31
* fixed: errors during imports can now be translated and don't lead to an error (Bug #1881000)
* fixed: now the "Use selected device" button works again - shame on me... (Bug #1878304)
* added: now we have a (rather uninteresting) man page (Bug #1841869)

# 1.2.1
`I'll be back` 2007.11.22
* fixed: proximity command now only executes if proximity detected and not paused (Bug #1835488)
* added: some tool tips should help the initial user
* added: new channel setting via GUI (Bug #1772585)
* added: scan for usable channels on a device (Bug #1772585)
* added: more error messages if external packages are missing

# 1.2
`call me HIG` 2007.09.11
* fixed: unlock command was always executed at start-up
* fixed: MAC address is now being saved even if nothing else changed (Bug #1781579)
* fixed: preferences window may now be closed using the X button of the window manager (thx to Zsolt Mazolt)
* added: lock/unlock commands now can be changed via GUI (notebook tab 'Locking')
* added: logging functions to log to syslog or file
* added: proximity command which will be fired at given interval while proximity is detected (possible use: never activate screensaver while near)
- added: we are now multilingual - see the .pot file. English and German in included (thx to Mark Mruss and www.learningpython.com) (Bug #1772603)
* added: language French (Claude - f5pbl@users.sourceforge.net)
* added: language Farsi (Ali Sattari - ali.sattari@gmail.com)
* added: language Spanish (César Palma - cesarpalma80@gmail.com)
* added: language Swedish (Daniel Nylander - dnylander@users.sourceforge.net)
* modified: scanning now shows by message and watch cursor (Bug #1776732)
* modified: every control directly accessible via keyboard (Bug #1776732)
* modified: layout optimized by Tobias Jakobs (Bug #1776732)
* modified: control range optimized to possible value range (Bug #1776732)
* modified: gnome screensaver now locks the screen no matter what its settings say (Bug #1778306)
* modified: new program info dialog accessible via icon's context menu (Bug #1776732)
* modified: preferences dialog now has a proper icon (Bug #1776732)
* modified: preferences dialog now accessible via 'preferences' entry in icon's context menu (Bug #1776732)
* modified: preferences dialog now does auto-save and auto-activate values - changes are active immediately (Bug #1776732)
* modified: info replaces old apply button which was no longer needed (Bug #1776732)
* modified: switched to new, scalable icon set by Tobias and me
* modified: changed allowed settings for ranges and durations to limits given by the GUI.

# 1.1
`see what's coming` 2007.08.18
* fixed: icon shows connecting process
* fixed: no window flicker on start-up (Bug #1772241)
* fixed: first window not displaced at upper left corner (Bug #1772241)
* fixed: wrong set MAC when no config file exists, now shows correctly "not configured" in icon tool-tip
* added: start-up script start_proximity.sh to be run from anywhere (link it in your session start-up)
* added: automatically show settings screen on first start-up (Feature #1772589)
* added: pause mode via icon's context menu (Feature #1776527)
* added: Ubuntu Feisty package (Feature #1772590)
* modified: some aspects regarding easier packaging
* modified: logo
* modified: switching most bt functions to pybluez, only rssi detection relies on hcitool

# 1.0
`the not final one` 2007.08.11
initial public release
