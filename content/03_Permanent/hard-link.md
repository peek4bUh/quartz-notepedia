---
title: Hard Link
parent: "[[computing-moc]]"
language: english
tags:
  - permanent
---

# Hard Link

The difference with [[soft-link|soft link]] is that **hard links** allow files to have multiple names, but they do it in a different way.

**Hard links** are the original Unix way of creating links, compared to [[soft-link|soft link]], which are more modern. By default, every file has a single hard link that gives the file its name. When creating a hard link, you create n additional directory entry for a file.

**Hard links** have two important limitations:

- A **hard link** cannot reference a file outside its own file system. This means a link cannot reference a file that is not on the same disk partition as the link itself.
- A **hard link** may not reference a directory.

A **hard link** is identical from the file itself. Unlike a [[soft-link|soft link]], when you list a directory containing a **hard link**, you will see no special indication of the link. When a **hard link** is deleted, the link is removed, but the contents of the file itself continue to exist (that is, its space not deallocated) until all links to the file are deleted.

It is important to be aware of **hard links** because you might encounter them from time to time, but modern practice prefer [[soft-link|soft link]].

When you create **hard link**, you are actually creating additional name parts that all refer to the same data part. The system assigns a chain of disk blocks called _inode_, which is then associated with the name part. Each **hard link** therebefore refers to a specific inode containing the file's contents.

![[hard-link.excalidraw|100%]]

The [[ls]] command has a way to reveal this information with the option `-i`.

```
[tux@linuxbox ~]$ ls ./bin
total 64
  1389 -rw-------  1 pi   pi   60355 Mar 14 15:41 .bash_history
  1333 -rw-r--r--  1 pi   pi     220 Apr  4  2022 .bash_logout
   870 -rw-r--r--  1 pi   pi    3820 Oct 17 19:34 .bashrc
122364 drwxr-xr-x  2 pi   pi    4096 Aug 29  2023 Desktop
122374 drwxr-xr-x  3 pi   pi    4096 Dec 17 00:07 Documents
122377 drwxr-xr-x  2 pi   pi    4096 Jan 28 17:05 Downloads
122376 drwxr-xr-x  2 pi   pi    4096 Jun 27  2023 Images
130956 drwxr-xr-x  5 pi   pi    4096 Feb  3 22:29 Videos
```

## References

- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Exploring the System: Symbolic Links (2nd ed.)</span>. No Starch Press
- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Manipulating Files and Directories: ln-Create Links: Hard Links (2nd ed.)</span>. No Starch Press

## See Also

- [[soft-link|Soft Link]]
- [[ln-reference|ln: Reference]]
