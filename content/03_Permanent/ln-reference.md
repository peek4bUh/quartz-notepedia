---
title: "ln: Reference"
language: english
binaryType: files-directories-manipulation
tags:
  - permanent
  - command-reference
---


> Creates links to files and directories.

```bash
# Create a hard link to a file (directories
# are not allowed)
ln /path/to/file path/to/hardlink

# Create a soft link to a file or directory
ln -s /path/to/file_or_directory path/to/symlink

# Overwrite an existing soft link to point
# to a different file
ln -sf /path/to/new_file path/to/symlink
```

## References

- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Manipulating Files and Directories: rm-Remove Files and Directories: Useful Options and Examples (2nd ed.)</span>. No Starch Press
- _tldr InBrowser.App_. (n.d.). [https://tldr.inbrowser.app/pages/common/ln](https://tldr.inbrowser.app/pages/common/ln)

## See Also

- [[hard-link|Hard Link]]
- [[soft-link|Soft Link]]
