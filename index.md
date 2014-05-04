---
layout: default
title: Pandora Radio Client
---

Pithos is a native [Pandora Radio](http://pandora.com) client for Linux. It's much more lightweight
than the Pandora.com web client, and integrates with desktop features such as media
keys, notifications, and the sound menu.

## News

**We are happy to announce the release of Pithos 1.0.0!** This is a huge
release for the project. There are many new features, including a redesigned
UI and icon. We hope you like it! Pithos 1.0.0 requires GTK 3.10+
(Ubuntu 14.04). The release will be available via RPMFusion shortly.
See below for installation instructions.

## Screenshot

![Pithos screenshot](img/screenshot0.2.png)

## Links

- [Downloads](https://github.com/pithos/pithos/releases)
- [Changelog](changelog.html)
- [Source](https://github.com/pithos/pithos)
- [Bug reports](https://github.com/pithos/pithos/issues)
- [Wiki](https://github.com/pithos/pithos/wiki)
- [IRC](ircs://chat.freenode.net/pithos)

## Features

- Play / Pause / Next Song
- Switching stations
- Remembering user name and password
- Cover Art
- Thumbs Up / Thumbs Down / Tired of this song
- Notification popup with song info
- Launching pandora.com song info page and station page
- Reconnecting when pandora session times out
- Editing QuickMix
- Creating stations
- Media Key support
- Proxy support
- Last.fm scrobbling
  
### Not yet implemented

- Browsing genre stations
- Adding songs to stations / move song to another station

## Install

### Ubuntu

    sudo add-apt-repository ppa:pithos/ppa
    sudo apt-get update
    sudo apt-get install pithos

### Fedora

First add the [RPMFusion](http://rpmfusion.org/Configuration) repos. Then:

    sudo yum install pithos
    
### Installing from source

**Note**: Remove any copies installed by a package manager before installing from source

#### Installing dependencies

Package names vary by distribution but here is the list of deps required:

      python3-setuptools python3-dbus python3-gobject python3-pylast
      gstreamer1 gstreamer1-plugins-good gstreamer1-plugins-bad
      gtk3 git (optionally libnotify appindicator3 keybinder3)

#### Download and installation

    git clone https://github.com/pithos/pithos.git
    cd pithos
    sudo python3 setup.py install
    pithos
  
## FAQ

### Why the name "Pithos"?

The original Pandora myth used the word ["pithos"](http://en.wikipedia.org/wiki/Pithos), which was mistranslated to "box";. Similarly, a flash applet is a mistranslation to the Linux platform. 
 
### What does Pithos mean for Pandora?

To support Pandora Media Inc., we recommend subscribing to [Pandora One](http://pandora.com/one).
