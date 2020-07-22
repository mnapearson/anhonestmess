# Command Line

[Codes](/codes/)

## Filepaths

|                 |                                                               |
| --------------- | ------------------------------------------------------------- |
| `img/logo.png`  | Relative path: resolved relative to current working directory |
| `/usr/bin/bash` | Absolute path: resolved relative to the file system root      |
| `.`             | Current working directory                                     |
| `. .`           | Parent directory                                              |
| `~`             | User home directory                                           |

## Browsing the file system

|                  |                                                                                            |
| ---------------- | ------------------------------------------------------------------------------------------ |
| `pwd`            | Print working directory                                                                    |
| `cd <path>`      | Change working directory to `<path>`                                                       |
| `cd`             | Change working directory to home directory, equivalent to `cd ~`                           |
| `ls <path>`      | List the files in `<path>`                                                                 |
| `ls`             | List the files in current directory                                                        |
| `ls -l`          | List files in **long format** , including file permissions, owner, change date, size, etc. |
| `ls -a`          | List all files, including hidden files (starting with a .)                                 |
| `cat <file>`     | Print `<file>` to stdout, interpreted as plain text                                        |
| `hexdump <file>` | Print bytes in `<file>` using hexadecimal digits                                           |
