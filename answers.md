HW 1 Project tr288619@ohio.edu: 

Answer 1: 
git version 2.39.2 (Apple Git-143)

Answer 2: 
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % git config --list
credential.helper=osxkeychain
init.defaultbranch=main
user.name=Taylor Reigle
user.email=tr288619@ohio.edu
credential.helper=cahce
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
remote.origin.url=https://github.com/tr288619/git-lab.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % 

Answer 3:
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % git add --help


       Everything below this line in this section is selectively included from
       the git-config(1) documentation. The content is the same as what’s
       found there:

       add.ignoreErrors, add.ignore-errors (deprecated)
           Tells git add to continue adding files when some files cannot be
           added due to indexing errors. Equivalent to the --ignore-errors
           option of git-add(1).  add.ignore-errors is deprecated, as it does
           not follow the usual naming convention for configuration variables.

       add.interactive.useBuiltin
           Set to false to fall back to the original Perl implementation of
           the interactive version of git-add(1) instead of the built-in
           version. Is true by default.

SEE ALSO
       git-status(1) git-rm(1) git-reset(1) git-mv(1) git-commit(1) git-
       update-index(1)

GIT
       Part of the git(1) suite

Git 2.39.0                        12/12/2022                        GIT-ADD(1)
(END)

Answer 4:
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	git-lab/

nothing added to commit but untracked files present (use "git add" to track)
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % 

Answer 5:
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md

(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % 

Answer 6: 
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md

(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % 

Answer 7: 
(base) taylorreigle@Taylors-Air-4 git-lab % git commit -m "Initial commit"
[main (root-commit) 8739e2f] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
(base) taylorreigle@Taylors-Air-4 git-lab % 

Answer 8: 
(base) taylorreigle@Taylors-Air-4 git-lab % git log
commit 8739e2f978c0c1eec9dcba4fa10f7e964ad5f4fe (HEAD -> main)
Author: Taylor Reigle <tr288619@ohio.edu>
Date:   Wed May 17 19:26:49 2023 -0400

    Initial commit
(base) taylorreigle@Taylors-Air-4 git-lab % 

Answer 9:
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(base) taylorreigle@Taylors-MacBook-Air-4 git-lab % 

Answer 10: 
(base) taylorreigle@Taylors-Air-4 git-lab % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(base) taylorreigle@Taylors-Air-4 git-lab % 

Answer 11: 
(base) taylorreigle@Taylors-Air-4 git-lab % git push
To https://github.com/tr288619/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/tr288619/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
(base) taylorreigle@Taylors-Air-4 git-lab % 

Answer 12:
(base) taylorreigle@Taylors-Air-4 git-lab % git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 680 bytes | 226.00 KiB/s, done.
From https://github.com/tr288619/git-lab
   8739e2f..63ae68d  main       -> origin/main
Updating 8739e2f..63ae68d
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)
(base) taylorreigle@Taylors-Air-4 git-lab % 

Answer 13:
(base) taylorreigle@Taylors-Air-4 git-lab % ls -a
.		.git		answers.md
..		README.md	git-lab-2
(base) taylorreigle@Taylors-Air-4 git-lab % 

