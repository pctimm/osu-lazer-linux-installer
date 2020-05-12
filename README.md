# News

## 9.5.2020
AppImage Support
Since PPY now regularly releases builds on github in the AppImage format, I added support for downloading and managing those.
AppImages get stored in the appimages/ folder so you can easily switch between current and older builds in case of something going wrong with linux support in PPY's builds.

## 25.12.2019
Add function to quickly start the game with Wayland instead of X11.
Add info that the automatic dependency installer is deprecated.

## 24.12.2019
Update: It took stupidly long and I am sorry for that, but the script is working again.
Lets hope it stays this way for a long long time.
I try to find some time to improve other issues with this project.

## 29.12.2018
A new Stable-and-or-Daily-Build-System, for more info check out the Wiki link
https://github.com/Alexmitter/osu-lazer-linux-installer/wiki/Stable-and-or-Daily-Build-System

# osu!lazer install tool

[![Youtube Video](https://img.youtube.com/vi/doMdNU4I-u4.jpg)](https://www.youtube.com/watch?v=doMdNU4I-u4 "osu!lazer installer")

osu!lazer is the new early development open source version of osu!

This script helps you build, maintain and play on the latest build without any stress on your favorite Linux distribution.

## Easy instructions for new users

`sudo apt install dialog git`

`git clone https://github.com/Alexmitter/osu-lazer-linux-installer.git`

`cd osu-lazer-linux-installer`

`bash start.sh`

Dependencies are only needed if you plan to compile osu!lazer with this tool, you can ignore if you plan to use the AppImages functionality only.
Please, do not use the automatic dependency installer.
Use the Manual Dependency Installation informatin in the Wiki
https://github.com/Alexmitter/osu-lazer-linux-installer/wiki/Manual-Dependency-install

Void Linux Users: https://github.com/Alexmitter/osu-lazer-linux-installer/wiki/Void-Linux:-Dependency-Installation
