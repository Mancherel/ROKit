ROKit
=====
## Responsive Optimization Kit
2014-11-19 Telegraph Hill, San Francisco. This is where it begins. /Magnus Blix
### What is this sorcery?

ROKit is a javscript kit helping you accomplish thoose impossible quests your art director often gives you.

The base of the script is a media query detector and eventhandler for thoose screen resizes thay may occure with users flipping, draging, dropping or resizing their screens, or if content is magically added with asyncronous calls.

- Scanner (rokit.scanner) - let your js funtions know the dirty details about the client screen, also adds event if the screen changes.

The extent of the script is a number of functions making those impossible css hack possible.

- Equalibrium (rokit.equal) - Since no one dares to use flexbox yet, this will equalize height of columns.
- Middler (rokit.middle) - those situations when css table is not possible, center content vertically in containers.
