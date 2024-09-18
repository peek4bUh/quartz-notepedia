---
title: "mysql: Reference"
language: english
tags:
  - permanent
  - command-reference
---


> The MariaDB command-line tool (mysql is now a symlink to mariadb)

```bash
# Connect to a host with an username
mysql -h <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺> -u <𝑼𝑺𝑬𝑹𝑵𝑨𝑴𝑬>

# Connect to a host with root
mysql -h <𝑰𝑷_𝑨𝑫𝑫𝑹𝑬𝑺𝑺> -u root

# -- INSIDE DB --
# Prints out the databases we can access.
SHOW databases;

# Set to use the database named {database_name}.
USE <𝑫𝑨𝑻𝑨𝑩𝑨𝑺𝑬_𝑵𝑨𝑴𝑬>;

# Prints out the available tables inside the current database.
SHOW tables;

# Prints out all the data from the table {table_name}.
SELECT * FROM <𝑻𝑨𝑩𝑳𝑬_𝑵𝑨𝑴𝑬>;
```

## References

- 0ne-nine9, & ilinor. (n.d.). <span class="reference-title">Sequel Write-up</span>. _HTB Labs_. [https://app.hackthebox.com/starting-point](https://app.hackthebox.com/starting-point)
