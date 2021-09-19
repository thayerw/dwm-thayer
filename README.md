# dwm-thayer

This repository contains my customizations to the dwm tiling window manager for X.

## Patches

As much as I love dwm's minimilistic approach, I find that some community patches significantly improve my workflow and overall user experience. The
following patches have been incorporated into my config:

* [barheight](https://dwm.suckless.org/patches/bar_height/): allows the statusbar height to be defined in user config
* [cyclelayouts](https://dwm.suckless.org/patches/cyclelayouts/): cycle back/forward through layouts with key binds (Mod+Up/Mod+Down by default)
* [fakefullscreenclient](https://github.com/bakkeby/patches/wiki/fakefullscreenclient): applications can enter fullscreen mode within their client window, on an individual basis
* [maximize](https://dwm.suckless.org/patches/maximize/): enables floating clients to be maximized vertically and/or horizontally using key binds
* [noborder](https://dwm.suckless.org/patches/noborder/): removes the client border when only one client is visible
* [pertag](https://dwm.suckless.org/patches/pertag/):  layout, mwfact, barpos and nmaster are applied to individual tags
* [scratchpad](https://dwm.suckless.org/patches/scratchpad/):  spawn a floating terminal window, and dynamically show/hide the terminal across all tags using a key bind
* [shiftview](https://github.com/chau-bao-long/dotfiles/blob/master/suckless/dwm/shiftview.diff): cycle back/forward through tags using a key bind (mod+left/mod+right by default)
* [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/): adds preconfigured and dynamically updated gaps around client windows; also provides several layout styles, including bottomstack, spiral, etc.
* [zoomswap](https://dwm.suckless.org/patches/zoomswap/): zoomed clients (Mod+Enter) return to their original position in the stack when swapped back

## Patch workflow

Managing patches is a hot topic for many users. I prefer to add patches manually using `git apply <patchname>.diff`, as I often modify the patch files beforehand in order to suit my needs. Once you familiarize yourself with dwm's source code, it's pretty easy to decipher changes between revisions.

## Installation

For instructions on how to install and run dwm, see the README file in the [master branch](https://github.com/thayerwilliams/dwm-thayer/tree/master), or visit <https://dwm.suckless.org/>. My configuration has no additional requirements beyond what is normally needed to build and execute dwm.

