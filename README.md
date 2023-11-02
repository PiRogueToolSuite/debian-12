## Configure the PiRogue repository for Debian 12

To install PiRogue packages repository on your fresh Debian 12 installation, execute the following command in a terminal:

```
sudo curl -o /etc/apt/sources.list.d/pirogue.list https://pts-project.org/debian-12/pirogue.list
sudo curl -o /etc/apt/trusted.gpg.d/pirogue.asc   https://pts-project.org/debian-12/Key.gpg
sudo apt update
```

## Installation on Raspberry Pi
Check the corresponding [documentation on PTS's website](https://pts-project.org/docs/pirogue/build-a-pirogue/).

## Installation on a regular PC
Check the corresponding [documentation on PTS's website](https://pts-project.org/docs/recipes/turn-a-regular-pc-into-a-pirogue/).
