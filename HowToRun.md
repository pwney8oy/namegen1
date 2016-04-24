# Introduction #

This Wiki page will show you how to run NameGen on a Linux or Windows computer.


# Details #

SYNTAX:
```
     name -[m, f]
     Ex.
     name -m ## Male
     name -f ## Female
```

### To run NameGen in Linux: ###
**With Installer**

To run with installer, run the installer (setup.py) as root. If you don't want to install the files in /usr/bin, run it with `-p` (`sudo ./setup.py -p` or `sudo python setup.py -p`) to install it to the first directory in your PATH.

After install, it should tell you to type `name` into your command prompt to use NameGen.

**Without Installer**

Make sure `name` is in the same directory as the `dist.*` files and run `./name` to use.

### To run NameGen in Windows: ###
There is currently no installer for Windows. You must have Python installed before using NameGen. Type `python name` in the Command Prompt (Start -> Run -> cmd.exe) when in the directory of the NameGen executable to run. If you have an IDE, try renaming `name` to `name.py` and using the IDE to run it (most likely by double clicking it).