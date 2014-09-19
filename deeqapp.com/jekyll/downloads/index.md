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

The Deeq program is a specially crafted 32-bits [Command-Line](http://en.wikipedia.org/wiki/Command-line_interface) application, it's available for both OSX and Linux.

The CLI application will inform you when there is a new version available, however, it doesn't install the new version automatically. You need to use the distribution mechanism to install newer versions.

#### Brew

Initial setup and updates managed through [Homebrew](http://brew.sh/):

    $ brew install deeq

#### OSX/Linux executable (Advanced)

This shell downloads and installs Deeq in your OSX or Linux system as an independently distributed executable in `/usr/local/bin`: 

    $ (curl -rSL http://dl.bithavoc.io/deeq/releases/latest.sh | bash)
