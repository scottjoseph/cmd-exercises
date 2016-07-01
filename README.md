# Learn Enough Command Line to be Dangerous - Exercise Answers

## Table of Contents
- [1: Basics](#1-basics)
  - [1.1: Running a terminal](#11-running-a-terminal)
    - [Exercise: 2](#exercise-2)
  - [1.2: Our first command](#12-our-first-command)
    - [Exercise: 1](#exercise-1)
    - [Exercise: 2](#exercise-2-1)
  - [1.3: Man pages] (#13-man-pages)
    - [Exercise: 1](#exercise-1-1)
    - [Exercise: 2](#exercise-2-2)
  - [1.4: Editing the line](#14-editing-the-line)
    - [Exercise: 1](#exercise-1-2)
    - [Exercise: 2](#exercise-2-3)
  - [1.5: Cleaning up](#15-cleaning-up)
    - [Exercise: 1](#exercise-1-3)
    - [Exercise: 2](#exercise-2-4)
  - [1.6: Summary](#16-summary)
    - [Exercise: 1](#exercise-1-4)
    - [Exercise: 2](#exercise-2-5)
- [2: Manipulating files](#2-manipulating-files)
  - [2.1: Redirecting and appending](#21-redirecting-and-appending)
    - [Exercise: 1](#exercise-1-5)
    - [Exercise: 2](#exercise-2-6)
    - [Exercise: 3](#exercise-3-3)
  - [2.2: Listing](#22-listing)
    - [Exercise: 1](#exercise-1-6)
    - [Exercise: 2](#exercise-2-7)
    - [Exercise: 3](#exercise-3-1)
  - [2.3: Renaming, copying, deleting](#23-renaming-copying-deleting)
    - [Exercise: 1](#exercise-1-7)
    - [Exercise: 2](#exercise-2-8)
    - [Exercise: 3](#exercise-3-2)
    - [Exercise: 4](#exercise-4)
  - [2.4: Summary](#24-summary)
    - [Exercise: 1](#exercise-1-8)
    - [Exercise: 2](#exercise-2-9)
    - [Exercise: 3](#exercise-3-3)
    - [Exercise: 4](#exercise-4-1)
- [3: Inspecting files](#3-inspecting-files)
  - [3.1: Downloading a file](#31-downloading-a-file)
    - [Exercise: 1](#exercise-1-9)
    - [Exercise: 2](#exercise-2-10)
    - [Exercise: 3](#exercise-3-4)
    - [Exercise: 4](#exercise-4-2)
  - [3.2: Making heads and tails of it](#32-making-heads-and-tails-of-it)
    - [Exercise: 1](#exercise-1-10)
    - [Exercise: 2](#exercise-2-11)
    - [Exercise: 3](#exercise-3-5)
    - [Exercise: 4](#exercise-4-3)
  - [3.3: Less is more](#33-less-is-more)
    - [Exercise: 1](#exercise-1-11)
    - [Exercise: 2](#exercise-2-12)
    - [Exercise: 3](#exercise-3-6)
    - [Exercise: 4](#exercise-4-4)
  - [3.4: Grepping](#34-grepping)
    - [Exercise: 1](#exercise-1-12)
    - [Exercise: 2](#exercise-2-13)
    - [Exercise: 3](#exercise-3-7)
    - [Exercise: 4](#exercise-4-5)
    - [Exercise: 5](#exercise-5)
  - [3.5: Summary](#35-summary)
    - [Exercise: 1](#exercise-1-13)
    - [Exercise: 2](#exercise-2-14)
    - [Exercise: 3](#exercise-3-8)
    - [Exercise: 4](#exercise-4-6)
    - [Exercise: 5](#exercise-5-1)
- [4: Directories](#4-directories)
  - [4.1: Structure](#41-structure)
    - [Exercise: 1](#exercise-1-14)
    - [Exercise: 2](#exercise-2-15)
    - [Exercise: 3](#exercise-3-9)
  - [4.2: Making directories](#42-making-directories)
    - [Exercise: 1](#exercise-1-15)
    - [Exercise: 2](#exercise-2-16)
    - [Exercise: 3](#exercise-3-10)
  - [4.3: Navigating directories](#43-navigating-directories)
    - [Exercise: 1](#exercise-1-16)
    - [Exercise: 2](#exercise-2-17)
    - [Exercise: 3](#exercise-3-11)
    - [Exercise: 4](#exercise-4-7)
  - [4.4: Renaming, coping, deleting directories](#44-renaming-copying-deleting-directories)
    - [Exercise: 1](#exercise-1-17)
    - [Exercise: 2](#exercise-2-18)
    - [Exercise: 3](#exercise-3-12)
    - [Exercise: 4](#exercise-4-8)
  - [4.5: Summary](#45-summary)
    - [Exercise: 1](#exercise-1-18)
    - [Exercise: 2](#exercise-2-19)
    - [Exercise: 3](#exercise-3-13)
    - [Exercise: 4](#exercise-4-9)

## 1: Basics

### 1.1: Running a terminal

#### Exercise: 2

Q: By examining the menu items for your terminal program, figure out how to create a new tab. 

Extra credit: Learn the keyboard shortcut for creating a new tab.

A: `ctrl + alt + t`

---

## 1.2: Our first command

### Exercise: 1

Q: Write a command that prints out the string “hello, world”. Extra credit: As in Listing 1, do it two different ways, both with and without using quotation marks.

A: `echo "hello, world"` , `echo hello, world`

### Exercise 2

Q: Type the command echo ’hello (with a mismatched single quote), and then get out of trouble using the technique from Box 4.

A: `echo 'hello`, `ctrl-c`

---

## 1.3: Man pages

### Exercise 1 

Q: According to the man page, what is the official description of echo on your system? 

A: display a line of text

### Exercise 2

Q: By reading the man page for echo, determine the command needed to print out “hello” without the trailing newline, and verify using your terminal that it works as expected.

A: `echo -n [text]`

---
## 1.4: Editing the line

### Exercise 1

Q: Using the up arrow, print to the screen the strings “fee”, “fie”, “foe”, and “fum” without retyping echo each time.

A: `echo "fee"`, press `up-arrow`, replace "fee" with "fie", etc

### Exercise 2

Q: Starting with the line in Listing 4, use any combination of Ctrl-A, Ctrl-E, arrow keys, or Option-click to change the occurrences of the short s to the archaic long s “ſ” in order to match the appearance of the original (Figure 10).

A: use `ctrl-A`, `ctrl-E`, or arrow keys to navigate and edit

---
## 1.5: Cleaning up

### Exercise 1

Q: Clear the contents of the current tab.

A: type `clear` or press `ctrl-l`

### Exercise 2

Q: Open a new tab, execute echo ’hello’, and then exit.

A: press `ctrl + alt + t`, type `echo 'hello'`, type `exit` or `ctrl-d`

---
## 1.6: Summary

### Exercise 1

Q: Write a command to print the string Use "man echo", including the quotes; i.e., take care not to print out Use man echo instead.

A: type `echo 'Use "man echo"'`

### Exercise 2

Q: By running man sleep, figure out how to make the terminal “sleep” for 5 seconds, and execute the command to do so. After waiting the requisite 5 seconds, execute the command to sleep for 5000 seconds, realize that’s well over an hour, and then use the instructions from Box 4 to get out of trouble. 

A: type `sleep 5s` , type `sleep 5000s` , press `ctrl-c` or `Esc`

---
# 2: Manipulating files

## 2.1: Redirecting and appending

### Exercise 1

Q: Using echo and >, make files called line_1.txt and line_2.txt containing the first and second lines of Sonnet 1, respectively. 

A: `echo "From fairest creatures we desire increase," > line_1.txt` , `echo "That thereby beauty's rose might never die," > line_2.txt`

### Exercise 2

Q: Replicate the original sonnet_1.txt (containing the first two lines of the sonnet) by first redirecting the contents of line_1.txt and then appending the contents of line_2.txt. Call the new file sonnet_1_copy.txt, and confirm using diff that it’s identical to sonnet_1.txt.

A: `echo "From fairest creatures we desire increase," > sonnet_1_copy.txt` , `echo "That thereby beauty's rose might never die," >> sonnet_1_copy.txt` , `diff sonnet_1.txt sonnet_1_copy.txt`

### Exercise 3

Q: Use cat to combine the contents of line_1.txt and line_2.txt in reverse order using a single command, yielding the file sonnet_1_reversed.txt.

A: `cat line_2.txt line_1.txt > sonnet_1_reversed.txt`

---
## 2.2: Listing

### Exercise 1

Q: What’s the command to list all the files (and directories) that start with the letter “s”? 

A: `ls s*`

### Exercise 2

Q: What is the command to list all the files that contain the string “onnet”, long-form by reverse modification time?

A: `ls -rtl *onnet*`

### Exercise 3

Q: What is the command to list all files (including hidden ones) by reverse modification time, in long form?

A: `ls -artl`

---
## 2.3: Renaming, copying, deleting

### Exercise 1

Q: Use the echo command and the redirect operator > to make a file called foo.txt containing the text “hello, world”. Then, using the cp command, make a copy of foo.txt called bar.txt. Using the diff command, confirm that the contents of both files are the same.

A: `echo "hello, world" > foo.txt` , `cp foo.txt bar.txt` , `diff foo.txt bar.txt`

### Exercise 2

Q: By combining the cat command and the redirect operator >, create a copy of foo.txt called baz.txt without using the cp command.

A: `cat foo.txt > baz.txt`

### Exercise 3

Q: Create a file called quux.txt containing the contents of foo.txt followed by the contents of bar.txt.

A: `cat foo.txt bar.txt > quux.txt`

### Exercise 4

Q: How do rm nonexistent and rm -f nonexistent differ for a nonexistent file?

A: `rm` nonexistant asks for confirmation, `rm -f` nonexistant does not ask for comfirmation

---
## 2.4: Summary

### Exercise 1

Q: By copying and pasting the text from the HTML version of Figure 15, use echo to make a file called sonnet_1_complete.txt containing the full (original) text of Shakespeare’s first sonnet.

A: `echo "FRom faireſt creatures we deſire increaſe, That thereby beauties Roſe might neuer die, But as the riper ſhould by time deceaſe, His tender heire might beare his memory: But thou contracted to thine owne bright eyes, Feed’ſt thy lights flame with ſelfe ſubſtantiall fewell, Making a famine where aboundance lies, Thy ſelfe thy foe,to thy ſweet ſelfe too cruell: Thou that art now the worlds freſh ornament, And only herauld to the gaudy ſpring, Within thine owne bud burieſt thy content, And tender chorle makſt waſt in niggarding:    Pitty the world,or elſe this glutton be,    To eate the worlds due,by the graue and thee." > sonnet_1_complete.txt` , `cat sonnet_1_complete.txt`

### Exercise 2

Q: Type the sequence of commands needed to create an empty file called foo, rename it to bar, and copy it to baz. 

A: `touch foo`, `mv foo bar`, `cp bar baz`

### Exercise 3

Q: What is the command to list only the files starting with the letter “b”?

A: `ls b*`

### Exercise 4

Q: Remove both bar and baz using a single call to rm.

A: `rm ba*`

---
# 3: Inspecting files

## 3.1: Downloading a file

### Exercise 1

Q: Use the command curl -I www.learnenough.com to fetch the HTTP header for the Learn Enough website. What is the HTTP status code of the address? How does this differ from the status code of learnenough.com? 

A: 200 ok , status code of learnenough.com is 301 Moved Permanently

### Exercise 2

Q: Using ls, confirm that sonnets.txt exists on your system. How big is it in bytes?

A: `ls -l sonnets.txt` , 96635 bytes

### Exercise 3

Q: Using the -h (“human-readable”) option to ls, list the long form of the sonnets file with a human-readable byte count. 

A:`ls -lh sonnets.txt`

### Exercise 4

Q: Suppose you wanted to list the files and directories using human-readable byte counts, all, by reverse time-sorted long-form. Why might this command be the personal favorite of the author of this tutorial?

A: `ls -hartl` , hartl the author's last name

---
## 3.2: Making heads and tails of it

### Exercise 1

Q: By piping the results of tail sonnets.txt through wc, confirm that (like head) the tail command outputs 10 lines by default. 

A: `tail sonnets.txt | wc`

### Exercise 2

Q: By experimenting with different values of n, find a head command to print out just enough lines to display the first sonnet in its entirety

A: `head -n 18 sonnets.txt`

### Exercise 3

Q: Pipe the results of the previous exercise through tail (with the appropriate options) to print out only the 14 lines composing Sonnet 1.

A: `head -n 18 sonnets.txt | tail -n 14`

### Exercise 4

Q: To simulate the creation of a log file, run ping learnenough.com > learnenough.log in one terminal tab. (The ping command “pings” a server to see if it’s working.) In a second tab, type the command to tail the log file. (At this point, both tabs will be stuck, so once you’ve gotten the gist of tail -f you should use the technique from Box 4 to get out of trouble.)

A: `ping learnenough.com > learnenough.log` , `tail -f learnenough.log` , `ctrl-c`

---
## 3.3: Less is more

### Exercise 1

Q: Run less on sonnets.txt. Go down three pages and then back up three pages. Go to the end of the file, then to the beginning, then quit. 

A: press `spacebar` x3, press `ctrl-b` x3, `G`(capital g), `1G` , `q`

### Exercise 2

Q: Search for the string “All” (case-sensitive). Go forward a few occurrences, then back a few occurrences. Then go to the beginning of the file and count the occurrences by searching forward until you hit the end. Compare your count to the result of running grep All sonnets.txt | wc.

A: `/All`, press `n`, press `N`, 10 "Alls", type`grep All sonnets.txt | wc`

### Exercise 3

Q: Using less and / (“slash”), find the sonnet that begins with the line “Let me not”. Are there any other occurrences of this string in the Sonnets?

A: `less sonnets.txt`, `/Let me not`, no

### Exercise 4

Q: By searching for the string “sort” in the man page for ls, discover the option to sort files by size. What is the command to display the long form of files sorted so the largest files appear at the bottom?

A: `ls -Slr`

---
## 3.4: Grepping

### Exercise 1

Q: By searching man grep for “line number”, construct a command to find the line numbers in sonnets.txt where the string “rose” appears. 

A: `grep -n rose sonnets.txt`

### Exercise 2

Q: You should find that the last occurrences of “rose” is (via “roses”) on line 2203. Figure out how to go directly to this line when running less sonnets.txt.

A: `less sonnets.txt`, `2203G`

### Exercise 3

Q: By piping the output of grep to head, print out the first (and only the first) line in sonnets.txt containing “rose”.

A: `grep -n rose sonnets.txt | head -n 1`

### Exercise 4

Q: In Listing 16, we saw two additional lines that case-insensitively matched “rose”. Execute a command confirming that both of the lines contain the string “Rose” (and not, e.g., “rOSe”).

A: `grep Rose sonnets.txt`

### Exercise 5

Q: Write a command confirming that the number of lines matching “Rose” but not matching “rose” is equal to the expected 2.

A: `grep Rose sonnets.txt | grep -v rose | wc`

---
## 3.5: Summary

### Exercise 1

Q: Pipe history to less to examine your command history. What was your 17th command?

A: `history | less` , uname -r

### Exercise 2

Q: By piping the output of history to wc, count how many commands you’ve executed so far. 

A: `history | wc`, 401

### Exercise 3

Q: By piping the output of history to grep, determine the number for the last occurrence of curl. 

A: `history | grep`, 402

### Exercise 4

Q: Use the result from the previous exercise to re-run the last occurrence of curl. 

A: `!402`, `!401`

### Exercise 5

Q: What do the O and L options in Listing 8 mean?

A: `-O` = remote-output = write output to a file named as the remote file, `-L` = location/follows redirects

---
# 4: Directories

## 4.1: Structure

### Exercise 1

Q: Write in words how you might speak the directory ~/foo/bar. 

A: root slash foo slash bar

### Exercise 2

Q: In /Users/bill/sonnets, what is the home directory? What is the username? Which directory is deepest in the hierarchy? 

A: home dir = users, username = bill, deepest directory = sonnets

### Exercise 3

Q: For a user with username bill, how do /Users/bill/sonnets and ~/sonnets differ (if at all)?

A: `~/sonnets` belongs to the superuser/root, `/Users/bill/sonnets` belongs to a user named bill

---
## 4.2: Making directories

### Exercise 1

Q: What is the option for making intermediate directories as required, so that you can create, e.g., ~/foo and ~/foo/bar with a single command?

A: `-p`

### Exercise 2

Q: Use the option from the previous exercise to make the directory foo and, within it, the directory bar (i.e., ~/foo/bar) with a single command.

A: `mkdir -p ~/foo/bar`

### Exercise 3

Q: By piping the output of ls to grep, list everything in the home directory that contains the letter “o”. 

A: `ls -a | grep o`

---
## 4.3: Navigating directories

### Exercise 1

Q: How do the effects of cd and cd ~ differ (or do they)? 

A: they don't differ, they both change the current directory to home directory

### Exercise 2

Q: Change to text_directory, then change to second_directory using the “one directory up” double dot operator ... 

A: `cd text_directory`, `cd ..`

### Exercise 3

Q: From wherever you are, create an empty file called nil in text_directory using whatever method you wish. 

A: `cd text_directory`, `touch nil`

### Exercise 4

Q: Remove nil from the previous exercises using a different path from the one you used before. (In other words, if you used the path ~/text_directory before, use something like ../text_directory or /Users/<username>/text_directory.) 

A: `../nil`

---
## 4.4: Renaming, copying, deleting directories

### Exercise 1

Q: Make a directory foo with a subdirectory bar, then rename the subdirectory to baz. 

A: `mkdir ~/foo/bar`, `mv ~/foo/bar ~/foo/baz`

### Exercise 2

Q: Copy all the files in text_files, with directory, into foo. 

A: `cp -r ../text_files foo`

### Exercise 3

Q: Copy all the files in text_files, without directory, into bar. 

A: `cp -r ../text_files/ bar`

### Exercise 4

Q: Remove foo and everything in it using a single command. 

A: `rm -rf foo`

---
## 4.5: Summary

### Exercise 1

Q: Using a single command-line command, make a directory foo, change into it, create a file bar with content “baz”, print out bar’s contents, and then cd back to your home directory.

A: `mkdir foo && cd foo && touch baz > bar && cd`

### Exercise 2

Q: What happens when you run the previous command again? How many of the commands executed? Why? 

A: no commands are executed because it won't create the same directory again

### Exercise 3

Q: Explain why the command rm -rf / is unbelievably dangerous, and why you should never type it into a terminal window, not even as a joke. 

A: force removes all files on the system

### Exercise 4

Q: How can the previous command be made even more dangerous? Hint: Refer to Box 11. (This command is so dangerous you shouldn’t even think it, much less type it.) 

A: by adding "sudo" to the beginning, anybody can use the command
