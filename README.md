# st - simple terminal

My personal configuration of the st Terminal emulator.


## Requirements

In order to build st you need the Xlib header files.
To use this configuration without changes, install the FiraCode Medium Font

## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```bash
make clean install

```

## Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```bash
tic -sx st.info
```

See the man page for additional details.

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

