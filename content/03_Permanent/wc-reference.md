---
title: "wc: Reference"
parent: "[[wc]]"
language: english
binaryType: text-manipulation
tags:
  - permanent
  - command-reference
---

# wc: Reference

> Count lines, words, and bytes.

```bash
# Print lines, words and bytes
wc 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Count all lines
wc -l 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Count all words
wc -w 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Count all bytes
wc -c 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Count all characters (taking multi-byte
# characters into account)
wc -m 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Count all lines, words and bytes from `stdin`
𝑐𝑜𝑚𝑚𝑎𝑛𝑑 | wc

# Count the length of the longest line in
# number of characters
wc -L 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/wc](https://tldr.inbrowser.app/pages/common/wc)
