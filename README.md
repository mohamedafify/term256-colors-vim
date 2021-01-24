Usage:
---------------------------------------------------------
Show you the colors for any terminal emulator that supports 256-color to customize your syntax highlighting for vim.

Installation:
---------------------------------------------------------
```
git clone https://github.com/mohamedafify/term256-colors-vim.git
cd term256-colors-vim/vim
```
copy the termcolors.vim color theme that highlights the numbers according to its color in numbers.
```
cp colors/termcolors.vim ~/.vim/colors
```
copy the syntax file which defines the colors to the numbers.
```
cp syntax/c.vim ~/.vim/syntax
```
OR
```
cp syntax/c.vim ~/.vim/after/syntax
```
if you don't want to mess up your c.vim syntax file.

If any folder doesn't exist create it.

You can use any syntax extenstion file just rename the 'c.vim' file to 'extenstion.vim'.

add these two lines in your ~/.vim/vimrc
```
syntax enable
colorscheme termcolors
```

open colors.c file
