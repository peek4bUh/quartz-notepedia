---
title: 'sudo: Reference'
parent: '[[sudo]]'
language: english
tags:
  - permanent
  - command-reference
---

# sudo: Reference

```bash
# Run a command as the superuser
sudo 𝑐𝑜𝑚𝑚𝑎𝑛𝑑

# Display privileges granted
sudo -l

# Edit a file as the superuser with
# your default editor
sudo -e 𝑓𝑖𝑙𝑒

# Run a command as another user and/or group
sudo -u 𝑢𝑠𝑒𝑟 -g 𝑔𝑟𝑜𝑢𝑝 𝑐𝑜𝑚𝑚𝑎𝑛𝑑

# Repeat the last command prefixed with `sudo`
# (only in Bash, Zsh, etc.)
sudo !!

# Launch the default shell with superuser privileges
# and run login-specific files (`.profile`,
# `.bash_profile`, etc.)
sudo -i

# Launch the default shell with superuser privileges
# without changing the environment
sudo -s

# Launch the default shell as the specified user, loading
# the user's environment and reading login-specific files
# (`.profile`, `.bash_profile`, etc.):
sudo -i -u 𝑢𝑠𝑒𝑟
```

## References

- tldr. _inbrowser.app_. (n.d.). [https://tldr.inbrowser.app/pages/common/sudo](https://tldr.inbrowser.app/pages/common/sudo)
