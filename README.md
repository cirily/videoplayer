# Cirily Video Player

An open source video player built with Qt/QML and libmpv.

### Third Party Code

[haruna](https://github.com/g-fb/haruna)

## Dependencies (For Ubuntu/Debian)

```bash
sudo apt install extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev libmpv-dev
```

## Build and Install

```
git clone https://github.com/cirily/videoplayer.git
cd videoplayer
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

# License

This project has been licensed by GPLv3.
