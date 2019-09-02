# vim-bow-wob

This is a colorscheme that consists of almost exclusively black-ish and
white-ish. The primary "colors" are very close to black and white, but slightly
off in a way that hopefully makes it a bit nicer to look at.

I have tried to find all places that should _not_ be black on white or vice
versa (e.g. whitespace characters, colorcolumn), but I have probably missed
some. If you notice anything that is illegible, please make an issue.

## Settings

This colorscheme has 2 settings:

```vim
" By default, italics are used for various things.
" If your terminal doesn't support italics, set this to 0
let g:bow_terminal_italics = 1

" By default, spelling errors (from `set spell`) have wiggly underlines.
" If you would rather have normal underlines, set this to 0
let g:bow_spell_undercurl = 1
```

## Credit

This theme is based on [vim-colors-pencil][vim-colors-pencil].

[vim-colors-pencil]: https://github.com/reedes/vim-colors-pencil
