# clutter your HOME

I'm sick of software keeping itself "nice and tidy" nested in stupid directories with stupid names. I like chaos and knowing deep down inside that anything I need is a single tilde away.

A lot of programs are notorious for creating crap in some nested directory structure cluttering your .config. Most of these read an environment variable to fix this egregious behavior.

```
ls -la ~ | wc -l
1452
```

Ah. Perfect. My mind is now clear.


## XDG_CRAP_DIR

FreeDesktop are the evil entity taking my tilde away. Thankfully their own efforts can be used against them to bring chaos and peace back HOME.

```
export XDG_CACHE_HOME=~
export XDG_CONFIG_HOME=~
export XDG_DATA_HOME=~
export XDG_RUNTIME_DIR=~
export XDG_DATA_DIRS=~
export XDG_CONFIG_DIRS=~
```


## GOOD HOME respecting software

This page has a list of software that respects your Wife, Children and your HOME: https://wiki.archlinux.org/index.php/XDG_Base_Directory

- ALSA:     `~/.asoundrc`
- AzPainer: `~/.azpainter`
- BitchX:   `~/.BitchX` (Don't tell your parents)
- Firefox:  `~/.mozilla`
- GnuPG:    `~/.gnupg`
- Nix:      `~/.nixpkgs`, `~/.nix-profile`, `~/.nix-defexpr`, `~/.nix-channels`
- OpenSSH:  `~/.ssh`
- Shells:   `~/.shellrc`
- Surf:     `~/.surf`
- URxvt:    `~/.urxvt`
- bim:      `~/.biminfo`
- dosbox:   `~/.dosbox`
- feh:      `~/.fehbg`
- howl:     `~/.howl`
- nodejs:   `~/.node_repl_history`
- npm:      `~/.npm`
- pass:     `~/.password-store`
- vim:      `~/.vim`
- weechat:  `~/.weechat`
- xsel:     `~/.xsel.log` (This one is a MUST HAVE)

## BAD BAD BAD SHAME LIST

This page has a list of software that disrespects your Wife, Children and your HOME: https://wiki.archlinux.org/index.php/XDG_Base_Directory

- ????: `$XDG_CRAP_HOME/jesseduffield` (WHO?)
- aerc: `$XDG_CRAP_HOME/aerc`
- berry: `$XDG_CRAP_HOME/berry`
- bspwm: `$XDG_CRAP_HOME/bspwm`
- cmus: `$XDG_CRAP_HOME/cmus`
- falkon: `$XDG_WHERE?/falkon`
- gh:   `$XDG_CRAP_HOME/fg`
- glib: `$XDG_CRAP_HOUSE/glib-2.0`
- grafx2: `$XDG_CRAP_HOME/grafx2`
- htop: `$XDG_CRAP_HOME/htop`
- i3: `$XDG_CRAP_HOME/i3`
- keepassc: `$XDG_CRAP_HOME/keepassc`
- mpv: `$XDG_CRAP_HOME/mpv`
- neofetch: `$XDG_CRAP_HOME/neofetch`
- openbox: `$XDG_CRAP_HOME/openbox`
- sxhkd: `$XDG_CRAP_HOME/sxhkd`
- wal: `$XDG_CRAP_HOME/wal`
