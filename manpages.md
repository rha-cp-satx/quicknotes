### Man Page

Go here for a quick and simple man page tutorial on how to use man and search for what you want:
- [Efficiently use man pages (search/etc):]( https://ostechnix.com/learn-use-man-pages-efficiently/)
- [View specific man page sections:]( https://ostechnix.com/how-to-view-a-specific-section-in-man-pages-in-linux/)
- [Man page basics:](  https://bash.cyberciti.biz/guide/Man_command?utm_source=Linux_Unix_Command&utm_medium=faq&utm_campaign=nixcmd)

---------------------------------------------

1. To read the man page for something use: `man <keyword>`; example:

```sh
man selinux
```

2. To search for something specific in the man database, use: `man -k <keyword>`

    **This will search the short description of the man page name**

Say that you are trying to remember the syntax of labeling a file with a selinux context but you can only remember one part of the command `fcontext`. You can use the `-k` switch with man to search for a particular keyword.


```sh
man -k fcontext
```

Using `man -K` will search for that keyword globally 

3. To print all man pages for something like selinux: `man -a ls`

4. There are various sections of man pages too:

|section|purpose|
|---|---|
|1|Executable programs or Shell Commands|
|2|System Calls (functions provided by the kernel)|
|3|Library calls (functions within program libraries)|
|4|Special Files (usually found in /dev)|
|5|File formats and conventions|
|6|Games|
|7|Miscellaneous (including macro packages and conventions)|
|8|System administration commands (usually only for root)|
|9|Kernel routines [Non Standard]|
