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

* `ssh pi@{raspberry-ip-address}`

* the first time you `ssh` onto pi the password is `raspberry`


## Git
- install git `sudo apt install git`

### Connect with Github (Pi)

- [generate ssh keys](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- add public key to github user

## Install Node (Pi)

- [install node & npm](https://www.instructables.com/id/Install-Nodejs-and-Npm-on-Raspberry-Pi/)

## Install Python 3.7

* [Install Python](https://gist.github.com/SeppPenner/6a5a30ebc8f79936fa136c524417761d)

Set python 3.7 to primary version:

* `sudo update-alternatives --config python`
* Might show you an error: `update-alternatives: error: no alternatives for python3 `
* `sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.7 1`


## VSCode remote editing (Pi & Local)
* use [Remote-SSH with vscode](https://code.visualstudio.com/blogs/2019/07/25/remote-ssh)

Remote Web:
*[wcode](https://github.com/fmsouza/wcode)
