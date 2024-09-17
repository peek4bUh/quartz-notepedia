---
title: "tail: Reference"
parent: "[[tail]]"
language: english
binaryType: file-interaction
tags:
  - permanent
  - command-reference
---

# tail: Reference

> Output the last part of files.

```bash
# Specify the last `number` lines in a file
tail -n 𝑛𝑢𝑚𝑏𝑒𝑟 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Specify the line number where you start in a file
tail -n +𝑛𝑢𝑚𝑏𝑒𝑟 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Print a specific count of bytes `-c` from the
# end of a given file
tail -c 𝑛𝑢𝑚𝑏𝑒𝑟 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Print the last lines of a file and keep reading it
# until `Ctrl + C`
tail -f 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/tail](https://tldr.inbrowser.app/pages/common/tail)
