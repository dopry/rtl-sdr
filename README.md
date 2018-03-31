# RTL-SDR

Minimal Docker image with RTL-SDR. Based on [bemasher/rtl-sdr](https://hub.docker.com/r/bemasher/rtl-sdr), but only about 4.5M instead of 180M.

## Setup

**Running under Docker standalone**
`docker run -d --privileged -v /dev/bus/usb:/dev/bus/usb -p 1234:1234 dopry/rtl-sdr`
