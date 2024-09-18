---
title: "echo: Reference"
language: english
binaryType: text-manipulation
tags:
  - permanent
  - command-reference
---


> Display a line of text.

```bash
# Print a text message (quotes are optional)
echo "𝑡𝑒𝑥𝑡_𝑚𝑒𝑠𝑠𝑎𝑔𝑒"

# Print a message with environment variables
echo "𝑡𝑒𝑥𝑡_𝑚𝑒𝑠𝑠𝑎𝑔𝑒 $𝐸𝑁𝑉_𝑉𝐴𝑅𝐼𝐴𝐵𝐿𝐸"

# Print a message without the trailing newline
echo -n "𝑡𝑒𝑥𝑡_𝑚𝑒𝑠𝑠𝑎𝑔𝑒"

# Append a message to the file
echo "𝑡𝑒𝑥𝑡_𝑚𝑒𝑠𝑠𝑎𝑔𝑒" >> 𝑓𝑖𝑙𝑒

# Enable interpretation of backslash escapes
# (special characters)
echo -e "𝐶𝑜𝑙𝑢𝑚𝑛1\t𝐶𝑜𝑙𝑢𝑚𝑛2"

# Print the exit status of the last executed command
echo $?
```

## References

- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/echo](https://tldr.inbrowser.app/pages/common/echo)
