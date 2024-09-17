---
title: 'passwd: Reference'
language: english
tags:
  - permanent
  - command-reference
---

# passwd: Reference

> Change a user's password.

```bash
# Change the password of the current user interactively
passwd

# Change the password of a specific user
passwd 𝑢𝑠𝑒𝑟𝑛𝑎𝑚𝑒

# Get the current status of the user
passwd -S

# Make the password of the account blank (it will
# set the named account passwordless)
passwd -d
```

## References

- tldr. _inbrowser.app_. (n.d.). [https://tldr.inbrowser.app/pages/common/passwd](https://tldr.inbrowser.app/pages/common/passwd)
