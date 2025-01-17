# ipu6-camera-bins

This repository supports MIPI cameras through the IPU6 on Intel Tigerlake platforms. There are 4 repositories that provide the complete setup:

* https://github.com/9elements/ipu6-drivers - kernel drivers for the IPU and sensors
* https://github.com/9elements/ipu6-camera-hal - HAL for processing of images in userspace
* https://github.com/9elements/ipu6-camera-bins - IPU firmware and proprietary image processing libraries
* https://github.com/9elements/icamerasrc - Gstreamer src plugin


## Content of this repository:
* IPU6 firmware
* Library binary dependencies for IPU6 HAL
* Headerfiles for those libraries

## Deployment
ipu6-camera-bins should be copied to build server and target
```
cp -r include/* /usr/include/
cp -r lib/* /usr/lib/
```
