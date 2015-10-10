#1: Basics
---
###1.1: Running a terminal
---
1. `ctrl + alt + t`

---
###1.2: Our first command
---
1. `echo "hello, world"` , `echo hello, world`
2. `ctrl-c`

---
###1.3: Man pages
---
1. display a line of text
2. `echo -n`

---
###1.4: Editing the line
---
1. use up-arrow to repeat commands
2. use ctrl-A, ctrl-E, or arrow keys to navigate and edit

---
###1.5: Cleaning up
---
1. type `clear` , `ctrl-l`
2. type `exit` , `ctrl-d`

---
###1.6: Summary
---
1. `echo 'Use "man echo"'`
2. `sleep 5s` , `sleep 5000s` , `ctrl-l`

---
#2: Manipulating files
---
###2.1: Redirecting and appending
---
1. `echo "From fairest creatures we desire increase," > line_1.txt` , `echo "That thereby beauty's rose might never die," > line_2.txt`
2. `echo "From fairest creatures we desire increase," > sonnet_1_copy.txt` , `echo "That thereby beauty's rose might never die," >> sonnet_1_copy.txt` , `diff sonnet_1.txt sonnet_1_copy.txt`
3. `cat line_2.txt line_1.txt > sonnet_1_reversed.txt`

---
###2.2: Listing
---
1. `ls s*`
2. `ls -rtl *onnet*`
3. `ls -artl`

---
###2.3: Renaming, copying, deleting
---
1. `echo "hello, world" > foo.txt` , `cp foo.txt bar.txt` , `diff foo.txt bar.txt`
2. `cat foo.txt > baz.txt`
3. `cat foo.txt bar.txt > quux.txt`
4. rm nonexistant asks for confirmation, rm -f nonexistant does not ask for comfirmation

---
###2.4: Summary
---
1. `echo "FRom faireſt creatures we deſire increaſe, That thereby beauties Roſe might neuer die, But as the riper ſhould by time deceaſe, His tender heire might beare his memory: But thou contracted to thine owne bright eyes, Feed’ſt thy lights flame with ſelfe ſubſtantiall fewell, Making a famine where aboundance lies, Thy ſelfe thy foe,to thy ſweet ſelfe too cruell: Thou that art now the worlds freſh ornament, And only herauld to the gaudy ſpring, Within thine owne bud burieſt thy content, And tender chorle makſt waſt in niggarding:    Pitty the world,or elſe this glutton be,    To eate the worlds due,by the graue and thee." > sonnet_1_complete.txt` , `cat sonnet_1_complete.txt`
2. `touch foo`, `mv foo bar`, `cp bar baz`
3. `ls b*`
4. `rm ba*`

---
3: Inspecting files
---
###3.1: Downloading a file
---
1. 200 ok , status code of learnenough.com is 301 Moved Permanently
2. `ls -l sonnets.txt` , 96635 bytes
3. `ls -lh sonnets.txt`
4. `ls -hartl` , hartl the author's last name

---
###3.2: Making heads and tails of it
---
1. `tail sonnets.txt | wc`
2. `head -n 18 sonnets.txt`
3. `head -n 18 sonnets.txt | tail -n 14`
4. `ping learnenough.com > learnenough.log` , `tail -f learnenough.log`

---
###3.3: Less is more
---
1. press `spacebar` x3, press `ctrl-b` x3, `G`(capital g), `1G` , `q`
2. `/All`, press `n`, press `N`, 10 "Alls"
3. `less sonnets.txt`, `/Let me not`, no
4. `ls -Cl`

---
###3.4: Grepping
---
1. `grep -n rose sonnets.txt`
2. `less sonnets.txt`, `2203G`
3. `grep -n rose sonnets.txt | head -n 1`
4. `grep Rose sonnets.txt`
5. `grep Rose sonnets.txt | grep -v rose | wc`

---
###3.5: Summary
---
1. `history | less` , uname -r
2. `history | wc`, 401
3. `history | grep`, 402
4. `!402`, `!401`
5. -O=remote-output=write output to a file named as the remote file, -L=location/follows redirects

---
#4: Directories
---
###4.1: Structure
---
1. ~/foo/bar = root slash foo slash bar
2. home dir = users, username = bill, deepest directory = sonnets
3. ~/sonnets belongs to the superuser/root, Users/bill/sonnets belongs to a user named bill

---
###4.2: Making directories
---
1. `mkdir -p <name>`
2. `mkdir -p ~/foo/bar`
3. `ls | grep o`

---
###4.3: Navigating directories
---
1. they don't differ, they both change the current directory to home directory
2. `cd text_directory`, `cd ..`
3. `cd text_directory`, `touch nil`
4. `../nil`

---
###4.4: Renaming, copying, deleting directories
---
1. `mkdir ~/foo/bar`, `mv ~/foo/bar ~/foo/baz`
2. `cp -r ../text_files foo`
3. `cp -r ../text_files/ bar`
4. `rm -rf foo`

---
###4.5: Summary
---
1. `mkdir foo && cd foo && touch baz > bar && cd`
2. no commands are executed because it won't create the same directory again
3. force removes all files on the system
4. by adding "sudo" to the beginning, anybody can use the command
