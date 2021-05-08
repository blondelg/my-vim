# my-vim
After having been lost in many plugins tutorials, I decided to strenghen the basics of vim learning by setting up a **pluggin free** .vimrc file, plus some commands I must know to leverage my vim experience.

# Cheatsheet

## Search files
:Ex Open file explorer
-   Go to parent folder in file explorer
:bd Close file explorer
:find <file name> Open file from its filename
:find <fuzzy file pattern> + Tab Shows recursives matches of the file pattern
                             files can be navigated by keyboard arrows and opened by press Enter

## Search words
:/<pattern> Highligh patterns, go to the first
n           Go to the next pattern
N           Go to the previous pattern
:noh        Clear pattern highlighting

## Split screen

## Terminal interface
:! <term command> Execute terminal command from vim
Ctrl + z          Switch from vim to terminal
fg                Go back to vim from terminal 
