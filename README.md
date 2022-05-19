# hsh 



This repository contains the files for alx-Holberton's Simple_Shell project. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the $PATH.

##  Description

simple_shell is a command line interpreter, or shell, in the tradition of the first Unix shell written by Ken Thompson in 1971. This shell is intentionally minimalistic, yet includes the basic functionality of a traditional Unix-like command line user interface. Standard functions and system calls employed in simple_shell include: access, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.



## Pre-requisites
Authorized functions and macros:
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)


### GCC command to compile:
```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```

## Installation
 - Clone this repository: git clone "https://github.com/Bino26/simple_shell.git"
 - Change directories into the repository: cd simple_shell
 - Compile: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
 - Run the shell in interactive mode: ./hsh
 - Or run the shell in non-interactive mode: example echo "pwd" | ./hsh

## Usage

The simple_shell is designed to execute commands in a similar manner to sh, however with more limited functionality. The development of this shell is ongoing...


