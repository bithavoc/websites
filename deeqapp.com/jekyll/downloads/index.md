---
layout: page
title: Downloads
permalink: /downloads/
weight: 0
---

### Applications 

Desktop applications to use in Mac OSX.

#### Mac AppStore (Recommended)

Initial setup and updates managed through the Mac AppStore.

[Install from the AppStore](https://itunes.apple.com/us/app/deeq/id906558269?mt=12&uo=4)

#### Cask

Initial setup and updates managed through [Cask](http://caskroom.io/):

    $ cask install deeq

### CLI Programs

The Deeq program is a specially crafted [Command-Line](http://en.wikipedia.org/wiki/Command-line_interface) application, it's available for OSX and Linux.

This script downloads and installs Deeq in your OSX/Linux system as an independently distributed executable in `$HOME/.deeq`.

Install using cURL(installed by default in OSX):

    $ (curl -rSL http://dl.bithavoc.io/deeq/releases/posix-install.sh | bash)

Install using wget(installed by default in Linux):

    $ (wget -qO- http://dl.bithavoc.io/deeq/releases/posix-install.sh | bash)

The CLI application will inform you when there is a new version available, however, it doesn't install the new version automatically. To install the latest version, run the same command again.
