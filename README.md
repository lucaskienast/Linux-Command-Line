# Linux Command Line
Overview of Linux command line tools

## GNU/Linux Background

### Linux Distributions
The Linux Kernel itself is not a full-blown operating system. When people talk about a Linux-based operating system, they are referring to Linux distributions. Typically, a Linux distribution bundles together the Linux kernel, GNU tools, documentation, a package manager, a window system, and desktop environment. There are nearly 1000 Linux distros available. Some of the more popular ones includes Fedora, Ubunutu, Debian, and Slackware.

### Kernel
A kernel is a computer program that forms the core of an operating system and manages critical tasks like memory management, task scheduling, and managing hardware. It is not the same as an OS. The kernel is the part of an OS that facilitates interactions between hardware (CPU, memory, devices) and software (applications).

### Shell
A shell is a computer interface to an operating system. Shells expose the OS's services to human users or other programs. The shell takes our commands and gives them to the operating system to perform. It's named a shell because it is the outer layer around the OS, like the shell around an oyster. The most common shell is called "bash". To find out which shell is running, type `echo $SHELL`. To change the shell being used (e.g. to bash), type `chsh -s /bin/bash`.

### Terminal
A terminal is a program that runs a shell. 

### bash
On most Linux-based systems, the default shell program is "bash". There are many other shells, but bash is currently the most popular one. The name "bash" is an acronym for "Bourne-Again-SHell", a reference to Stephen Bourne, the creator of bash's direct ancestor, "sh".

### Prompt
When we open our terminal, we will see our prompt which will likely include your `username@machinename~$`. This prompt is what we will see whenever the shell is ready to accept new input.

### Argument / Parameter
The terms "argument" and "parameter" are often used interchangeably to refer to values that we provide to commands.

## Basic Commands

### Command Structure `command -options arguments`
Most commands support multiple options that modidy their behavior.

### `clear`
Clears terminal window.

### `echo`
Prints out the argument after the `echo` command.

### `date`
Shows current date.

### `ncal`
Shows the current month's calendar (Stands for "new calendar") if left alone. There is also a `cal` command that does almost the same thing, but `ncal` adds more functionalities. If the command is accompanied by an argument (e.g. 2021 or july 1994), it will print out the calendar for the specified argument(s).

### `sort`
Accepts a filename as argument and prints out the sorted content of that file. For example, `sort file.txt` prints out each line of the file.txt file, sorted in alphabetical order.

## References
Steele, C. (2021) The Linux Command Line Bootcamp: Beginner To Power User. Available at: https://www.udemy.com/course/the-linux-command-line-bootcamp/ (Accessed: 3 September 2021)
