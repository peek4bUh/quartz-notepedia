---
title: "rm: Reference"
parent: "[[rm]]"
language: english
binaryType: files-directories-manipulation
tags:
  - permanent
  - command-reference
---

# rm: Reference

> Remove files or directories.

```bash
# Remove specific files
rm 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2...

# Remove specific files ignoring nonexistent ones
rm -f 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2...

# Remove specific files interactively prompting before each removal
rm -i 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2...

# Remove specific files printing info about each removal
rm -v 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2...

# Remove specific files/directories recursively
rm -r 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦2...

# Remove specific files/directories recursively and
# ignoring nonexistent ones.
rm -rf 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦2 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦2...
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/rm](https://tldr.inbrowser.app/pages/common/rm)
