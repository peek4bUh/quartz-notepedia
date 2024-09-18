---
title: "mv: Reference"
language: english
binaryType: files-directories-manipulation
tags:
  - permanent
  - command-reference
---


> Move or rename files and directories.

```bash
# Rename file or directory when the target
# is not an existing directory
mv 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡

# Move a file or directory into an existing directory
mv 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑒𝑥𝑖𝑠𝑡𝑖𝑛𝑔_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Move multiple files into an existing directory,
# keeping the filenames unchanged
mv 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒2... 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑒𝑥𝑖𝑠𝑡𝑖𝑛𝑔_𝑑𝑖𝑟𝑒𝑐𝑡𝑜𝑟𝑦

# Do not prompt for confirmation before
# overwriting existing files
mv -f path/to/source 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡

# Prompt for confirmation before overwriting existing
# files, regardless of file permissions
mv -i path/to/source 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡

# Do not overwrite existing files at the target
mv -n 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡

# Move files in verbose mode, showing files after they are moved
mv -v 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑠𝑜𝑢𝑟𝑐𝑒 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑡𝑎𝑟𝑔𝑒𝑡
```

## References

- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Manipulating Files and Directories: mv-Move and Rename Files: Useful Options and Examples (2nd ed.)</span>. No Starch Press
- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/mv](https://tldr.inbrowser.app/pages/common/mv)

## Related

- Jacob Hornbeck. (2022, January 16), & Scott - Слава Україні. (2022, January 16). <span class="reference-title">mv: target “XXX” is not a directory</span>. _Super User_. [https://superuser.com/a/1699537](https://superuser.com/a/1699537)
