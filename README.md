<div align="center">
<img width="60px" src="https://pts-project.org/android-chrome-512x512.png">
<h1>PiRogue PPA for Debian 12</h1>
<p>
This PPA contains all the Debian packages to be installed on PiRogue OS to turn a Raspberry Pi into a PiRogue. Want to build one? Follow the guide "<a href="https://pts-project.org/guides/g1/" alt="How to setup a PiRogue">How to setup a PiRogue</a>".
</p>
</div>

## Package sources
All the sources of the packages distributed by this PPA are available at:
- https://github.com/PiRogueToolSuite/deb-packages
- https://github.com/PiRogueToolSuite/pirogue-cli
- https://github.com/PiRogueToolSuite/pirogue-colander-connector
- https://github.com/PiRogueToolSuite/deb-python/tree/debian-12

## Configure the PiRogue repository for Debian 12

To install PiRogue packages repository on your fresh Debian 12 installation, execute the following command in a terminal:

```
sudo curl -o /etc/apt/sources.list.d/pirogue.list https://pts-project.org/debian-12/pirogue.list
sudo curl -o /etc/apt/trusted.gpg.d/pirogue.asc   https://pts-project.org/debian-12/Key.gpg
sudo apt update
```

## Installation on Raspberry Pi
Check the corresponding [documentation on PTS's website](https://pts-project.org/guides/g1/).

## Installation on a regular PC
Check the corresponding [documentation on PTS's website](https://pts-project.org/docs/recipes/turn-a-regular-pc-into-a-pirogue/).
