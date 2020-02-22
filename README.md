# clutter your home

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
```

