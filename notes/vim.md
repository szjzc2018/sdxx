## VIM NOTES

```
NORMAL MODE:
(1) MOVE
- h/j/k/l: left/down/up/right
(2) delete
- dd: delete line
- dw, da(2)w: delete word, delete 1(2) word
- d$(0): delete to end(beginning) of line
- d2j/k: delete 2 lines(2j/k)
(3) copy
- yy: copy line
- yw, ya(2)w: copy word, copy 1(2) word
- y$(0): copy to end(beginning) of line
(4) cut
- x: cut character
- xp: cut and paste
- xw, xa(2)w: cut word, cut 1(2) word
- x$(0): cut to end(beginning) of line
(5) paste
- p: paste after cursor
- P: paste before cursor
(6) undo/redo
- u: undo
- ctrl+r: redo
(7) search
- /: search
- n: next search
- N: previous search
(8) change
- cw, ca(2)w: change word, change 1(2) word
- c$(0): change to end(beginning) of line
(9) replace
- :%s/old/new/g: replace all old with new
- :%s/old/new/gc: replace all old with new with confirmation
(10) save/quit
- :w: save
- :q: quit
- :q!: quit without saving
```

```
VISUAL MODE:
(0) enter visual mode
- v: enter visual mode
- V: enter visual line mode
- ctrl+v: enter visual block mode
(1) select
- h/j/k/l: left/down/up/right
- w: select word
- $(0): select to end(beginning) of line
(2) copy
- y: copy
(3) cut
- x: cut
(4) paste
- p: paste after cursor
- P: paste before cursor
(5) undo/redo
- u: undo
- ctrl+r: redo
```

```
Useful commands:
- :set number: show line number
- .: repeat last command
- :line_number
```