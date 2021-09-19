
# VIM

### Tips and tricks

i insert
I insert begining of the line
a insert next caracter
A insert end of line
o insert next line
O insert line before
S delete line and go insert mode

:wq save file and quit
:w save file
:q quit
:x save and quit
ZZ save and quit (zair and zalvar)


yy copy line 
p paste the content copied
y3y copy 3 lines

dd cut line 
p paste the line cut

v + arrow key + y -> go to visual mode, we can select part of the line, y to copy the content
p paste part of the line copied above

v + arrow key + d -> to delete part of the line selected
p paste content deleted above


Ctrl + V Select vertical mode (collums)
y copy the content selected above
p paste the content

yw copy one word
y3w copy 3 words

x delete caracter
X delete caracter before (like backspace)

:w new-file-name -> Save as...

:split /etc/hosts -> open second file in the same vim window
CTRL + ww => change to next area
yy copy one line 

:r /etc/hosts -> brings the /etc/hosts content to the current file

/NOTE search the word NOTE in the file
n search the next NOTE word in the file 

?NOTE search the previously NOTE (reverse search)
n search the previously word NOTE 

:15s/word/new-word -> change word to new word on line 15 only

:13,22s/ctrl/controle/ -> change ctrl to controle on line 13 to 22

:%s/word/WORD/g -> change word to WORD in the whole/entire file

:set number -> enumer the file line (just show/view on the screen)
:set nu -> same above
:set nonu -> remove numbers

:syntax on -> recognize file extension like .txt .sh. .py 
