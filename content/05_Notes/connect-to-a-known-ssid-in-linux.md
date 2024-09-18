---
title: 'Connect to a Known SSID in Linux'
language: english
tags:
  - note
---


## Manual

The `wpa_supplicant` requires a _root shell_:

```
# wpa_supplicant -B -i interface -c <(wpa_passphrase MYSSID passphrase)
```

Renew the ip addres (I think) to have internet:

```
# dhclient
```

https://stackoverflow.com/questions/63961142/what-does-dhclient-do

## At Boot

Inside the _root shell_ go to the `/etc` directory and type:

```
# wpa_passphrase "MYSSID" "passphrase" > wpa_supplicant-wlan0.conf
```

Enable at start up:

```
# systemctl enable wpa_supplicant@wlan0.service
```

Enable now if you don't want to reboot the machine (need to renew ip address):

```
# systemctl start wpa_supplicant@wlan0.service
```

