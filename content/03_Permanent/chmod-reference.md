---
title: 'chmod: Reference'
language: english
tags:
  - permanent
  - command-reference
---

# chmod: Reference

> Change the access permissions of a file or directory.

```bash
# Give the user who owns a file the right
# to execute it
chmod u+x 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Give the user rights to read and write
# to a file/directory
chmod u+rw 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒_𝑜𝑟_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Remove executable rights from the group
chmod g-x 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Give all users rights to read and execute
chmod a+rx 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Give others (not in the file owner's group)
# the same rights as the group
chmod o=g 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Remove all rights from others
chmod o= 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Change permissions recursively giving group
# and others the ability to write
chmod -R g+w,o+w 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Recursively give all users read permissions
# to files and execute permissions to sub-directories
# within a directory
chmod -R a+rX 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/chmod](https://tldr.inbrowser.app/pages/common/chmod)
