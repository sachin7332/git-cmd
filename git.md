   <git add                     ::::      Add file contents to the index >
   <git am                      ::::      Apply a series of patches from a mailbox >
   <git archive                 ::::      Create an archive of files from a named tree >
   <git bisect                  ::::      Use binary search to find the commit that introduced a bug >
   <git branch                  ::::      List, create, or delete branches >
   <git bundle                  ::::      Move objects and refs by archive >
   <git checkout                ::::      Switch branches or restore working tree files >
   <git cherry-pick             ::::      Apply the changes introduced by some existing commits >
   <git citool                  ::::      Graphical alternative to git-commit >
   <git clean                   ::::      Remove untracked files from the working tree >
   <git clone                   ::::      Clone a repository into a new directory >
   <git commit                  ::::      Record changes to the repository >
   <git describe                ::::      Give an object a human readable name based on an available ref >
   <git diff                    ::::      Show changes between commits, commit and working tree, etc >
   <git fetch                   ::::      Download objects and refs from another repository >
   <git format-patch            ::::      Prepare patches for e-mail submission >
   <git gc                      ::::      Cleanup unnecessary files and optimize the local repository >
   <git gitk                    ::::      The Git repository browser >
   <git grep                    ::::      Print lines matching a pattern >
   <git gui                     ::::      A portable graphical interface to Git >
   <git init                    ::::      Create an empty Git repository or reinitialize an existing one >
   <git log                     ::::      Show commit logs >
   <git maintenance             ::::      Run tasks to optimize Git repository data >
   <git merge                   ::::      Join two or more development histories together >
   <git mv                      ::::      Move or rename a file, a directory, or a symlink >
   <git notes                   ::::      Add or inspect object notes >
   <git pull                    ::::      Fetch from and integrate with another repository or a local branch >
   <git push                    ::::      Update remote refs along with associated objects >
   <git range-diff              ::::      Compare two commit ranges (e.g. two versions of a branch) >
   <git rebase                  ::::      Reapply commits on top of another base tip >
   <git reset                   ::::      Reset current HEAD to the specified state >
   <git restore                 ::::      Restore working tree files >
   <git revert                  ::::      Revert some existing commits >
   <git rm                      ::::      Remove files from the working tree and from the index >
   <git scalar                  ::::      A tool for managing large Git repositories >
   <git shortlog                ::::      Summarize 'git log' output >
   <git show                    ::::      Show various types of objects >
   <sparse-checkout             ::::      Reduce your working tree to a subset of tracked files>
   <git stash                   ::::      Stash the changes in a dirty working directory away >
   <git status                  ::::      Show the working tree status >
   <git submodule               ::::      Initialize, update or inspect submodules >
   <git switch                  ::::      Switch branches>
   <git tag                     ::::      Create, list, delete or verify a tag object signed with GPG >
   <git worktree                ::::      Manage multiple working trees >




1. Initialize Project = git init
2. Add Single File = git add  <file_name>
3. Add ALl File = git add . 
4. commit on add files = git commit -m "message" (-m <Message>)
5. add and commit = git commit -a -m "Your commit message"
6. add and commit short = git commit -am "Your commit message"
7. check status file = git status   && git status -s
8. check log = git log
9. check log with commit name = git log --grep="commit_name"
10. show commit id with commit name = git log --pretty=format:"%H %s"
11. make MAIN branch =  git branch -m main
12. add remote name = git remote add <remote_name> <remote_url>
13. show remote name = git remote
14. show remote version = git remote -v
15. git clone = git clone <remote_url> <repository_name>
16. create branch = git branch <branch_name>
17. swith branch = git checkout <branch_name>
18. create and swith branch = git checkout -b <branch_name>
19. fetch data from remote branch = git pull <remote_name> <branch_name>
19. push data to local to remote branch = git push <remote_name> <branch_name>
20. get data from remote branch and auto merge = git pull <remote_name>  <branch_name>
21. delete remote = git remote remove origin
22. get data from remote branch and no auto merge = git fecth <remote_name>  <branch_name>
22. get data from remote branch and  auto merge command = git merge <remote_name>/<branch_name>
21. delete branch = git branch -d <branch_name>












git stash
git stash save "add stash v2"
git stash --all


git stash list
git stash clear

git stash apply
git stash apply stash@{0}



git add . && git commit -m "add branch" && git pull origin main
git pull origin main

git stash drop

git stash pop



git log --oneline


git push git@github.com-sachin:sachin7332/git-cmd.git --delete features/auth
