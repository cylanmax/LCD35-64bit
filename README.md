A quick guide on how to install a (3.5) waveshare(/clone) LCD on a Raspberry Pi running 64bit OS (namely Raspbian).
Guide is written for 3.5 inch screen but could be adapted for any screen.

# Installation
`git clone https://github.com/tux1c/wavesharelcd-64bit-rpi.git`

`cd wavesharelcd-64bit-rpi`

`chmod +x install.sh`

`sudo bash install.sh`

# Troubleshooting
## White screen on boot (raspberry pi boots)
make sure `dtoverlay=vc4-fkms-v3d` is **NOT** present / commented out in `/boot/config.txt`
