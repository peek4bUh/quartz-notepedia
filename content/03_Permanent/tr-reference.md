---
title: "tr: Reference"
language: english
binaryType: text-manipulation
tags:
  - permanent
  - command-reference
---

# tr: Reference

> Translate or delete characters.

```Bash
# Replace all occurrences of a character in a file
# and print the result
tr 𝑜𝑙𝑑_𝑐ℎ𝑎𝑟𝑎𝑐𝑡𝑒𝑟 𝑛𝑒𝑤_𝑐ℎ𝑎𝑟𝑎𝑐𝑡𝑒𝑟 < 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Replace all occurrences of a character
# from another command's output
𝑐𝑜𝑚𝑚𝑎𝑛𝑑_𝑜𝑢𝑡𝑝𝑢𝑝 | tr 𝑜𝑙𝑑_𝑐ℎ𝑎𝑟𝑎𝑐𝑡𝑒𝑟 𝑛𝑒𝑤_𝑐ℎ𝑎𝑟𝑎𝑐𝑡𝑒𝑟
```

## References

- _HTB Academy_. (n.d.). <span class="reference-title">Linux Fundamentals: Workflow: Filter Contents</span>. [https://academy.hackthebox.com/module/18/section/80](https://academy.hackthebox.com/module/18/section/80)
