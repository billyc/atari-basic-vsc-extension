# Atari FastBasic language support

A very simple extension which enables syntax highlighting for FastBasic files.

- Enables FastBasic syntax highlighting for `.bas` and `.fb` filename extensions
- Full-line comments start with apostrophe `'` or period `.` -- and end of line comments after any statements, using apostrophe `'`
- FastBasic statements and functions highlighted in different color than flow control statements
  (loops, procs, etc)
- Case-insensitive
  - EXCEPT: variable names that are in all-caps are highlighted as system constants
- Should highlight integers, floating point, and hex values as constants (probably needs some testing)

That's about it! Have fun :-)

**Sample Code**
![Sample Code](https://github.com/billyc/atari-basic-vsc-extension/raw/main/screenshot.png)


