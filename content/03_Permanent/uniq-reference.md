---
title: 'uniq: Reference'
parent: '[[uniq]]'
language: english
tags:
  - permanent
  - command-reference
---

# uniq: Reference

> Report or omit repeated lines.

```bash
# Display each line once
sort 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒 | uniq

# Display only unique lines
sort 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒 | uniq -u

# Display only duplicate lines
sort 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒 | uniq -d

# Display number of occurrences of each line
# along with that Line
sort 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒 | uniq -c

# Display number of occurrences of each line,
# sorted by the most frequent
sort 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒 | uniq -c | sort -nr
```

## References

- tldr. _inbrowser.app_. (n.d.). [https://tldr.inbrowser.app/pages/common/uniq](https://tldr.inbrowser.app/pages/common/uniq)
