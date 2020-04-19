# Foreword

I have forked this from [ParamagicDev's medic_chalk](https://github.com/ParamagicDev/vim-medic_chalk) who forked from [Tpope's Vividchalk](https://github.com/tpope/vim-vividchalk)
and slightly modified it.

All credit goes to both. Check them out. Tpope has many great Vim plugins.

## Installation

```vimL
call plug#begin()
  Plug 'rarean/vim-rare_chalk'
call plug#end()

colorscheme rare_chalk
```


Below is a sample for `~/.Xresources` taken from RomainL

    *.foreground: #FFFFFF
    *.background: #000000
    *.color0:     #000000
    *.color8:     #111111
    *.color1:     #FFA500
    *.color9:     #FF6600
    *.color2:     #66FF00
    *.color10:    #99CC99
    *.color3:     #FFCC00
    *.color11:    #FFEE98
    *.color4:     #5F87AF
    *.color12:    #33C9C9
    *.color5:     #9933CC
    *.color13:    #AA1BF2
    *.color6:     #88B5C3
    *.color14:    #AABBEE
    *.color7:     #FFFFFF
    *.color15:    #808080

## Differences from Medic_Chalk

There aren't many differences,

I added syntax highlighting for ES6 jascript and various React plugins.

Overall, it's pretty much the same just with a few adjustments. TPope did
All the heavy lifting on this one.
