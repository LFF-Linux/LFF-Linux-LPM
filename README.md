# LFF Package Manager (LPM)

LPM is a custom package manager I built for my Linux OS project, LFF Linux. That said, it should work on any Debian-based Linux system with Python installed (tested on Ubuntu 24.04).

LPM lets you install packages from my GitHub organization: [LFF-Linux-Packages](https://github.com/LFF-Linux-Packages).
It is kind of like apt, but not enough to call it apt-like.
I occasionally (once in a blue mooon) create and publish new packages for it, and plan to expand the ecosystem as LFF Linux evolves.

---

## How to install (The easy way)

1. Download the deb from the [latest LPM release](https://github.com/LFF-Linux/LFF-Linux-LPM/releases/latest).  
2. Open the file in your software/package manager.  
3. Install the package, following the instructions from the software/package manager.

## How to install (The hard way)

1. Download the [latest LPM release](https://github.com/LFF-Linux/LFF-Linux-LPM/releases/latest).  
2. Open a terminal and go to the folder that contains the *lpm.py* file.  
3. Run the command:
```bash
sudo cp ./lpm.py /usr/bin/lpm && \
sudo chmod 777 /usr/bin/lpm
```
4. Run `lpm search` to see the available packages. If it works, you are good to go!

## Contributing

Thank you for wanting to contribute to LPM! I need help with some things, so if you are a python wizzard, or a little better than me at code, you can help me implement these features!

* Add support for npm and brew (optional installs, required for some packages I plan to make)
* Let users set custom github organisations as repos
