---
title: "tee: Reference"
language: english
binaryType: text-manipulation
tags:
  - permanent
  - command-reference
---

# tee: Reference

> Read from standard input and write to standard output and files.

```bash
# Copy `stdin` to each file, and also to `stdout`
echo "string" | tee 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Append to the given files, do not overwrite
echo "string" | tee -a 𝑝𝑎𝑡ℎ/𝑡𝑜/𝑓𝑖𝑙𝑒

# Print `stdin` to the terminal, and also pipe it
# into another program for further processing
echo "string" | tee /dev/tty | xargs printf "[%s]"

# Create a directory called `example`, Count the
# Number of Characters in `example` and Write
# `example` to the Terminal
echo "example" | tee >(xargs mkdir) >(wc -c)
```

## References

- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Redirection: Pipelines: Filters: tee: Read from Stdin and Output to Stdout and Files (2nd ed.)</span>. No Starch Press
- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/tee](https://tldr.inbrowser.app/pages/common/tee)
