# Arcana

Scribe your glyphs in inks carefully chosen to illuminate the secrets of your
incantations.

Arcana is a semantically themed dark colour scheme for Neo/Vim based on an
extended palette of the kanagawa theme.


## Theming

This remix is designed to be slightly warmer and easier on the eyes over long
sessions. The colours are themed to try to give a general 'feeling' of the
layout without losing enough contrast to make distinguishing individual features
difficult.

- Type-level tokens are in a cooler, blue-ish spectrum
- Value-level tokens are warm and yellow
- Keywords are various shades of red
- Scope-altering tokens are purples, as a mix of types, values and keywords
- Operators and constants are vibrant oranges to ensure they pop out

Tokens which blur the line between several categories are colours which indicate
that (eg. constructors often represent both type- and value-level items, so are
green rather than a blue or yellow).


## Install

The recommended approach is to use Neo/Vim's built-in plugin manager (see
[:help package](https://vimhelp.org/repeat.txt.html#packages)). Simply
clone/download this repository to `pack/<name>/<start|opt>/arcana`, where
`<name>` can be whatever you like, and `<start|opt>` should be `start` if you
want to load the theme by default, or `opt` if you want to load it explicitly.
Nightly versions of Neovim also have a built-in plugin manager which manages
cloning as well (see
[:help vim.pack](https://neovim.io/doc/user/pack/#vim.pack)).

If you prefer to use an external plugin manager, follow the usual instructions
for that package.


## Treesitter

Note that this theme extends and tweaks treesitter highlight groups when loaded
by default. See `:help arcana` if you would like to disable this feature.


## Transparent background

By default, Arcana uses a transparent background to allow things like `tmux` to
set different backgrounds for active/inactive panes. See `:help arcana` if you
would like to disable this feature.


## Acknowledgments

- Being an extended remix of the palette, Arcana owes a lot to
  [kanagawa](https://github.com/rebelot/kanagawa.nvim). Check it out if you want
  something more configurable or with different theming.
- Arcana is built with
  [vim-colortemplate](https://github.com/lifepillar/vim-colortemplate) (v2 for
  Neovim compatibility), an excellent tool if you want to create your own
  colour scheme.
