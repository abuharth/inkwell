# inkwell

A text editor coded in one file of **C code**.

---

This project is based on a [great tutorial](https://viewsourcecode.org/snaptoken/kilo/index.html) that takes you through the step by step process of its creation.

---

There are very little dependencies so this should build out of the box on a linux machine. Just clone the repository, and run the following commands inside of the inkwell directory.


```
    $ make                      # builds project executable
    $ ./inkwell                 # opens inkwell with a blank file
    $ ./inkwell <filename>      # opens the given file in inkwell
```

## Features

- opening and viewing text files
    - text navigation (Arrow Keys, HOME/END, and PAGEUP/PAGEDOWN)
- basic text editing
- search in file (Ctrl-F)
- file saving (Ctrl-S)
    - prompts user for file name if a name is not already given

Planned additions are included in TODO
