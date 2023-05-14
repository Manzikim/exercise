NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1
$ git init
Initialized empty Git repository in C:/Users/NIC/Desktop/the gym/git/bundle1/.git/

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (master)
$ rename repository main
bash: rename: command not found

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (master)
$ git branch main
fatal: not a valid object name: 'master'

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (master)
$ git branch -m main

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ touch bundle1

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ vim bundle1

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ mv bundle1 bundel2.0

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ ls
bundel2.0

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ less
Missing filename ("less --help" for help)

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ less bundle2.0
bundle2.0: No such file or directory

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ less bundel2.0

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git add .
warning: in the working copy of 'bundel2.0', LF will be replaced by CRLF the next time Git touches it

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git commit -m "bundle2.0 is about to be committed"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'NIC@DESKTOP-J0Q1ROH.(none)')

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git remote add orgin https://github.com/Manzikim/giti.git

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git push --set-upstream orgin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Manzikim/giti.git'

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git remote add orgin https://github.com/Manzikim/giti.git
error: remote orgin already exists.

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git push --set-upstream orgin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Manzikim/giti.git'

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git init
Reinitialized existing Git repository in C:/Users/NIC/Desktop/the gym/git/bundle1/.git/

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ touch README.md

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   bundel2.0

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md


NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git add .

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   bundel2.0


NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git commit -m "exe1"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'NIC@DESKTOP-J0Q1ROH.(none)')

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$   git config --global user.email "manzidakimo@gmail.com^C

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git config --global user.email "manzidakimo@gmail.com"

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git config --global user.name "Manzikim"

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git commit -m "exe1"
[main (root-commit) a151119] exe1
 2 files changed, 1 insertion(+)
 create mode 100644 README.md
 create mode 100644 bundel2.0

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git remote add orgin https://github.com/Manzikim/giti.git
error: remote orgin already exists.

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git push --set-upstream orgin main
fatal: helper error (-1): User cancelled dialog.


NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git push --set-upstream origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git remote add orgin https://github.com/Manzikim/exercise.git
error: remote orgin already exists.

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git remote add origin https://github.com/Manzikim/exercise.git

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
$ git push --set-upstream origin main
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 266 bytes | 266.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Manzikim/exercise.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

NIC@DESKTOP-J0Q1ROH MINGW64 ~/Desktop/the gym/git/bundle1 (main)
