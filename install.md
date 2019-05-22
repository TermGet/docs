---
layout: default
title: Install on Linux, BSD, and macOS
nav_order: 5
---

# Install on Linux, BSD, and macOS

### Installing Python3

To install TermGet, we need to install Python 3. Most Linux distributions come with Python 3 out of box. To check if it's already installed, open a terminal window and type:

    python3 --version

If it is not installed, install it off your operating system's respository. The package is most likely named `python3`.
If you are on macOS, install it from Homebrew with `brew install python3` (See `macOS Dependencies` below).

Some operating systems require specific dependencies that need to be installed before TermGet is installed. If your OS is not listed below, skip this step.

### Arch Linux Dependencies

If you are on Arch Linux, you need to install yay in order to use the AUR. To install it, open a terminal window and type:

    sudo pacman -S git
    git clone https://aur.archlinux.org/yay.git
    cd yay
    makepkg -si
    cd ..

### macOS Dependencies

If you are on macOS, you need to install Homebrew. To install it, open a terminal window and type:

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"


### Downloading and Installing TermGet

We are now ready to install TermGet!

Download the latest stable version of TermGet from the [download page](download.html) or by clicking `Download TermGet (stable)` in the top right corner.

Extract TermGet on your system and open a terminal window.

Now set your current directory in the terminal window to the extracted TermGet folder, (e.g. ```cd ~/Downloads/TermGet-x.x.x```).

Now type:

    ./install.sh

If you would prefer to run the installation script without detection of the package manager, add the `--no-detection` flag:

    ./install.sh --no-detection

The above command can be used if the package file already exists from an older build of TermGet. It can also be used if you want TermGet to directly ask you what package manager you would want to use or if you are going to use TermGet with a third-party package manager, such as npm.

TermGet will now install. Please report any errors to the [GitHub Issues](https://github.com/termget/termget/issues).
