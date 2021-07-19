### About

DSBXinput is a graphical tool which uses *xinput* to configure pointing devices.

### Installation
#### Dependencies
* lang/python38
* devel/py-qt5-core
* x11-toolkits/py-qt5-gui
* x11-toolkits/py-qt5-widgets
* x11/xinput
* devel/qt5-linguisttools
* textproc/py-qt5-xml (for pylupdate5)

#### Building and installation

    # git clone https://github.com/mrclksr/DSBXinput.git
    # cd DSBXinput && make install

### Setup

DSBXinput saves the current mouse/touchpad configuration in the executable
shell script `~/.config/DSB/dsbxinput.sh`. If your window manager or desktop
environment does not support XDG autostart, make sure it gets executed on
session start by adding the line `~/.config/DSB/dsbxinput.sh&` to your
`~/.xinitrc`, `~/.xsession`, or your window manager's autostart file.

