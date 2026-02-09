+++
title = "Cool Things on Linux"
date = "2026-02-08T21:08:42Z"
author = "Leo"
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["linux", "easter egg"]
keywords = ["linux", ""]
description = "Some cool commands on Linux that you may have not heard before"
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
draft = true
+++

# Some cool commands on Linux that you may have not heard before

## Apt
When I was using Termux, I typed `apt` to check how to use it. This is its output:
```
apt 2.8.1 (aarch64)
Usage: apt [options] command

apt is a commandline package manager and provides commands for
searching and managing as well as querying information about packages.
It provides the same functionality as the specialized APT tools,
like apt-get and apt-cache, but enables options more suitable for
interactive use by default.

Most used commands:
  list - list packages based on package names
  search - search in package descriptions
  show - show package details
  install - install packages
  reinstall - reinstall packages
  remove - remove packages
  autoremove - automatically remove all unused packages
  update - update list of available packages
  upgrade - upgrade the system by installing/upgrading packages
  full-upgrade - upgrade the system by removing/installing/upgrading packages
  edit-sources - edit the source information file
  satisfy - satisfy dependency strings

See apt(8) for more information about the available commands.
Configuration options and syntax is detailed in apt.conf(5).
Information about how to configure sources can be found in sources.list(5).
Package and version choices can be expressed via apt_preferences(5).
Security details are available in apt-secure(8).
                                        This APT has Super Cow Powers.
```

Look at the last line.
```
This APT has Super Cow Powers.
```
It says it has `Super Cow Powers`! So I [duckduckgo'd]({{< relref "duckduckgo.md" >}}) it. I found the cool command `apt moo`! Now let's try it:
```bash
~ $ apt moo
                 (__)
                 (oo)
           /------\/
          / |    ||
         *  /\---/\
            ~~   ~~
..."Have you mooed today?"...
```
Isn't it cool?

---

## Typo
Have you ever typed `sl` accidentally when you wanted `ls` to list directory contents? If you ever have, you must try this!

Installation  
`apt`:
```bash
sudo apt install sl
```
`dnf`:
```bash
sudo dnf install sl
```
`yum`:
```bash
sudo yum install epel-release -y # You may need to run this first
sudo yum install sl -y
```
`pacman`:
```bash
sudo pacman -S sl
```

Then the next time you accidentally type `sl`, you'll have to smile!
```
                          (  ) (@@) ( )  (@)  ()    @@    O     @     O     @
                     (@@@)
                 (    )
              (@@@@)

            (   )
        ====        ________                ___________
    _D _|  |_______/        \__I_I_____===__|_________|
     |(_)---  |   H\________/ |   |        =|___ ___|      _________________
     /     |  |   H  |  |     |   |         ||_| |_||     _|                \___
    |      |  |   H  |__--------------------| [___] |   =|
    | ________|___H__/__|_____/[][]~\_______|       |   -|
    |/ |   |-----------I_____I [][] []  D   |=======|____|______________________
  __/ =| o |=-~~\  /~~\  /~~\  /~~\ ____Y___________|__|________________________
   |/-=|___|=O=====O=====O=====O   |_____/~\___/          |_D__D__D_|  |_D__D__D
    \_/      \__/  \__/  \__/  \__/      \_/               \_/   \_/    \_/   \
```

---

## Command combo
`apt`:
```bash
sudo apt install fortune cowsay
```
`dnf`:
```bash
sudo dnf install fortune-mod cowsay
```
`pacman`:
```bash
sudo pacman -S fortune cowsay
```

