---
title: "man: Reference"
parent: "[[man-page|Man Page]]"
language: english
binaryType: files-commands-info
tags:
  - permanent
  - command-reference
---


> Format and display manual pages.

```bash
# Display the man page for a command
man 𝑐𝑜𝑚𝑚𝑎𝑛𝑑

# List all available sections for a command
man -f 𝑐𝑜𝑚𝑚𝑎𝑛𝑑

# Display the man page for a command from
# specific section listed above
man 𝑠𝑒𝑐𝑡𝑖𝑜𝑛_𝑛𝑢𝑚𝑏𝑒𝑟 𝑐𝑜𝑚𝑚𝑎𝑛𝑑

# Display the path of manpages
man -w

# Display the location of a command's manpage
man -w 𝑐𝑜𝑚𝑚𝑎𝑛𝑑

# Display the manpage using a specific language
man 𝑐𝑜𝑚𝑚𝑎𝑛𝑑 -L 𝑙𝑎𝑛𝑔𝑢𝑎𝑔𝑒

# Search for manpages containing a search string
man -k "𝑠𝑒𝑎𝑟𝑐ℎ_𝑠𝑡𝑟𝑖𝑛𝑔"
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/man](https://tldr.inbrowser.app/pages/common/man)
- _man_. manned.org. [https://www.man7.org/linux/man-pages/man1/man.1.html](https://www.man7.org/linux/man-pages/man1/man.1.html)
