# 1. sed command
```
-e : Add the script to the commands to be executed
(if ommited, the first non-option argument string is taken as the script)
-f : Add the script-file to the commands to be executed
-n : Suppress automatic printing of pattern space
-i : Directly modify the file
```
## 1.1 Common sed commands
```
'2a text' : Append text after line 2
'2a text\
text2' : Append text after line 2
'2,4c text' : Change line 2 to 4 with text
'2,4d' : Delete line 2 to 4
'2,4p' : Print line 2 to 4
'2,4s/old/new/g' : Substitute old with new in line 2 to 4
'/old/p': Search for old and print
```
## 1.2 Combine multiple sed commands
```
nl testfile | sed -n '/oo/{s/oo/kk/;p;q}'
```


