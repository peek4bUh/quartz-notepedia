---
title: "smbclient: Reference"
parent: '[[smbclient]]'
language: english
tags:
  - permanent
  - command-reference
---


> FTP-like client to access SMB/CIFS resources on servers.

```bash
# List the contents
smbclient -L <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺>

# List the contents anonymously
smbclient -L <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺> -N

# Connect to a specific share
smbclient \\\\<𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺>\\<𝑺𝑯𝑨𝑹𝑬>

smbclient -L 10.129.109.209 --user administrator

smbclient \\\\10.129.109.209\\ADMIN$ --user administrator
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/linux/smbclient](https://tldr.inbrowser.app/pages/linux/smbclient)
