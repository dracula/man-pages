# Dracula Universal for [man-pages](https://man7.org/linux/man-pages/man1/man.1.html)

> A dark theme for [man-pages](https://man7.org/linux/man-pages/man1/man.1.html)

![man](https://user-images.githubusercontent.com/96319944/232507545-1e08c499-f41c-4258-a036-3086d5732b52.png)


## Install

Man-pages can now be themed universally meaning the same code works for both Dracula & Dracula Pro.

The only requirement is using [less](https://man7.org/linux/man-pages/man1/less.1.html) for MANPAGER

Add this first to your .zshrc to use less as MANPAGER:

  export MANPAGER="/usr/bin/less -s -M +Gg"

Please note the location of less may be different on macOS

M1 location

  export MANPAGER="/opt/homebrew/bin/less -s -M +Gg"


Then simply add this to your .zshrc to define the colors:

  export LESS_TERMCAP_mb=$'\e[1;31m'
  export LESS_TERMCAP_md=$'\e[1;34m'
  export LESS_TERMCAP_so=$'\e[01;45;37m'
  export LESS_TERMCAP_us=$'\e[01;36m'
  export LESS_TERMCAP_me=$'\e[0m'
  export LESS_TERMCAP_se=$'\e[0m'
  export LESS_TERMCAP_ue=$'\e[0m'
  export GROFF_NO_SGR=1

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
