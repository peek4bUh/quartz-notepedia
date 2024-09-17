---
title: "sed: Reference"
language: english
binaryType: text-manipulation
tags:
  - permanent
  - command-reference
---

# sed: Reference

> Stream editor for filtering and transforming text.

```bash
# Replace all `𝑜𝑙𝑑_𝑤𝑜𝑟𝑑` occurrences with `𝑛𝑒𝑤_𝑤𝑜𝑟𝑑`
# in all input lines and print the result to `stdout`
sed 's/𝑜𝑙𝑑_𝑤𝑜𝑟𝑑/𝑛𝑒𝑤_𝑤𝑜𝑟𝑑/g' 𝑖𝑛𝑝𝑢𝑡_𝑓𝑖𝑙𝑒
𝑐𝑜𝑚𝑚𝑎𝑛𝑑 | sed 's/𝑜𝑙𝑑_𝑤𝑜𝑟𝑑/𝑛𝑒𝑤_𝑤𝑜𝑟𝑑/g'
```

## References

- _HTB Academy_. (n.d.). <span class="reference-title">Linux Fundamentals: Workflow: Filter Contents</span>. [https://academy.hackthebox.com/module/18/section/80](https://academy.hackthebox.com/module/18/section/80)
- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/sed](https://tldr.inbrowser.app/pages/common/sed)
