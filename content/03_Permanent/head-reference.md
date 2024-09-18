---
title: 'head: Reference'
parent: "[[head]]"
language: english
binaryType: file-interaction
tags:
  - permanent
  - command-reference
---


> Output the first part of files.

```bash
# Output the first few lines of a file
head -n 𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
head --lines 𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Output the first few bytes of a file
head -c 𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
head --bytes=𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Output everything but the last few lines of a file
head -n -𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
head --lines -𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Output everything but the last few bytes of a file
head -c -𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
head --bytes -𝑐𝑜𝑢𝑛𝑡 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/linux/head](https://tldr.inbrowser.app/pages/linux/head)
