# Pi-HiFi

High bitrate streaming box for Spotify

## Setup

### Install Rasbian

[Download Rasbian](https://www.raspberrypi.org/downloads/raspbian/) and burn it to an SD card with Etcher.

Install Vim and a RDP client

```bash
sudo apt install vim xrdp -y
```

### Raspotify

[Raspotify](https://github.com/dtcooper/raspotify) sets up a Spotify Connect endpoint.

Be sure to set `BITRATE="320"` in the raspotify config as described in their README.

### HiFi Hat

I used the [HiFi Berry Pro](https://www.hifiberry.com/shop/boards/hifiberry-dac-pro/) and the Steel case from the same company.

[HiFi hat setup details here](https://www.hifiberry.com/build/documentation/configuring-linux-3-18-x/) if you don't want to use their OS.

## Troubleshooting

- You might need to `sudo service raspotify restart` every once in a while if things aren't working.

## That's it!

You should be able to stream spotify to the Pi-HiFi now!