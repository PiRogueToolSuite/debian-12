<div align="center">
<img width="60px" src="https://pts-project.org/android-chrome-512x512.png">
<h1>ViRogue PPA for Debian 12</h1>
<p>
<b>WARNING:</b> This PPA contains <em>work-in-progress</em> packages regarding
the “let's virtualize the PiRogue” project. It is only meant to be used by
developers during the initial development phase. Please use
<a href="https://github.com/PiRogueToolSuite/debian-12">the regular PPA</a>
to deploy on a Raspberry Pi 3, 4, or 5.
</p>
</div>

## Package sources

All the sources of the packages distributed by this PPA are available at:

- https://github.com/PiRogueToolSuite/deb-packages/tree/virogue
- https://github.com/PiRogueToolSuite/pirogue-admin/tree/main
- https://github.com/PiRogueToolSuite/pirogue-colander-connector/tree/main
- https://github.com/PiRogueToolSuite/deb-python/tree/debian-12

## Configure the **ViRogue** repository for Debian 12

To install PiRogue packages repository on your fresh Debian 12 installation, execute the following command in a terminal:

```
sudo wget -O /etc/apt/sources.list.d/pirogue.list https://pts-project.org/debian-12-virogue/pirogue.list
sudo wget -O /etc/apt/trusted.gpg.d/pirogue.gpg   https://pts-project.org/debian-12-virogue/pirogue.gpg
sudo apt update
```
