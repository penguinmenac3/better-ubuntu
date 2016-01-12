# Better Ubuntu

Initialisation scripts and tools that make your ubuntu better.

This is a project that aims to provide some easy to install tools for ubuntu. These tools are build ontop of ubuntu and assume that you have a clean install to start with.

# How to install with ui configuration

Download the zip. Extract it and start the install_graphical.sh

```bash
wget https://github.com/penguinmenac3/better-ubuntu/archive/master.zip
unzip master.zip
mv better-ubuntu-master better-ubuntu
cd better-ubuntu
./install_graphical.sh
```

Follow the instructions.

![Follow the instructions](https://raw.githubusercontent.com/penguinmenac3/better-ubuntu/master/images/packages-ui.png)

# How to install without configuration

Simply download the install.sh make it executable and run it.

```bash
wget https://raw.githubusercontent.com/penguinmenac3/better-ubuntu/master/scripts/install.sh
chmod +x install.sh
./install.sh
```

Then configure what you want to install and what you don't need/want by following the instructions given by the program.

Now let your computer do all the heavy duty stuff.

# What is done

## Install List
The following is done only once.

1. Apport disabled
2. Add ppa for: Oracle Java 8, Sublime 3, Cinnamon, Numix
3. Add spotify repo
4. Download and install Chrome-Latest
5. Download and install TeamSpeak 3
6. Download and install Synology Cloud Station
7. Install Sublime 3 and Oracle Java 8
8. Install and update software in the software list

## Software List
The following software is installed and updated

* chromium-browser
* cinnamon
* cmake
* gimp
* git
* gnome-tweak-tool
* htop
* ipython
* josm
* keepass2
* ninja-ide
* numix-gtk-theme
* numix-icon-theme-circle
* numix-wallpaper-*
* openssh-server
* python-pip
* python-pyglet
* python-wxgtk2.8
* qtcreator
* qt4-designer
* sl
* spotify-client
* steam
* texmaker
* tmux
* unity-tweak-tool
* virtualbox
* vlc
