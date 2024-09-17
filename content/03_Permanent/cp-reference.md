---
title: "cp: Reference"
language: english
binaryType: files-directories-manipulation
tags:
  - permanent
  - command-reference
---

# cp: Reference

> Copy files and directories.

```bash
# Copy a file to another location (if `target_file`
# exists, it is overwritten with the contents of
# `source_file`; otherwise, it is created)
cp 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑓𝑖𝑙𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡_𝑓𝑖𝑙𝑒

# Prompt user to copy a file to another location
cp -i 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑓𝑖𝑙𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡_𝑓𝑖𝑙𝑒

# Copy a file into another directory, keeping the filename
# INFO: `dest_directory` must already exist
cp 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑓𝑖𝑙𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑒𝑠𝑡_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Copy multiple files into another directory,
# keeping the filename
# INFO: `dest_directory` must already exist
cp 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑓𝑖𝑙𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡_𝑓𝑖𝑙𝑒2... 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑒𝑠𝑡_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Copy all files from a directory to another
# INFO: `dest_directory` must already exist
cp  𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦/* 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑒𝑠𝑡_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Recursively copy a directory's contents to
# another location (If `dest_directory` exists,
# the `source_directory` is copied inside it,
# otherwise `dest_directory` is created)
cp -R 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑑𝑒𝑠𝑡_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Recursively copy a directory's contents
# to another location in verbose mode (show files
# as they are copied)
cp -vR  𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦
```

## References

- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Manipulating Files and Directories: cp-Copy Files and Directories: Useful Options and Examples</span> (2nd ed.). No Starch Press
- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/cp](https://tldr.inbrowser.app/pages/common/cp)
