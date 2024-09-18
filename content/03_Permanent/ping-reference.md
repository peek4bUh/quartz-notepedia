---
title: 'ping: Reference'
language: english
tags:
  - permanent
  - command-reference
---


> Send ICMP ECHO_REQUEST to network hosts.

```bash
# Ping to a host by ip
ping 𝑖𝑝_𝑎𝑑𝑑𝑟𝑒𝑠𝑠

# Ping a host only a specific number of times
ping -c 𝑐𝑜𝑢𝑛𝑡 ℎ𝑜𝑠𝑡

# Ping to a host, specifying the interval in
# seconds between requests (default is 1 second)
ping -i 𝑠𝑒𝑐𝑜𝑛𝑑𝑠 ℎ𝑜𝑠𝑡

# Ping to a host without trying to lookup symbolic
# names for addresses
ping -n ℎ𝑜𝑠𝑡

# Ping to a host and ring the bell when a packet
# is received (if your terminal supports it)
ping -a ℎ𝑜𝑠𝑡

# Display a message if no response was received
ping -O ℎ𝑜𝑠𝑡
```

## References

- tldr. _inbrowser.app_. (n.d.). [https://tldr.inbrowser.app/pages/common/ping](https://tldr.inbrowser.app/pages/common/ping)
