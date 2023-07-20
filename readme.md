 Git Tutorial for Beginners - Git & GitHub Fundamentals In Depth

Tech With Tim 
https://youtube.com/@TechWithTim
https://youtu.be/DVRQoVRzMIY 

Prompt 
C:\Users\Matheus>cd Desktop
C:\Users\Matheus\Desktop>mkdir test-repo
C:\Users\Matheus\Desktop>cd test-repo
C:\Users\Matheus\Desktop\test-repo>git init
Initialized empty Git repository in C:/Users/Matheus/Desktop/test-repo/.git/
C:\Users\Matheus\Desktop\test-repo>git commit 
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)

C:\Users\Matheus\Desktop\test-repo>cd ..
C:\Users\Matheus\Desktop>cd test-repo
C:\Users\Matheus\Desktop\test-repo>git add readme.md 
C:\Users\Matheus\Desktop\test-repo>cd ..
C:\Users\Matheus\Desktop>cd Rodrigo
C:\Users\Matheus\Desktop\Rodrigo>cd Git and Github
Visual Studio Code
readme.md
# Hi
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git add readme.md
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   readme.md

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    "../Anota\303\247\303\265es 0.txt"

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.vscode/
        ../AWS/
        ../Academind/
        ../C.V.pdf
        ../Python/
        ../Rodrigo.jpg
        ../Threadjs.txt
        ../Visual Studio Code/
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git commit -m “added readme.md”
[main d6f93a9] added readme.md
 1 file changed, 1 insertion(+)
 create mode 100644 Git and Github/readme.md
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git status
On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    "../Anota\303\247\303\265es 0.txt"

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.vscode/
        ../AWS/
        ../Academind/
        ../C.V.pdf
        ../Python/
        ../Rodrigo.jpg
        ../Threadjs.txt
        ../Visual Studio Code/

no changes added to commit (use "git add" and/or "git commit -a")
Visual Studio Code
readme.md
# Hi

# Hello
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git status
On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    "../Anota\303\247\303\265es 0.txt"
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.vscode/
        ../AWS/
        ../Academind/
        ../C.V.pdf
        ../Python/
        ../Rodrigo.jpg
        ../Threadjs.txt
        ../Visual Studio Code/

no changes added to commit (use "git add" and/or "git commit -a")
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git add . 
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   readme.md

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    "../Anota\303\247\303\265es 0.txt"

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.vscode/
        ../AWS/
        ../Academind/
        ../C.V.pdf
        ../Python/
        ../Rodrigo.jpg
        ../Threadjs.txt
        ../Visual Studio Code/
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git commit -m “made changes”
[main b819375] made changes
 1 file changed, 3 insertions(+), 1 deletion(-)
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git checkout -b new
Switched to a new branch 'new'
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git add .
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git commit -m “first commit on new branch”
[new 676b57d] first commit on new branch
 1 file changed, 2 insertions(+)
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git checkout master
Switched to branch ‘master’ 
Visual Studio Code
test.py
import pygame 
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git add .
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git status
On branch new
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test.py

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    "../Anota\303\247\303\265es 0.txt"

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.vscode/
        ../AWS/
        ../Academind/
        ../C.V.pdf
        ../Python/
        ../Rodrigo.jpg
        ../Threadjs.txt
        ../Visual Studio Code/
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git commit -m “added test.py”
[new 9e5850f] added test.py
 1 file changed, 1 insertion(+)
 create mode 100644 Git and Github/test.py
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git checkout new
Switched to branch ‘new’
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git merge master
Merge made by ‘recursive’ strategy.
 test.py | 1 +
 1 file changed, 1 insertion(+)
 create mode 100664 test.py
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git checkout  master 
Github 
Create new repository 
Git Tutorial for Beginners - Git & GitHub Fundamentals In Depth
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git remote add origin https://github.com/RodrigoMvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth.git
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git checkout master
Already on 'master'
D       "Anota\303\247\303\265es 0.txt"
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git push -u origin master
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 24 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (9/9), 708 bytes | 708.00KiB/s, done.
Total 9 ( delta 0), reused 0 ( delta 0)
To https://github.com/RodrigoMvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth.git
*[new branch]  master -> master
Branch ‘master’ set up to track remote branch ‘master’ from ‘origin’.
Github 
https://github.com/RodrigoMvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth.git
readme.md 
test.py
Hi 
Hello
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git config - -global user.name “Rodrigo”
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git config - -global user.email “rodrigomvsrodrigo@gmail.com”
Visual Studio Code
readme.md
# Hello
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git pull origin master
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing Objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/rodrigomvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth
*branch                            master       -> FETCH HEAD
a44d742..48a71d3          master       -> origin/master
Updating a44d742..48a71d3 
Fast-forward
 readme.md | 4 + - - - -
 1 file changed, 1 insertion(+), 3 deletions(-)
Visual Studio Code
readme.md
# Hi
https://github.com/RodrigoMvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth/tree/main
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git add .
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git commit -m “change”
[master 8d3709b] change
 1 file changed, 1 insertion(+), 3 deletions(-)
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git pull origin master
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing Objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/rodrigomvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth
*branch                            master       -> FETCH HEAD
a44d742..48a71d3          master       -> origin/master
Auto-merging readme.md 
CONFLICT ( content ): Merge conflict in readme.md
Automatic merge, failed, fix conflicts and then commit the result. 	 	
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git add .
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git commit -m “change”
[master a4607e5] change
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git push 
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 24 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 557 bytes | 557.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To https://github.com/rodrigomvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth
fff74bd..04607e5     master -> master
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git checkout new
Switched to branch 'new'
D       "Anota\303\247\303\265es 0.txt"
C:\Users\Matheus\Desktop\Rodrigo\Git and Github>git push origin new
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 24 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 564 bytes | 564.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
Github 
https://github.com/RodrigoMvs123/Git-Tutorial-for-Beginners---Git-GitHub-Fundamentals-In-Depth.git
7 commit             2 branches
Overview
Default branch
master Updated 2 minutes ago by rodrigomvs123
Your branches                                                                 New pull request
new updated 17 minutes ago by rodrigomvs123
Open a pull request
New
Write
Draft pull request 
New #1
Draft 
Conversation        commit 2         Checks 0          Filed changed 1
Changes from all commits
readme.md
# Hi

# Hello
# Hello

# new branch 
Active branches
new updated 17 minutes ago by rodrigomvs123
new ( less than a minute ago )         compare & pull request
readme.md 
test.py
Hi 
Hello











