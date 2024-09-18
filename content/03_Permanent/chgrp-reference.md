---
title: 'chgrp: Reference'
language: english
tags:
  - permanent
  - command-reference
---


> Change group ownership of files and directories.

```bash
# Change the owner group of a file/directory
chgrp 𝑔𝑟𝑜𝑢𝑝 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Recursively change the owner group of a
# directory and its contents
chgrp -R 𝑔𝑟𝑜𝑢𝑝 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Change the owner group of a symbolic link
chgrp -h 𝑔𝑟𝑜𝑢𝑝 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑦𝑚𝑙𝑖𝑛𝑘

# Change the owner group of a file/directory
# to match a reference file
chgrp --reference=𝑝𝑎𝑡ℎ/𝑡𝑜/𝑟𝑒𝑓𝑒𝑟𝑒𝑛𝑐𝑒_𝑓𝑖𝑙𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/chgrp](https://tldr.inbrowser.app/pages/common/chgrp)

## See Also

- [[chown-reference|chown: Reference]]
