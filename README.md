# ultrabay-scripts
## Management of ThinkPad UltraBay devices and batteries

Scripts to safely dock and undock UltraBay devices of ThinkPads via udev rules.
Also includes a script to switch discharge order to first drain the main
battery in case an UltraBay battery has been inserted.

As Thinkpads with an Ivy Bridge processor (X230, T430, T530, etc.) are not
supported by tp-smapi, the UltraBay battery feature will not work.  This
Thinkpad generation requires tpacpi-bat for battery management, but this has
unfortunately not been packaged for Debian yet.

This was created in context of and for the Debian based 'Window Maker Live'
project. The principal scripts probably only work properly on a Debian based
system.
