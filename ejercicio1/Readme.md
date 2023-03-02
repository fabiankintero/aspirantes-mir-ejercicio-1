PS C:\Users\fabte\Documents\ejercicios> pwd

Path
----
C:\Users\fabte\Documents\ejercicios


PS C:\Users\fabte\Documents\ejercicios> git init
Initialized empty Git repository in C:/Users/fabte/Documents/ejercicios/.git/
PS C:\Users\fabte\Documents\ejercicios> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicio1/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\fabte\Documents\ejercicios> git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
PS C:\Users\fabte\Documents\ejercicios> git add .
PS C:\Users\fabte\Documents\ejercicios> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ejercicio1/Readme.md

PS C:\Users\fabte\Documents\ejercicios> git commit -m "version inicial"
[master (root-commit) 238fc1a] version inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/Readme.md
PS C:\Users\fabte\Documents\ejercicios> git remote add origin https://github.com/fabiankintero/aspirantes-mir-ejercicio-1.git
PS C:\Users\fabte\Documents\ejercicios> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/fabiankintero/aspirantes-mir-ejercicio-1.git'
PS C:\Users\fabte\Documents\ejercicios> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\fabte\Documents\ejercicios> git commit -m "version inicial"
On branch master
nothing to commit, working tree clean
PS C:\Users\fabte\Documents\ejercicios> git branch -M main
PS C:\Users\fabte\Documents\ejercicios> git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Writing objects: 100% (4/4), 257 bytes | 51.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/fabiankintero/aspirantes-mir-ejercicio-1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\fabte\Documents\ejercicios>
PS C:\Users\fabte\Documents\ejercicios> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ejercicio1/Readme.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\fabte\Documents\ejercicios> git add .
PS C:\Users\fabte\Documents\ejercicios> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   ejercicio1/Readme.md

PS C:\Users\fabte\Documents\ejercicios> git commit -m "Agrega solución primer ejercicio"
[main 51f78ae] Agrega solución primer ejercicio
 1 file changed, 1 insertion(+)
PS C:\Users\fabte\Documents\ejercicios> git commit -m "Agrega solución primer ejercicio"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\fabte\Documents\ejercicios> git branch -M main     
PS C:\Users\fabte\Documents\ejercicios> git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Writing objects: 100% (4/4), 321 bytes | 80.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/fabiankintero/aspirantes-mir-ejercicio-1.git
   238fc1a..51f78ae  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\fabte\Documents\ejercicios> 