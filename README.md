processo:

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout.
git: 'checkout.' is not a git command. See 'git --help'.

The most similar command is
        checkout

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout-
git: 'checkout-' is not a git command. See 'git --help'.

The most similar command is
        checkout

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
error: The following untracked working tree files would be overwrit
        prova.html
Please move or remove them before you switch branches.
Aborting

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git push
Everything up-to-date

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
error: Your local changes to the following files would be overwritt
        prova.html
Please commit your changes or stash them before you switch branches
Aborting

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git commit -m "aggiunto prova"
[main acef42f] aggiunto prova
 1 file changed, 11 insertions(+)
 create mode 100644 prova.html

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
Switched to branch 'test1'
Your branch is up to date with 'origin/test1'.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
error: Your local changes to the following files would be overwritt
        prova.html
Please commit your changes or stash them before you switch branches
Aborting

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
Your branch is up to date with 'origin/test1'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git commit -m "mmoo d prova"
[test1 5818eea] mmoo d prova
 1 file changed, 11 insertions(+)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$


Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)  

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 1 commit.
  (use "git push" to publish your local commits)   

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 1 commit.
  (use "git push" to publish your local commits)   

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git restore index.html

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git restore index.html

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git commit -m "added about css"
[test1 5e3761d] added about css
 1 file changed, 1 insertion(+), 1 deletion(-)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout .
Updated 0 paths from the index

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 2 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git sa
git: 'sa' is not a git command. See 'git --help'.

The most similar commands are
        stage
        stash
        svn
        tag
        var

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git restore git restore --staged index.html
error: pathspec 'git' did not match any file(s) known to git
error: pathspec 'restore' did not match any file(s) known to git

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
M       index.html
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git brach
git: 'brach' is not a git command. See 'git --help'.

The most similar command is
        branch

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git branch
* main
  test
  test1

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout test
M       index.html
Switched to branch 'test'

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test)
$ git push origin --delete test
To https://github.com/Mattia-scarpia/Prima-prova.git
 - [deleted]         test

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test)
$ git branch
  main
* test
  test1

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test)
$ git branch -D
fatal: branch name required

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test)
$ git branch -D test
error: cannot delete branch 'test' used by worktree at 'C:/Users/PC/Desktop/git prova'

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test)
$ git checkout main
M       index.html
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git branch -D test
Deleted branch test (was 417e526).

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git branch
* main
  test1

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git merge test1
error: Your local changes to the following files would be overwritten by merge:
  index.html
Merge with strategy ort failed.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout test1
M       index.html
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 2 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git commit -m "tetstattotutto"
[test1 c9a76b4] tetstattotutto
 1 file changed, 1 insertion(+)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git merge test1
Auto-merging prova.html
CONFLICT (add/add): Merge conflict in prova.html
Automatic merge failed; fix conflicts and then commit the result.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main|MERGING)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main|MERGING)
$ git checkout -
error: Your local changes to the following files would be overwritten by checkout:
        prova.html
Please commit your changes or stash them before you switch branches.
Aborting

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main|MERGING)
$ git commit -m "risolto problemi"
[main 96c2b8e] risolto problemi

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 7 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git merge test1
Already up to date.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git branch
* main
  test1

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git merge test1
Already up to date.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 7 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git push
Enumerating objects: 20, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 8 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (15/15), 1.89 KiB | 322.00 KiB/s, done.
Total 15 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 1 local object.
To https://github.com/Mattia-scarpia/Prima-prova.git
   417e526..96c2b8e  main -> main

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git push origin main
Everything up-to-date

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ Already up to date.Already up to date.git
bash: Already: command not found

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash
Saved working directory and index state WIP on test1: c9a76b4 tetstattotutto

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash list
stash@{0}: WIP on test1: c9a76b4 tetstattotutto

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout -
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash pop
On branch test1
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{0} (dd4ab39144a111db65872d007553e62fe9c6a555)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git status
On branch test1
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash
Saved working directory and index state WIP on test1: c9a76b4 tetstattotutto

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git commit -m "fatto?"
[main f389bff] fatto?
 1 file changed, 1 insertion(+), 1 deletion(-)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 366 bytes | 366.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Mattia-scarpia/Prima-prova.git
   96c2b8e..f389bff  main -> main

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout test1
Switched to branch 'test1'
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash pop
On branch test1
Your branch is ahead of 'origin/test1' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prova.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{0} (de5f553d06943d1f939992c7bdda2693f233dc37)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash list

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash
Saved working directory and index state WIP on test1: c9a76b4 tetstattotutto

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash list
stash@{0}: WIP on test1: c9a76b4 tetstattotutto

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash clear

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git stash list

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (test1)
$ git checkout -
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git branch
* main
  test1

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ ^C

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout prova
error: pathspec 'prova' did not match any file(s) known to git

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git fetch
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 917 bytes | 70.00 KiB/s, done.
From https://github.com/Mattia-scarpia/Prima-prova
 * [new branch]      prov       -> origin/prov

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git branch 
* main
  test1

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout prova
error: pathspec 'prova' did not match any file(s) known to git

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (main)
$ git checkout prov
branch 'prov' set up to track 'origin/prov'.
Switched to a new branch 'prov'

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (prov)
$ git add .

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (prov)
$ git commit -m "mvjveivmejivmeji"
[prov 9e93ff0] mvjveivmejivmeji
 1 file changed, 1 insertion(+), 1 deletion(-)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (prov)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Mattia-scarpia/Prima-prova.git
   cf59847..9e93ff0  prov -> prov

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (prov)
$ git pull origin prov
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 935 bytes | 71.00 KiB/s, done.
From https://github.com/Mattia-scarpia/Prima-prova
 * branch            prov       -> FETCH_HEAD
   9e93ff0..8b7d924  prov       -> origin/prov
Updating 9e93ff0..8b7d924
Fast-forward
 README.md | 2 ++
 1 file changed, 2 insertions(+)

Mattia@DESKTOP-KHHGQ6F MINGW64 ~/Desktop/git prova (prov)
$
