# Linux Command Line
Overview of Linux command line tools

## Linux Distributions
The Linux Kernel itself is not a full-blown operating system. When people talk about a Linux-based operating system, they are referring to Linux distributions. Typically, a Linux distribution bundles together the Linux kernel, GNU tools, documentation, a package manager, a window system, and desktop environment. There are nearly 1000 Linux distros available. Some of the more popular ones includes Fedora, Ubunutu, Debian, and Slackware.

## Kernel
A kernel is a computer program that forms the core of an operating system and manages critical tasks like memory management, task scheduling, and managing hardware. It is not the same as an OS. The kernel is the part of an OS that facilitates interactions between hardware (CPU, memory, devices) and software (applications).

## Shell
A shell is a computer interface to an operating system. Shells expose the OS's services to human users or other programs. The shell takes our commands and gives them to the operating system to perform. It's named a shell because it is the outer layer around the OS, like the shell around an oyster. The most common shell is called "bash". To find out which shell is running, type `echo $SHELL`. To change the shell being used (e.g. to bash), type `chsh -s /bin/bash`.

## Terminal
A terminal is a program that runs a shell. 

## bash
On most Linux-based systems, the default shell program is "bash". There are many other shells, but bash is currently the most popular one. The name "bash" is an acronym for "Bourne-Again-SHell", a reference to Stephen Bourne, the creator of bash's direct ancestor, "sh".

## Prompt
When we open our terminal, we will see our prompt which will likely include your `username@machinename~$`. This prompt is what we will see whenever the shell is ready to accept new input.

## Argument / Parameter
The terms "argument" and "parameter" are often used interchangeably to refer to values that we provide to commands.

## Options
Options, typically a single letter (most often case-sesnitive), modify the behavior of the command in predefined ways. Options are prefixed by a dash (e.g. -u for coordinated universal time). Some options also support equivalent long format options that are usually full words and are prefixed with two dashes instead of just one (e.g. --universal for coordinated universal time, too).

## Options with Parameters
Some options require us to pass in an additional value. For example, `ncal`'s `-A` option is used to display a certain number of months after a specific date. We need to tell it how many months to display.

## Command Structure `command -options arguments`
Most commands support multiple options that modidy their behavior.

## Git
Git is officially defined as a distributed version control system (VCS). In other words, it's a system that tracks changes to our project files over time. It enables us to record project changes and go back to a specific version of the tracked files, at any given point in time.  This system can be used by many people to efficiently work together and collaborate on team projects, where each developer can have their own version of the project, distributed on their computer. Later on, these individual versions of the project can be merged and adapted into the main version of the project.

Introduction: https://www.notion.so/zarkom/Introduction-to-Git-ac396a0697704709a12b6a0e545db049

Documentation: https://git-scm.com/doc

## References

Devconnected (2021) How To Count Files in Directory on Linux. Available at: https://devconnected.com/how-to-count-files-in-directory-on-linux/ (Accessed: 3 September 2021)

Child, D. (2011) Linux Command Line Cheat Sheet. Available at: https://cheatography.com/davechild/cheat-sheets/linux-command-line/ (Accessed: 4 September 2021)

SS64 (2021) An A-Z Index of the Linux command line: bash + utilities. Available at: https://ss64.com/bash/ (Accessed: 3 September 2021)

Steele, C. (2021) The Linux Command Line Bootcamp: Beginner To Power User. Available at: https://www.udemy.com/course/the-linux-command-line-bootcamp/ (Accessed: 3 September 2021)

University of Warwick (2018) Basics of the Command Line. Available at: https://warwick.ac.uk/research/rtp/sc/rse/training/linuxdesktop/basiccommandline/ (Accessed: 3 September 2021)

Wikipedia (2021) Filename. Available at: https://en.wikipedia.org/wiki/Filename (Accessed: 4 September 2021)
