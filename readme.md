## Shopify Liquid Syntax

This is a fork of [Shopify Siteleaf Syntax](https://github.com/siteleaf/liquid-syntax-mode) which is a fork of [shopify-liquid](https://bitbucket.org/granteagon/shopify-liquid) syntax, which was based off of the Djaniero package for Django.

This is a work in progress, and is meant to be used in conjunction with a couple other Shopify Sublime Text Packages I'm developing. Eventually this will just be for syntax-related stuff - highlighting and setting Sublime Text's language scope.

## Changes so far:
* Autocomplete for `{%` and `{{` differs from original package by using a `.sublime-keymap` file.
* Removed `tag.sublime-snippet`. Corrected misnaming of `if.sublime-snippet` which contained content intended for `tag.sublime-snippet`.