---
title: 'su: Reference'
language: english
tags:
  - permanent
  - command-reference
---

# su: Reference

> Switch shell to another user.

```bash
# Switch to superuser (requires the root password)
su

# Switch to another user (requires the user's password)
su 𝑢𝑠𝑒𝑟𝑛𝑎𝑚𝑒

# Switch to a given user and simulate a full login shell
su - 𝑢𝑠𝑒𝑟𝑛𝑎𝑚𝑒

# Execute a command as another user
su - 𝑢𝑠𝑒𝑟𝑛𝑎𝑚𝑒 -c "𝑐𝑜𝑚𝑚𝑎𝑛𝑑"
```

## References

- tldr. _inbrowser.app_. (n.d.). [https://tldr.inbrowser.app/pages/common/su](https://tldr.inbrowser.app/pages/common/su)
