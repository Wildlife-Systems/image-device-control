# Image device control and installation for Raspberry Pi
This bash script allows for control of various Raspberry Pi cameras using a simple and standardised interface. The script was developed as part of the Urban Nature Project and simplifies the automated control of image collection when using a network of Raspberry Pi devices with a heterogenous set of sound devices.

## Comaptible devices
Devices that have been tested with these scripts are listed below. The short name is used internally to refer to different cameras, and is the paramater passed to `idc-inst` to perform the installation.

| Device | `shortname` |
| --- | --- |
| RaspberryPi Camera | rpi-cam |
| RaspberryPi NoIR Camera | rpi-noir |

## Installing this package
`wget -O - https://github.com/Wildlife-Systems/image-device-control/raw/master/install | sudo bash`

## Installation of image device software
The script `idc-inst` can be used to install various drivers for cameras and configure them. This is mainly of use in large scale, automated, heterogenous deployments but may simplify things for some other end users.

Usage:
```
idc-inst <shortname>
```

## Development
* Development of this script was done as part of the Urban Nature Project at the Natural History Museum, London.
