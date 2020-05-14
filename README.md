# st-zi

st-zi is my personal build of st (simple terminal) with useful patches for my workflow.

## Patches
- Alpha (Transparency)
- Bold is not bright
- Font2
- Keyboard Select (not used for now)
- Scrollback (Mouse Scrollwheel, Alt + j/k, or Alt + PgUp/PgDown)
- Xresources

## Installation

### Manual
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install
    
### Arch Linux
If you are using Arch Linux, st-zi is available on [Arch User Repository](https://aur.archlinux.org/packages/st-ziro-git/).
