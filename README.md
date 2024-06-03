# qt5pi
Qt5 docker compiler for raspberry pi

## HOW TO

Set TARGET in ```Dockerfile``` to prefereable Raspberry Pi and execute the commands below:

```shell
docker build -t qt-builder .
docker run --rm -t -v ~/tmp/qt-src:/src -v ~/tmp/qt-build:/build qt-builder
```
