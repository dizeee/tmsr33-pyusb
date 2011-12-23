TMSR33 Magnetic Card Reader in Linux
====================================

The [T-MSR-33](http://www.barcode-manufacturer.com/magnetic_card/portable_magstripe/magnetic_card_reader_specification.html) magnetic card reader
is a cheap unit easily found that exists in USB, PS2 and TTL version. This
code makes support for the USB version of that device using pyusb and libusb.
Though, it shall work with most devices that "acts like a keyboard" out of the 
box.

This version of the code does not include Credit Card data extraction,
but implements recognition of Magnetic Card readers that act like HID
USB Keyboards, and thus retrieves the keycodes and returns an exploitable
string. Blog post explaining what I've done is to come.

This code is forked from [the code written by MicahCarrick](https://github.com/MicahCarrick/magtek-pyusb).
Read a complete description of his example program on 
[my blog](http://www.micahcarrick.com/credit-card-reader-pyusb.html)


