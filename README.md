# ultrabay-scripts
## Scripts to manage ThinkPad UltraBay devices 

Scripts to safely dock and undock UltraBay devices of ThinkPads via udev rules.
Also includes a script to switch discharge order to first drain the main
battery in case an UltraBay battery has been inserted.

As Thinkpads with an Ivy Bridge processor (X230, T430, T530, etc.) are not
supported by tp-smapi, the UltraBay battery feature will not work.  This
Thinkpad generation requires tpacpi-bat for battery management, but this has
unfortunately not been packaged for Debian yet.

This was created in context of and for the Debian based ['Window Maker Live'](http://wmlive.rumbero.org)
project. Inspired by and reusing code from http://www.thinkwiki.org/wiki/How_to_hotswap_Ultrabay_devices.

Works fine so far for T23 and T6x generation machines. Haven't tested it on
more modern Thinkpads due to lack of access.

Up to date ready made packages for Debian can be fetched from here:
http://wmlive.rumbero.org/repo. The packaged scripts probably only work
properly on a Debian based system.
