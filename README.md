# GnuPG-Smartcard-Scripts
Some helper scripts for GnuPG and the OpenPGP-Smartcard (or similar cards)

The `smartcard-init.desktop` file is for initializing the smartcard after normal booting.

The script `scd-event` activates and deactivates the screensaver if the Smartcard is removed or brought back.

The two scripts `cryptgnupg_sc` and `decrypt_gnupg_sc` are used for decrypting a LUKS key with GnuPG in the initrd. `cryptgnupg_sc` copies all the relevant files into the ramdisk. `decrypt_gnupg_sc` is used in the ramdisk to fire up GnuPG.
