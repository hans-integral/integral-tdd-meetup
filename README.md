# VirtualBox installation

Download and install `VirtualBox`. I used version: `6.1.4,136177`. Any `6.1` version should do.

## Install via Mac OSX
- with Brew installed: `brew cask install virtualbox`.
    - if you see an issue with virtualbox-beta: `brew untap homebrew/versions` and try again.
    - if the installer fails: https://developer.apple.com/library/archive/technotes/tn2459/_index.html
- without Brew installed: download https://download.virtualbox.org/virtualbox/6.1.4/VirtualBox-6.1.4-136177-OSX.dmg

## Install on Windows
- download https://download.virtualbox.org/virtualbox/6.1.4/VirtualBox-6.1.4-136177-Win.exe
- using Chocolatey: `choco install virtualbox`.

## Install on Linux
- Use your package manager (distribution dependant) to install VirtualBox. See https://www.virtualbox.org/wiki/Linux_Downloads for instructions.

# Import the VirtualBox image
[Google Drive link](https://drive.google.com/drive/folders/14dMkBtCQ0d_fdiV0ddSLuV65EbJs97oy?usp=sharing)

Download the Integral-TTD-meetup.ova and Integral-TTD-meetup.vdi files.
In VirtualBox, you can then import this virtual machine via: File > Import Appliance, where you import the Integral-TTD-meetup.ova file.

Recommended amount of RAM: 4096MB, minimal: 2048MB

# Start the image

When you boot the image, you will be presented with an Ubuntu login screen. You can log in with the following credentials.

    Username: integral
    Password: 123meetup

# IntelliJ 

On the virtual machine, there should be an IntelliJ installation. Please open IntelliJ and make sure it works for you.
If it does not work, please contact me at hans@integral.io
