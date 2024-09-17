---
title: "gobuster: Reference"
language: english
tags:
  - permanent
  - command-reference
binaryType:
  - brute-forcing
---

# gobuster: Reference

> Directory/file & DNS busting tool.

```bash
# Discover directories and files that match in the wordlist
gobuster dir -w <𝑾𝑶𝑹𝑫𝑳𝑰𝑺𝑻_𝑷𝑨𝑻𝑯> -u <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺>

# Discover directories and files that match in the wordlist
# but excluding files ending with the extension provided
gobuster dir -u <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺> -w <𝑾𝑶𝑹𝑫𝑳𝑰𝑺𝑻_𝑷𝑨𝑻𝑯> -x 𝑒𝑥𝑡1,𝑒𝑥𝑡2...

# Discover virtual hosts
gobuster vhost -w <𝑾𝑶𝑹𝑫𝑳𝑰𝑺𝑻_𝑷𝑨𝑻𝑯> -u <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺>
```

## References

- 0ne-nine9. (n.d.). <span class="reference-title">Preignition Write-up</span>. _HTB Labs_. [https://app.hackthebox.com/starting-point](https://app.hackthebox.com/starting-point)
- 0ne-nine9. (n.d.). <span class="reference-title">Crocodile Write-up</span>. _HTB Labs_. [https://app.hackthebox.com/starting-point](https://app.hackthebox.com/starting-point)

## See Also

- [[wfuzz]]
- [[feroxbuster]]
