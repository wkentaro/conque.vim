conque.vim
===
This is a mirror of https://code.google.com/p/conque/.

Conque is a Vim plugin which allows you to run interactive programs, such as bash on linux or powershell.exe on Windows, inside a Vim buffer. In other words it is a terminal emulator which uses a Vim buffer to display the program output.


Website
---

For more information https://code.google.com/p/conque/.

Screenshots
---


![unix.jpg](http://conque.googlecode.com/svn/wiki/screenshot/unix.jpg)
![windows.jpg](http://conque.googlecode.com/svn/wiki/screenshot/windows.jpg)


Usage
---
Type :ConqueTerm <command> to run your command in vim, for example:

```vim
:ConqueTerm bash
:ConqueTerm mysql -h localhost -u joe -p sock_collection
:ConqueTerm Powershell.exe
:ConqueTerm C:\Python27\python.exe
```

To open ConqueTerm in a new horizontal or vertical buffer use:

```vim
:ConqueTermSplit <command>
:ConqueTermVSplit <command>
:ConqueTermTab <command>
```

All text typed in insert mode will be sent to your shell.
Use the `<F9>` key to send a visual selection from any buffer to the shell.

For more help type :help ConqueTerm

Lisence
---
Copyright (C) 2009-2011 Nico Raffo  
Released under the MIT license  
https://github.com/wkentaro/conque.vim/blob/master/LICENSE
