
* Freedesktop's XDG environment variables

Freedesktop's XDG env vars^{ [2]} like XDG_CACHE_HOME=~,

XDG_CONFIG_HOME=~ and many more is a key to keep

your home directory messy because nine out of ten

software follows them. If they don't follow those

conventions, most of them have a flag to change

paths the software use for something.



Make sure to set them as they tend to drastically increase

the clutter in your home directory.

* More env vars

A lot of Unix tools are notorious for creating dotfiles and cluttering your

.config directory (i3, htop, gtk3 for example). But most of these read an env var

that points to the path of the configuration file or has a flag that

changes some kind of path. Some of these and their

env var/flag will be listed below for your benefit. If something that you use

isn't here, check the man page and make sure to make an issue so people

in the future can benefit too!



| Tool          | Env var                       | Flag                      |

|---------------+-------------------------------+---------------------------|

| less          | LESSHISTFILE=~                | -                         |

| gnupg         | GNUPGHOME=~                   | -                         |

| readline      | INPUTRC=~                     | -                         |

| ksh^{*}       | ENV=~                         | -                         |

| zsh^{*}       | ZDOTDIR=~                     | -                         |

| dialog        | DIALOGRC=~                    | -                         |

| mail          | MAIL=~                        | -                         |

| shell-history | HISTFILE=~                    | -                         |

