# AVRProg Metaboard

This is a copy of the [AVR ISP firmware](https://metalab.at/wiki/images/9/95/Avrprog-metaboard-1.1.zip) obtained from the [Avrprog-metaboard page](https://metalab.at/wiki/Avrprog-metaboard).

See the original [Readme.txt](/Readme.txt) for more information.

The initial commit on the repo is the package as precisely I downloaded from metalab.at. The SVN repo linked from that page seems to be defunct.

Some minor changes to make it work:

* Updated the vusb library --- the one bundled with AVRProg was old and no longer compiled;
* changed the USB D- pin for consistency with the current USBaspLoader; and
* added the `flashmetaboard` target in the makefile.

## Copyright and License

The hardware of this programmer are (C) 2008 by Christian Starkjohann and
the USBasp firmware is (C) by Thomas Fischl. All material is licensed under
the terms of the GNU General Public License (GPL) version 2. A copy of the
GPL is included in the firmware, see the file "License.txt" in the "usbdrv" directory.
