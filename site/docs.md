---
title: docs
x-toc-enable: true
---
find astro  
[available on codeberg](https://codeberg.org/yamlynn/astro)  
[available on github](https://github.com/sweetpotatopress/astro)  

## how to install

- install ncurses (most os have it by default)  
- `make` to build locally  
- `doas make install` to install to $PATH (sudo is also acceptable)  
- optionally create a file names `config` in `$XDG_CONFIG_HOME/astro` (typically ~/.config/astro) if you would like to create a default iana timezone and location. currently it has to be in the same order shown in the README. if you dont know the lat. and long. you can find it by searching the location in the program :D  

## how to set default location

- open astro
- press i to open the input data menu
- search for your city
- draw the chart
- press c to open config
- press tab to fill config automatically.
- press enter to save, setting the defaults for each open of astro

## contribution guidelines

- target c99 and posix 200809L, compile without error or warning with `make debug`  
- snake_case, all caps MACRO, no strcpy or continue. brackets on their own line  
- no typedef  
- a sense of love  

---
