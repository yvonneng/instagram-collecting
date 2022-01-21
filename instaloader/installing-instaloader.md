---
title: Installing Instaloader
layout: page
parent: Instaloader
nav_order: 1
---
# Installing Instaloader

## Opening the Command Line Interface
Everything here will be done in the command-line (i.e. text-based rather than graphical user interface), so you will be using the Terminal app. 

Terminal can be found in `Applications > Utilities > Terminal`.

## Getting Set Up
Don’t get discouraged with this part. Installing and setting up is the hardest (and most tedious) part. Get through this, and you’ll be smooth sailing!

Things you will need to install, with instructions below:

1. [XCode](https://apps.apple.com/us/app/xcode) part of MacOS, but for software developers. Has stuff you need in it. 
2. [Homebrew](https://brew.sh/index_cs) - this is a tool to help you install the other things. 
3. [Python3](https://www.python.org/download/releases/3.0/) and [pip3](https://pip.pypa.io/) - Instaloader is written in Python, so you need it. Pip is a tool for installing Python packages.
4. [Instaloader](https://instaloader.github.io/)! 
5. ? There may be other little dependencies that you will need to install that I’ve missed, since I wasn’t starting from scratch on my computer. But you will probably receive feedback/instructions in Terminal telling you if something’s missing and what you need to do if so. 

### Install XCode
Download it from the App Store and install like any app. Sorry it’s a big download. 

### Install Homebrew
In Terminal, copy/paste the following line and hit enter:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

You’ll see a bunch of text output in the Terminal.  If it asks you something (e.g. for a password) or tells you to do something (like how to install something else you need), just follow the instructions it gives you.

It might take a while. You’ll know it’s done when Terminal gives you a new command prompt (i.e. a line with a $ that you can type new commands into).

### Install Python3
In Terminal, install Python3 using Homebrew. Copy/paste the following and hit enter:
```
brew install python3
```

### Install Pip3
I think pip is included in the Python installation, but you can run this just in case. In Terminal, copy/paste and hit enter:
```
python3 -m pip install --upgrade pip
```

### Install Instaloader
In Terminal, copy/paste the following and hit enter:
```
pip3 install instaloader
```
