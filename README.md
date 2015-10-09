#3.2
---
1. tail sonnets.txt | wc
2. head -n 18 sonnets.txt
3. head -n 18 sonnets.txt | tail -n 14
4. ping learnenough.com > learnenough.log , tail -f learnenough.log

---
#3.3
---
1. spacebar x3, ctrl-b x3, G(capital g), 1G
2. /All, n, N, 10 "Alls"
3. less sonnets.txt, /Let me not, no
4. ls -Cl

---
#3.4
---
1. grep -n rose sonnets.txt
2. less sonnets.txt, 2203G
3. grep -n rose sonnets.txt | head -n 909 (?)
4. grep Rose sonnets.txt
5. grep Rose sonnets.txt | grep -v rose | wc

---
#3.5
---
1. uname -r
2. 401
3. 402
4. !402, !401
5. -O=remote-output=write output to a file named as the remote file, -L=location/follows redirects

---
#4.1
---
1. root slash foo slash bar
2. home dir = users, username = bill, deepest directory = sonnets
3. ~/sonnets belongs to the superuser

---
#4.2
---
1. mkdir -p <name>
2. mkdir -p ~/foo/bar
3. ls | grep o

---
#4.3
---
1. they don't differ, they both change the current directory to home directory
2. cd text_directory, cd ..
3. cd text_directory, touch nil
4. ../nil

---
#4.4
---
1.mkdir ~/foo/bar, mv ~/foo/bar ~/foo/baz
2. cp -r ../text_files foo
3. cp -r ../text_files/ bar
4. rm -rf foo

---
#4.5
---
1.mkdir foo && cd foo && touch baz > bar && cd
2. no commands are executed because it won't create the same directory again
3. force removes all files on the system
4. by adding "sudo" to the beginning, anybody can use the command
