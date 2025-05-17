
# tabline.vim

Configure tab labels within Terminal Vim with a very succinct output.

![Tabline Screenshot](https://raw.github.com/dcchuck/tabline.vim/master/screenshots/tabline.png)

- Tab number
- Filename (basename only)
- [+] if the current buffer has been modified

Tabs in this case, refer to Vim Tabs and not the Terminal.app tabs.

Based on settings found from [offensive
thinking](http://www.offensivethinking.org/data/dotfiles/vimrc).

## Changes

Thanks to [mkitt](http://github.com/mkitt/tabline.vim) for repo. This fork does not have the modified flag in the tabs and is right aligned. Colors set as written below.

## Configuration
Currently there are no configuration variables to define, you either
rock it or you don't. This may change at some point in the future.

Make sure to set the following settings within your color theme: 

```
hi TabLine      ctermfg=Black  ctermbg=Green     cterm=NONE
hi TabLineFill  ctermfg=Black  ctermbg=Green     cterm=NONE
hi TabLineSel   ctermfg=White  ctermbg=DarkBlue  cterm=NONE
```

