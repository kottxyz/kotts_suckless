# Kott's patched fork of Suckless software

Suckless software is awesome when it's patched, so I picked some necessary patches and applied them. Here's the list:

### DWM:
- fullgaps-toggle
- swallow
- hide vacant tags
- pertag
- movestack
- alwayscenter
- moveresize

### ST:
- expected-anysize
- scrollback + scrollback-mouse
- gruvbox-dark
- alpha

### DMENU:
- caseinsensitive
- fuzzyhighlight
- lineheight

### SLOCK:
- background-image

# USAGE

Edit `config.h` file to make changes (customize paths and other parameters) and then run `sudo make clean install` command to get changes working.
