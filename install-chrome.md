---
layout: default
title: Install on ChromeOS
nav_order: 6
---

# Install on ChromeOS

### Warning: TermGet on ChromeOS is not officially supported. TermGet on ChromeOS is also super buggy.

First put your Chromebook in [developer mode](https://www.howtogeek.com/210817/how-to-enable-developer-mode-on-your-chromebook/ "developer mode").

Now, open Crosh (`CTRL + ALT + T`), and type ```shell```. Check if Python 3 is already installed on your system by typing:

    python3 --version

If it is installed, continue to the next step.

If Python 3 is not installed, follow the instructions [here](https://wsvincent.com/install-python3-chromebook/) to install it.

Once you have installed Python 3, we need to install Chromebrew. To install it, type:

    wget -q -O - https://raw.github.com/skycocker/chromebrew/master/install.sh | bash

We are now ready to install TermGet!

Download the latest stable version of TermGet from the [download page](download.html) or by clicking `Download TermGet (stable)` in the top right corner.

Extract TermGet on your system and go back to Crosh.

Now set your current directory in Crosh to the extracted TermGet folder, (e.g. ```cd ~/Downloads/TermGet-x.x.x```).

To install, type:

    bash install.sh

If you would prefer to run the installation script without detection of the package manager, add the `--no-detection` flag:

    bash install.sh --no-detection

The above command can be used if the package file already exists from an older build of TermGet. It can also be used if you want TermGet to directly ask you what package manager you would want to use or if you are going to use TermGet with a third-party package manager, such as npm.

TermGet will now install. Please report any errors to the [GitHub Issues](https://github.com/termget/termget/issues).
