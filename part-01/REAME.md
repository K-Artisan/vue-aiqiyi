PS F:\Kzone\CodeLib\vue\aiqiyi> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   part-01/todolist.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        part-01/REAME.md

no changes added to commit (use "git add" and/or "git commit -a")
PS F:\Kzone\CodeLib\vue\aiqiyi> git add .
PS F:\Kzone\CodeLib\vue\aiqiyi> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   part-01/REAME.md
        modified:   part-01/todolist.html

PS F:\Kzone\CodeLib\vue\aiqiyi> git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS F:\Kzone\CodeLib\vue\aiqiyi> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   part-01/REAME.md
        modified:   part-01/todolist.html

PS F:\Kzone\CodeLib\vue\aiqiyi> git commit -m
error: switch `m' requires a value
PS F:\Kzone\CodeLib\vue\aiqiyi> git commit -m redme
[master 601fa47] redme
 2 files changed, 1 insertion(+), 1 deletion(-)
 create mode 100644 part-01/REAME.md
PS F:\Kzone\CodeLib\vue\aiqiyi> git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS F:\Kzone\CodeLib\vue\aiqiyi> git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 369 bytes | 184.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/K-Artisan/vue-aiqiyi.git
   8f311c7..601fa47  master -> master
PS F:\Kzone\CodeLib\vue\aiqiyi> git push
Everything up-to-date
PS F:\Kzone\CodeLib\vue\aiqiyi> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS F:\Kzone\CodeLib\vue\aiqiyi>
