## MOVE
```
hjkl: move left, down, up, right
w: move to the beginning of the next word
b: move to the beginning of the previous word
e: move to the end of the next word
E: move to the end of the next word
0: move to the beginning of the line
^: move to the first non-blank character of the line
$: move to the end of the line
gg: move to the beginning of the file
G: move to the end of the file
fx: move to the next occurrence of x
Fx: move to the previous occurrence of x
;: repeat the last f, t, F, or T command
,: repeat the last f, t, F, or T command in the opposite direction
%: move to the matching parenthesis
(: move to the beginning of the current sentence
): move to the beginning of the next sentence
{: move to the beginning of the current paragraph
}: move to the beginning of the next paragraph
C-u(d): move up(down) half a page
C-f(b): move forward(backward) one page
```
## NORMAL MODE
```
x: delete character under cursor
X: delete character before cursor
dd: delete current line
d+command: delete text specified by command
yy: yank current line
y+command: yank text specified by command
ci(: change the word inside ()
ca(: change the word and ()
```
NOTE：d will yank the text as well.
## INSERT MODE
```
i: insert before cursor
a: insert after cursor
o: insert new line below current line
O: insert new line above current line
```
## VISUAL MODE
```
v: enter visual mode
V: enter visual line mode
```
## COMMAND MODE
```
:w: save file
:q: quit
:q!: quit without saving
:wq: save and quit
```
## SEARCH MODE
```
/: search forward
n: go to next search result
N: go to previous search result
```
## COMMANDS
```
cat: concatenate files and print on the standard output
ls: list directory contents
cd: change directory
pwd: print name of current/working directory
mv: move files
cp: copy files
rm: remove files or directories
mkdir: make directories
rmdir: remove empty directories
touch: change file timestamps
echo: display a line of text
```
## REPLACE

```
:[scope]s/ori/sub/[flag]
flag:
/g :global
/c :confirm(yes/no/all/quit/leave=yes+quit)
/i :ingore lower/upper case
/e :error
scope:
(default):this line
%:all lines
a,b:between line a and b
```



## EXTRA

```
:help: open help
:%s/old/new/g: replace all occurrences of old with new
:%s/REGEX/new/g: replace all occurrences of REGEX with new
```