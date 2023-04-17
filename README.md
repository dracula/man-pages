# Dracula Universal for [man-pages](https://man7.org/linux/man-pages/man1/man.1.html)

> Dracula Universal theme for [man-pages](https://man7.org/linux/man-pages/man1/man.1.html)

![man](https://user-images.githubusercontent.com/96319944/232594745-3ad2644c-682e-4ea9-82e6-dbf91028f78b.png)


## Install

Man-pages can now be themed universally meaning the same code works for both Dracula & Dracula Pro.

The only requirement is using [less](https://man7.org/linux/man-pages/man1/less.1.html) for MANPAGER

## Step 1

Add this first to your .zshrc to use [less](https://man7.org/linux/man-pages/man1/less.1.html) as MANPAGER:

  export MANPAGER="/usr/bin/less -s -M +Gg"


Please note the location of [less](https://man7.org/linux/man-pages/man1/less.1.html) may be different on macOS

M1 location

  export MANPAGER="/opt/homebrew/bin/less -s -M +Gg"

![less](https://user-images.githubusercontent.com/96319944/232594938-f9357c93-1f2b-4f1d-aee4-b9511b4b1227.png)

## Step 2

Then simply add this to your .zshrc to define the colors:

export LESS_TERMCAP_mb=$'\e[1;31m'     
export LESS_TERMCAP_md=$'\e[1;34m'     
export LESS_TERMCAP_so=$'\e[01;45;37m' 

export LESS_TERMCAP_us=$'\e[01;36m'    
export LESS_TERMCAP_me=$'\e[0m'        
export LESS_TERMCAP_se=$'\e[0m'        
export LESS_TERMCAP_ue=$'\e[0m'        
export GROFF_NO_SGR=1                        

![colors](https://user-images.githubusercontent.com/96319944/232595015-053d22a3-dae8-43f8-8f1d-b4cd23d75fa2.png)

Download config

[manpages.zip](https://github.com/urrickhunt/Dracula-universal-for-manpages/files/11251263/manpages.zip)


## Team

This theme is maintained by the following person(s).

| [![urrickhunt](https://github.com/urrickhunt.png?size=100)](https://github.com/urrickhunt) |
| ---------------------------------------------------------------------------------------- |
| [urrickhunt](https://github.com/urrickhunt)                                               |

## Community

- [Twitter](https://twitter.com/draculatheme) - Best for getting updates about themes and new stuff.
- [GitHub](https://github.com/dracula/dracula-theme/discussions) - Best for asking questions and discussing issues.
- [Discord](https://draculatheme.com/discord-invite) - Best for hanging out with the community.

## License

[MIT License](./LICENSE)
