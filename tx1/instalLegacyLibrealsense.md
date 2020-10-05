# Install LibRealsense Legacy

## This version of librealsense is needed to support the old r200 depth cameras. This Page gives instructions on how to install librealsense and librealsense-ros on the jetson TX1.

# Flash Jetson with Jetpack 3.1

The following has only been tested on the TX1 with Jetpack 3.1

You have to install the old Jetpack installer. This can be found https://developer.nvidia.com/embedded/downloads/archive

This installer must be run on a ubuntu 16 host computer. This can be done in a VM but you must use VMware and not Virtualbox. Virtualbox's usb passthough for flashing does not appear to work.

When you flash the jetson you need to make sure you also install all of the additional libs. You may have to login and find the ip of the jetson to install these. The default username and password is nvidia:nvidia or ubuntu:ubuntu.
