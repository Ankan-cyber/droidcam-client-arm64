# droidcam-client-arm64
This is a droidcam client for arm64 raspberry pi cli version. I compile the source code from official droidcam repo.

Install the following dependencies
(the package names are for Debian based systems, adjust as needed for other distros)


```
sudo apt install libavutil-dev libswscale-dev libasound2-dev libspeex-dev libusbmuxd-dev libplist-dev

```
For droidcam-gui only =>
```
sudo apt install libgtk-3-dev libappindicator3-dev

```
if you want mic access follow [this repo](https://github.com/umlaeute/v4l2loopback)

run ./droidcam-cli <ip> <port>, instead of <ip> and <port> type data shown on your phone
