# droidcam-client-arm64
This is a droidcam client for arm64 raspberry pi cli version. I compile the source code from official droidcam repo.
Install the following dependencies
(the package names are for Debian based systems, adjust as needed for other distros)
```
libavutil-dev
libswscale-dev
libasound2-dev
libspeex-dev
libusbmuxd-dev
libplist-dev

gtk+-3.0               # Only needed for GUI client
libappindicator3-dev   # Only needed for GUI client^^

```

run ./droidcam-cli <ip> <port>, instead of <ip> and <port> type data shown on your phone
