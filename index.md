---
layout: default
title: Pandora Radio Client
---

Pithos is a native [Pandora Radio](http://pandora.com) client for Linux. It's much more lightweight
than the Pandora.com web client, and integrates with desktop features such as media
keys, notifications, and the sound menu.

## Screenshot

![Pithos screenshot](img/screenshot0.2.png)

## Links

- [Changelog](changelog.html)
- [GitHub (source code)](https://github.com/pithos/pithos)
- [Bug reports](https://github.com/pithos/pithos/issues)

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

    sudo add-apt-repository ppa:kevin-mehall/pithos-daily
    sudo apt-get update
    sudo apt-get install pithos

### Fedora

We hope to have Pithos in RPMFusion for the release of 1.0 but until then you can use [TingPing](https://github.com/TingPing)'s repo (requires [RPMFusion](http://rpmfusion.org/Configuration)):

    sudo yum-config-manager \
      --add-repo http://dl.tingping.se/fedora/tingping.repo
    sudo yum install pithos
    
### Installing from source

**Note**: Remove any copies installed by a package manager before installing from source

#### Installing dependencies

##### Debian/Ubuntu

    sudo apt-get install \
      python-setuptools python python-xdg python-dbus \
      python-gobject python-gst0.10 python-notify python-gtk2 \
      gstreamer0.10-plugins-good gstreamer0.10-plugins-bad git-core

#### Download and installation

    git clone https://github.com/pithos/pithos.git
    cd pithos
    sudo python setup.py install
    pithos
  
## FAQ

### Why the name "Pithos"?

The original Pandora myth used the word ["pithos"](http://en.wikipedia.org/wiki/Pithos), which was mistranslated to "box". Similarly, a flash applet is a mistranslation to the Linux platform. 
 
### What does Pithos mean for Pandora?

To support Pandora Media Inc., we recommend subscribing to [Pandora One](http://pandora.com/one).
