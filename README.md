## Flash with Etcher (Local – SD card)
Download latest raspian:
* https://www.raspberrypi.org/downloads/raspbian/

* 434 MB, 1.136 MB, 2.230 MB versions

Mac using UI:
`sudo /Applications/balenaEtcher.app/Contents/MacOS/balenaEtcher`

* After the OS is flashed onto SD card, reinsert the card before following next steps.

## ssh (Local – SD card)
Create a file in the `boot` directory to enable ssh
`touch /Volumes/boot/ssh`

With this setup, it is possible to `ssh` onto the raspberry pi using usb.
## SSH via Wifi (Local – SD card):

- [wifi w/o ethernet](https://howchoo.com/g/ndy1zte2yjn/how-to-set-up-wifi-on-your-raspberry-pi-without-ethernet)
- [Mobile Hotspot (iOS](https://www.techcoil.com/blog/how-to-connect-your-raspberry-pi-to-your-iphone-wifi-hotspot-via-raspbian-stretch-lite/)

## Connect with Github (Pi)

- [generate ssh keys](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- add public key to github user

## Install Node (Pi)

- [install node & npm](https://www.instructables.com/id/Install-Nodejs-and-Npm-on-Raspberry-Pi/)

## VSCode remote editing (Pi & Local)

Remote to Local:
- [rmate](https://github.com/textmate/rmate)
- [install ruby](https://www.raspberrypi.org/documentation/linux/software/ruby.md)
- [vscode setup](https://ladvien.com/visual-studio-code-raspberry-pi/)

Remote Web:
*[wcode](https://github.com/fmsouza/wcode)
