---
title: "cat: Reference"
parent: "[[cat]]"
language: english
binaryType: file-interaction
tags:
  - permanent
  - command-reference
---


> Concatenate files and print on the standard output.

```bash
# Print the contents of a file to `stdout`
cat 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Print the contents of a multiple files to `stdout`
cat 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒3...

# Concatenate several files into an output file
cat 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2... > 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑜𝑢𝑡𝑝𝑢𝑡_𝑓𝑖𝑙𝑒

# Append several files to an output file
cat 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2... >> 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑜𝑢𝑡𝑝𝑢𝑡_𝑓𝑖𝑙𝑒

# Copy the contents of a file into an output file without buffering
cat -u 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒1 > 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒2

# Write `stdin` to a file
# TIP: use `CTRL + D` to stop writing
cat - > 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
cat > 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/cat](https://tldr.inbrowser.app/pages/common/cat)
