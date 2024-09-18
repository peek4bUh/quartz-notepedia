---
title: Command
parent: "[[computing-moc]]"
language: english
tags:
  - permanent
---


A **command** can be one of four different things:

- An <span class="highlight">executable program</span> like all those files you see in [[usr-bin-directory|/usr/bin]]. Within this category, programs can be _compiled binaries_ such as programs written C and C++, or programs written in _scripting languages_ such as the shell, Perl, Python, Ruby, and so on.
- A <span class="highlight">command built into the shell itself</span>. [[bash|Bash]] supports a number of **commands** internally called _shell builtins_. The [[cd-reference|cd: Reference]] command, for example, is a [[shell|shell]] builtin.
- A <span class="highlight">shell function</span>. Shell functions are miniature [[shell|shell]] scripts incorporated into the _environment_.
- An <span class="highlight">alias</span>. Aliases are **commands** that we can define ourselves, built from other **commands**.

It is often useful to know exactly which of the four kinds of **commands** is being used, and Linux provides a couple of ways to find out:

- [[type-reference|type: Reference]]
- [[which-reference|which: Reference]]
- [[help]]
- **command** --help
- [[man-page|Man Page]]
- [[apropos-reference|apropos: Reference]]
- [[whatis]]
- [[info]]

## References

- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Navigation: Working With Commands: What Exactly Are Commands? (2nd ed.)</span>. No Starch Press
- Shotts, W. (2019). <span class="reference-title">The Linux Command Line: Navigation: Getting a Command's Documentation: help-Get Help for Shell Builtins (2nd ed.)</span>. No Starch Press
