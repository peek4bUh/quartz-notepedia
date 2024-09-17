---
title: 'chown: Reference'
language: english
tags:
  - permanent
  - command-reference
---

# chown: Reference

> Change owner and group ownership of files and directories.

```bash
# Change the owner user of a file/directory
chown 𝑢𝑠𝑒𝑟 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Change the owner user and group of a file/directory
chown 𝑢𝑠𝑒𝑟:𝑔𝑟𝑜𝑢𝑝 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Change the owner user and group to both have the name `user`
chown 𝑢𝑠𝑒𝑟: 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Change the group owner, the file owner is unchanged
chown :𝑔𝑟𝑜𝑢𝑝 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Recursively change the owner of a directory and its contents
chown -R 𝑢𝑠𝑒𝑟 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Recursively change the owner and group of a directory and its contents
chown -R 𝑢𝑠𝑒𝑟:𝑔𝑟𝑜𝑢𝑝 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Change the owner of a symbolic link
chown -h 𝑢𝑠𝑒𝑟 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑦𝑚𝑙𝑖𝑛𝑘
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/chown](https://tldr.inbrowser.app/pages/common/chown)

## See Also

- [[chgrp-reference|chgrp: Reference]]
