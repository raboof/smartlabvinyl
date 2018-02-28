Debian live-build definition for Deventer Smartlab vinyl cutter machine.

Using the Debian live-build tool the configuration in this repository
can be turned into a live cd/usb image.

## Generating

    lb build

## Writing to the USB disk

The resulting .iso can be written to a usb drive by simply copying it to the
correct /dev/sd* device. Be careful to choose the right one, and not
accidentally wipe your hard drive :).
