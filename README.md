# GIT Exercise
This project will be used to do different Git basics Learning.

## Bundle 1

### Exercise 1
```bash
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git init
Reinitialized existing Git repository in /Users/gymiriba/Documents/The Gym Guhirwa/Git_Learning/GIT-EXERCISE/.git/
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git branch
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git branch -M main
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git branch
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
gymiriba@Iribas-iMac-2 GIT-EXERCISE % gti add README.md 
zsh: command not found: gti
gymiriba@Iribas-iMac-2 GIT-EXERCISE % gti status
zsh: command not found: gti
gymiriba@Iribas-iMac-2 GIT-EXERCISE % gti status
zsh: command not found: gti
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git commit -m "Initialize my Exercise 1 from bundle 1"
On branch main

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git add .
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git commit -m "Initialize my Exercise 1 from bundle 1"
[main (root-commit) c755ae5] Initialize my Exercise 1 from bundle 1
 Committer: Gym Iriba <gymiriba@Iribas-iMac-2.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 7 insertions(+)
 create mode 100644 README.md
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git remote add origin https://github.com/Guhirwa/Git-Exercises.git
gymiriba@Iribas-iMac-2 GIT-EXERCISE % 
 *  History restored 

gymiriba@Iribas-iMac-2 GIT-EXERCISE % 
 *  History restored 

gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status   
On branch main
nothing to commit, working tree clean
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git branch
* main
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push          
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push --set upstream origin main
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git branch
* main
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push --set upstream origin main
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git remote -v                               
origin  https://github.com/Guhirwa/Git-Exercises.git (fetch)
origin  https://github.com/Guhirwa/Git-Exercises.git (push)
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git remote add origin https://github.com/Guhirwa/Git-Exercises.git
error: remote origin already exists.
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push --set upstream origin main
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status
On branch main
nothing to commit, working tree clean
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git checkout main
Already on 'main'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % gti add .
zsh: command not found: gti
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git add .
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git commit -m "Initialize my Exercise 1 from bundle 1"
On branch main
nothing to commit, working tree clean
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 337 bytes | 337.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Guhirwa/Git-Exercises.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push
Everything up-to-date
gymiriba@Iribas-iMac-2 GIT-EXERCISE % checkout -b dev
zsh: command not found: checkout
gymiriba@Iribas-iMac-2 GIT-EXERCISE % gti checkout -b dev
zsh: command not found: gti
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git checkout -b dev
Switched to a new branch 'dev'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git status
On branch dev
nothing to commit, working tree clean
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Guhirwa/Git-Exercises/pull/new/dev
remote: 
To https://github.com/Guhirwa/Git-Exercises.git
 * [new branch]      dev -> dev
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git checkout -b test
Switched to a new branch 'test'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Guhirwa/Git-Exercises/pull/new/test
remote: 
To https://github.com/Guhirwa/Git-Exercises.git
 * [new branch]      test -> test
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git checkout dev
Switched to branch 'dev'
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git branch -D test
Deleted branch test (was c755ae5).
gymiriba@Iribas-iMac-2 GIT-EXERCISE % git push origin --delete test
To https://github.com/Guhirwa/Git-Exercises.git
 - [deleted]         test
gymiriba@Iribas-iMac-2 GIT-EXERCISE % 