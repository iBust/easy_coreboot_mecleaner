# easy-coreboot
The easiest possible way to install coreboot and me_cleaner on Lenovo Thinkpads (t430, t440p, t530, w530, x230, x230t) for non-technical users.

The only easiest way is to buy a corebooted device on ebay, a System76 or Prism device (there are other brands, Prism had controversy on disabling vs neutralizing IME, beware). 

Of course you can always verify with https://github.com/corna/me_cleaner/wiki/Get-the-status-of-Intel-ME to get the status of IME

Tested on over dozens of thinkpads

This tutorial is based on the incredible work of:

- Martin Kepplinger Skulls

https://github.com/merge/skulls

- Connor Burns coreboot tutorial 

https://blog.0xcb.dev/lenovo-t440p-coreboot/

Before starting you need the following:

1. Compatible Lenovo Thinkpad (*t430, t440p, t530, w530, x230, x230t*)
2. Raspberry Pi 3 and a MicroSD card for the OS of your Pi.
3. SOIC8 or SOIC16 Clip (beware of cheap clips and cheap SPI Flasher that can damage your board) *Pomona 5250/5252 is recommanded for 8pins/16pins bios chip*
4. Breadboard Jumper Wires (Female/Female)
5. Keyboard/Mouse (USB or Bluetooth)
6. Screen with an HDMI cable
