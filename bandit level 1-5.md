## Challenge: Bandit Level 0 → Level 1

**Commands Used:**
```bash
bandit0@bandit:~$ ls -la
total 24
drwxr-xr-x   2 root    root    4096 Oct 14 09:25 .
drwxr-xr-x 150 root    root    4096 Oct 14 09:29 ..
-rw-r--r--   1 root    root     220 Mar 31  2024 .bash_logout
-rw-r--r--   1 root    root    3851 Oct 14 09:19 .bashrc
-rw-r--r--   1 root    root     807 Mar 31  2024 .profile
-rw-r-----   1 bandit1 bandit0  438 Oct 14 09:25 readme
bandit0@bandit:~$ ls README.md
ls: cannot access 'README.md': No such file or directory
bandit0@bandit:~$ README
README: command not found
bandit0@bandit:~$ ls README
ls: cannot access 'README': No such file or directory
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```
**passord for next level:**
```bash
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

## Challenge: Bandit Level 1 → Level 2

**Commands Used:**
```bash
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```
**passord for next level:**
```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

## Challenge: Bandit Level 2 → Level 3

**Commands Used:**
```bash
bandit2@bandit:~$ ls
--spaces in this filename--
bandit2@bandit:~$ cat --spaces in this filename--
cat: unrecognized option '--spaces'
Try 'cat --help' for more information.
bandit2@bandit:~$ cat "spaces in this filename"
cat: 'spaces in this filename': No such file or directory
bandit2@bandit:~$ ls -la
total 24
drwxr-xr-x   2 root    root    4096 Oct 14 09:26 .
drwxr-xr-x 150 root    root    4096 Oct 14 09:29 ..
-rw-r--r--   1 root    root     220 Mar 31  2024 .bash_logout
-rw-r--r--   1 root    root    3851 Oct 14 09:19 .bashrc
-rw-r--r--   1 root    root     807 Mar 31  2024 .profile
-rw-r-----   1 bandit3 bandit2   33 Oct 14 09:26 --spaces in this filename--
bandit2@bandit:~$ cat spaces
cat: spaces: No such file or directory
bandit2@bandit:~$ cat spaces\ in\ this\ filename
cat: 'spaces in this filename': No such file or directory
bandit2@bandit:~$ cat -- "--spaces in this filename--"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```
**passord for next level:**
```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

## Challenge: Bandit Level 3 → Level 4

**Commands Used:**
```bash
bandit3@bandit:~$ ls
inhere
bandit3@bandit:~$ cd inhere
bandit3@bandit:~/inhere$ cat




.
.
.
.
ls -la
ls -la
^C
bandit3@bandit:~/inhere$ ls -la
total 12
drwxr-xr-x 2 root    root    4096 Oct 14 09:26 .
drwxr-xr-x 3 root    root    4096 Oct 14 09:26 ..
-rw-r----- 1 bandit4 bandit3   33 Oct 14 09:26 ...Hiding-From-You
bandit3@bandit:~/inhere$ cat ...Hiding-From-You
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```
**passord for next level:**
```bash
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

## Challenge: Bandit Level 4 → Level 5

**Commands Used:**
```bash
bandit4@bandit:~$ ls
inhere
bandit4@bandit:~$ cat inhere
cat: inhere: Is a directory
bandit4@bandit:~$ cd inhere
bandit4@bandit:~/inhere$ cat
^C
bandit4@bandit:~/inhere$ ls -la
total 48
drwxr-xr-x 2 root    root    4096 Oct 14 09:26 .
drwxr-xr-x 3 root    root    4096 Oct 14 09:26 ..
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file00
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file01
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file02
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file03
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file04
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file05
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file06
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file07
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file08
-rw-r----- 1 bandit5 bandit4   33 Oct 14 09:26 -file09
bandit4@bandit:~/inhere$ cd ~
bandit4@bandit:~$ ls -la
total 24
drwxr-xr-x   3 root root 4096 Oct 14 09:26 .
drwxr-xr-x 150 root root 4096 Oct 14 09:29 ..
-rw-r--r--   1 root root  220 Mar 31  2024 .bash_logout
-rw-r--r--   1 root root 3851 Oct 14 09:19 .bashrc
drwxr-xr-x   2 root root 4096 Oct 14 09:26 inhere
-rw-r--r--   1 root root  807 Mar 31  2024 .profile
bandit4@bandit:~$ cd ~/inhere
bandit4@bandit:~/inhere$ file ./*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@bandit:~/inhere$ cat ./-file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
**passord for next level:**
```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
