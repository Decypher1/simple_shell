# Simple Shell Project
Creating our version of a command line interpreter: shell.

- This repository includes our version of the Shell: simple Unix command interpreter, replicates the basic functionalities of the simple shell (sh). Here, we will be employing our knowledge in C programming Language and attempt to emulate a simpler, basic version of the normal BASH (sh) in Linux.
- This project is in fulfillment of completion of our ALX Learning.

---------------

## What is the shell?

A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts.

- https://en.wikipedia.org/wiki/Unix_shell

This version of super simple shell support the next built-in

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit            | Exit the shell with the command exit.                                          |
| env                 | Print the environment.                                                                    |

## Installation

Use the [git clone]() to install this super simple shell.


## Compilation

Your code will be compiled this way:

```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```
This project works in two different modes, the interactive mode and the non interactive mode.

With the compilation create an executable file that can use to emulate the simple shell like this in interective mode:


```sh
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```
And also you can emulate the simple shell like this in non-interactive mode:

```sh
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
$
```

### Usage Examples

In the terminal, our version of the simple shell looks like this:

```sh
$ /bin/ls -l
total 84
-rwxrwxr-x 1 alango alango 18104 Nov 16 03:27 a.out
-rw-rw-r-- 1 alango alango     9 Nov 16 02:58 config
-rw-rw-r-- 1 alango alango 35141 Nov 16 02:58 LICENSE
```

```sh
$ pps
Does not execute, write valid command: No such file or directory
```
## Authors
- [Martins Umekwe](https://github.com/Decypher1)
- [Dandy Okoro](https://github.com/demondandy)
