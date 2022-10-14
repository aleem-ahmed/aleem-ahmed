# LINUX MINT SETUP NOTES

## time format

%l:%M:%S %p  [%m/%d]


## WEKA data examples location

/usr/share/doc/weka/examples

### To make lock screen time not move use

gsettings set org.cinnamon.desktop.screensaver floating-widgets false


## VS Code Extension List
- Bracket Pair Colorizer
- Debugger for Java
- Java Dependency Viewer
- Java Extension Pack
- Java Test Runner
- Language Support for Java(TM) by Red Hat
- Material Icon Theme
- Maven for Java
- React Native Tools
- Simple React Snippets
- Vetur
- Visual Studio IntelliCode
- Vue 2 Snippets

## Install Snapcraft

https://snapcraft.io/install/heroku/mint


## Install Nvidia Drivers

```
sudo apt install nvidia-driver-440
```

## Install drivers for WIFI

```
sudo apt install dkms
git clone https://github.com/aircrack-ng/rtl8812au
cd rtl8812au
make && sudo make install
reboot
```

## MongoDB Local URI

mongodb://localhost:27017/?readPreference=primary&appname=MongoDB%20Compass&ssl=false

