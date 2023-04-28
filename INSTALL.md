### [man-pages](https://man7.org/linux/man-pages/man1/man.1.html)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash

    git clone https://github.com/dracula/man-pages.git

```

#### Install manually

- Download using the [manpages.zip](https://github.com/dracula/man-pages/files/11354972/manpages.zip) link or
- Download using the [GitHub `.zip` download](https://github.com/dracula/man-pages/archive/refs/heads/main.zip) option and unzip them.

#### Requirements

The only requirement is using [less](https://man7.org/linux/man-pages/man1/less.1.html) for MANPAGER

#### Activating theme

1. Add this first to your .zshrc to use less as MANPAGER:

        export MANPAGER="/usr/bin/less -s -M +Gg"

Please note the location of [less](https://man7.org/linux/man-pages/man1/less.1.html) may be different on macOS

M1 location

        export MANPAGER="/opt/homebrew/bin/less -s -M +Gg"
       
2. Simply add this to your .zshrc to define the colors:

        export LESS_TERMCAP_mb=$'\e[1;31m'      # begin bold
        export LESS_TERMCAP_md=$'\e[1;34m'      # begin blink
        export LESS_TERMCAP_so=$'\e[01;45;37m'  # begin reverse video
        export LESS_TERMCAP_us=$'\e[01;36m'     # begin underline
        export LESS_TERMCAP_me=$'\e[0m'         # reset bold/blink
        export LESS_TERMCAP_se=$'\e[0m'         # reset reverse video
        export LESS_TERMCAP_ue=$'\e[0m'         # reset underline
        export GROFF_NO_SGR=1                   # for konsole
