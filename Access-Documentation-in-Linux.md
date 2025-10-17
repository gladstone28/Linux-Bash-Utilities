

Access Documentation in Linux
11 min
Linux
Preview: Docs Loading link description
 provides many ways to access documentation for other commands! Before we had the ability to use search engines to look up any questions we had, offline documentation was our only point of reference.

We can access documentation in the terminal itself using these files and commands:

- The /usr/share/doc/ directory
- The man command
- The info command

/usr/share/doc/

The /usr/share/doc/ directory contains README files, simple text files that describe a program, for many installed packages in your Linux distribution. You can explore the documentation available there using the command below.


```

ls /usr/share/doc


```

The man command

The man command is used to access the manual pages, the traditional way of distributing documentation for all bash programs. The command


```

man [options] <command_name>

```

will give us the command’s manual page includes a brief synopsis of the program, a description that lists all options, and examples.

For example, man cat will display the manual page for the command cat. The manual pages can be rather long but don’t be alarmed. We can also browse the manual pages online.


The info command

Even though manual pages are somewhat outdated, they make for great cheat sheets/reference cards. For full and detailed documentation, we can use the info command which also contains more recent information about programs than man. Its basic usage is:


```
info [options] <command_name>

```
For example, running info cat in the terminal will provide detailed information about the command cat.


lesson link


https://www.codecademy.com/courses/introduction-to-linux-bash-scripting/lessons/linux-shell-utilities/exercises/access-documentatino


