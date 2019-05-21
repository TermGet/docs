---
layout: default
title: Install on ChromeOS
nav_order: 6
---

# Install on ChromeOS

### Warning: TermGet on ChromeOS is not officially supported. TermGet on ChromeOS is also super buggy.

First put your Chromebook in [developer mode](https://www.howtogeek.com/210817/how-to-enable-developer-mode-on-your-chromebook/ "developer mode").

Now, Open Crosh, and type ```shell```. Check if Python3 is already installed on your system. Do so by typing

    python3 --version

If it is your good to go to the next step.

If not, then [watch this video](https://youtu.be/X7Y8b2S3nEA)

If you would rather read instead of a video, [click here](https://wsvincent.com/install-python3-chromebook/)

Once you have installed python, we need to install Chromebrew. To do this type:

    wget -q -O - https://raw.github.com/skycocker/chromebrew/master/install.sh | bash

    -- or --

    curl -Ls git.io/vddgY | bash

Now download TermGet and cd into it, then run

    bash install.sh

and it will install, if you get errors report it to the github issues.

That's it, type "termget" into the prompt and you should be good.
