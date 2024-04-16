# Nai

Remove the annoying 'free storage space' pop-ups on Telegram.

## Why?

Because these pop-ups are annoying. Also, there is no way to disable them inside the Telegram app (you can dismiss the pop-ups, but they will reaper after some time).

## Usage

Just install and reboot the device. If you are using LSposed, you just need to mark the "Telegram" package on the list of apps and then kill/force-close the `org.telegram.messenger` process (e.g., by running `/system/bin/am force-stop org.telegram.messenger` on a terminal emulator).

## Supported versions

This module was only tested on Telegram 10.9.1. It might be compatible with older releases, but that is not guaranteed to work.