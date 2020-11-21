### About

DSBXinput is a graphical tool which uses *xinput* to configure pointing devices.

### Installation
#### Dependencies
* lang/python37
* devel/py-qt5-core
* x11-toolkits/py-qt5-gui
* x11-toolkits/py-qt5-widgets
* x11/xinput
* devel/qt5-linguisttools

#### Building and installation

    # git clone https://github.com/mrclksr/DSBXinput.git
    # cd DSBXinput && make install

### Setup

DSBXinput saves the current mouse/touchpad configuration in the executable
shell script `~/.config/DSB/dsbxinput.sh`. Make sure it gets executed on
session start by adding the line `~/.config/DSB/dsbxinput.sh&` to your
`~/.xinitrc`, `~/.xsession`, or your window manager's autostart file.
