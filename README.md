# cutefish-dock
Desktop Taskbar

You also need [`fishui`](https://github.com/cutefishos/fishui) and [`libcutefish`](https://github.com/cutefishos/libcutefish).

## Build-Depends
```
sudo apt install cmake debhelper extra-cmake-modules libkf5windowsystem-dev libqt5x11extras5-dev qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev qttools5-dev-tools
```

## Depends 
```
sudo apt install qml-module-qtquick-controls2 qml-module-qtquick2 qml-module-qtquick-layouts qml-module-qt-labs-platform qml-module-qt-labs-settings qml-module-qtqml qml-module-qtquick-window2 qml-module-qtquick-shapes
```

## Build and Install
```
git clone https://github.com/cutefishos/dock.git
mkdir ~/dock/build $$ cd ~/dock/build
cmake ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.

![GPLv3](https://raw.githubusercontent.com/cutefish-ubuntu/cutefish-ubuntu.github.io/master/images/gpl3.png)
