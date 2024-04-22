# Gym-Git-Exercise-Solutions
# exercises-bundle 6 (3)
PS C:\Users\user\git-cafe-exercise> git add --all
PS C:\Users\user\git-cafe-exercise> git commit -m "changing phone number"
[bugfix 99547d8] changing phone number
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\user\git-cafe-exercise> git push
# exercises-bundle 6 (2)
PS C:\Users\user\git-cafe-exercise> git checkout -b bufix
Switched to a new branch 'bufix'
PS C:\Users\user\git-cafe-exercise> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\git-cafe-exercise> git branch -m bufix bugfix             
PS C:\Users\user\git-cafe-exercise> git checkout bugfix
Switched to branch 'bugfix'
PS C:\Users\user\git-cafe-exercise> git add --all
PS C:\Users\user\git-cafe-exercise> git commit -m "renaming index4.html"
[bugfix 8cff904] renaming index4.html
 1 file changed, 203 insertions(+), 203 deletions(-)
 rename index-4.html => Contact.html (97%)
PS C:\Users\user\git-cafe-exercise> git push
fatal: The current branch bugfix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bugfix

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\git-cafe-exercise>  git push --set-upstream origin bugfix
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.49 KiB | 2.49 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.       
remote:
remote: Create a pull request for 'bugfix' on GitHub by visiting:
remote:      https://github.com/nsengaqueen/git-cafe-exercise/pull/new/bugfix
remote:
To https://github.com/nsengaqueen/git-cafe-exercise.git
 * [new branch]      bugfix -> bugfix
branch 'bugfix' set up to track 'origin/bugfix'.
PS C:\Users\user\git-cafe-exercise> 
# exercises-bundle 6 (1)
PS C:\Users\user\git-cafe-exercise> git checkout -b feature 
Switched to a new branch 'feature'
PS C:\Users\user\git-cafe-exercise> history

  Id CommandLine
  -- -----------
   1 try . "c:\Users\user\AppData\Local\Programs\Microsoft VS Code\re... 
   2 git add --all
   3 git commit -m "editing data in index"
   4 git push
   5 git checkout -b feature


PS C:\Users\user\git-cafe-exercise> git add --all
PS C:\Users\user\git-cafe-exercise> git commit -m "adding new menu items"
[feature 5671a7f] adding new menu items
 1 file changed, 11 insertions(+)
 create mode 100644 Menu.html
PS C:\Users\user\git-cafe-exercise> git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\git-cafe-exercise> git push --set-upstream origin feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 430 bytes | 430.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.       
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/nsengaqueen/git-cafe-exercise/pull/new/feature
remote:
To https://github.com/nsengaqueen/git-cafe-exercise.git
 * [new branch]      feature -> feature
branch 'feature' set up to track 'origin/feature'.
PS C:\Users\user\git-cafe-exercise> git push
Everything up-to-date
# exercises-bundle 5 (2)
PS C:\Users\user\git-cafe-exercise> git add --all
PS C:\Users\user\git-cafe-exercise> git commit -m "editing data in index"
[main 6809761] editing data in index
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\user\git-cafe-exercise> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 319 bytes | 319.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.      
To https://github.com/nsengaqueen/git-cafe-exercise.git
   d1d3f9c..6809761  main -> main
PS C:\Users\user\git-cafe-exercise> git checkout -b feature 
Switched to a new branch 'feature'
# exercise-bundle 4 (2)
PS C:\Users\user\TheGymExercises--2a-> git checkout -b ft/footer
Switched to a new branch 'ft/footer'
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding some changes in ft/footer"
[ft/footer 3b94dfe] adding some changes in ft/footer
 1 file changed, 1 insertion(+)
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding more changes "

[ft/footer 8fcb81b] adding more changes
 1 file changed, 1 insertion(+)
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a->  git push --set-upstream origin ft/footer
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 586 bytes | 586.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.      
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:       
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/footer
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.
PS C:\Users\user\TheGymExercises--2a-> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\TheGymExercises--2a-> git checkout -b ft/squashing main
Switched to a new branch 'ft/squashing'
PS C:\Users\user\TheGymExercises--2a-> git merge squash
merge: squash - not something we can merge
PS C:\Users\user\TheGymExercises--2a-> git merge -- squash ft/footer
merge: squash - not something we can merge
PS C:\Users\user\TheGymExercises--2a-> git merge --squash ft/footer
Updating 99fff94..8fcb81b
Fast-forward
Squash commit -- not updating HEAD
 home.html | 2 ++
 1 file changed, 2 insertions(+)
PS C:\Users\user\TheGymExercises--2a-> git  commit -m "footer changes squashing"
[ft/squashing cc9aa02] footer changes squashing
 1 file changed, 2 insertions(+)
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a->   git push --set-upstream origin ft/squashing
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 340 bytes | 340.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.      
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:    
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.
# exercises-bundle 4 (1)
PS C:\Users\user\TheGymExercises--2a-> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\TheGymExercises--2a-> git  remote add https://github.com/nsengaqueen/TheGymExercises-bundle1.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)       
    -t, --track <branch>  branch(es) to track
    -m, --master <branch> master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

PS C:\Users\user\TheGymExercises--2a-> git remote add git-copy https://github.com/nsengaqueen/tTheGym-bundle4Repo.git
PS C:\Users\user\TheGymExercises--2a-> git add --all 
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding data to home"
[main 99fff94] adding data to home
 1 file changed, 11 insertions(+)
 create mode 100644 home.html
PS C:\Users\user\TheGymExercises--2a-> git push remote origin
fatal: 'remote' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\user\TheGymExercises--2a-> git push origin
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 496 bytes | 496.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   372b99b..99fff94  main -> main
PS C:\Users\user\TheGymExercises--2a-> git push git-copy
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 12 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (12/12), 1.79 KiB | 1.79 MiB/s, done.
Total 12 (delta 4), reused 3 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/nsengaqueen/tTheGym-bundle4Repo.git
 * [new branch]      main -> main
# exercises-bundle 3 (2)
PS C:\Users\user\TheGymExercises--2a-> git checkout -b ft/home-page-redesign ft/faq-page
Switched to a new branch 'ft/home-page-redesign'
PS C:\Users\user\TheGymExercises--2a-> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding changes to main "
[main 372b99b] adding changes to main
 1 file changed, 13 insertions(+)
 create mode 100644 faq.html
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 506 bytes | 506.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   3885b21..372b99b  main -> main
PS C:\Users\user\TheGymExercises--2a-> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\user\TheGymExercises--2a-> git rebase main
Auto-merging faq.html
CONFLICT (add/add): Merge conflict in faq.html
error: could not apply 708e3eb... adding data to faq page
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".   
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 708e3eb... adding data to faq page
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "resolving conflict on home-page-redesign"
[detached HEAD 455d8bb] resolving conflict on home-page-redesign
 1 file changed, 2 insertions(+)
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push origin HEAD:<name-of-remote-branch>

PS C:\Users\user\TheGymExercises--2a-> git status
interactive rebase in progress; onto 372b99b
Last commands done (2 commands done):
   pick e7d88c2 adding changes to conact page
   pick 708e3eb adding data to faq page
Next commands to do (2 remaining commands):
   pick da7acf2 Revert "adding new data"
   pick a3fd989 editing changes
  (use "git rebase --edit-todo" to view and edit)
You are currently editing a commit while rebasing branch 'ft/home-page-redesign' on '372b99b'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)   

nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises--2a-> git checkout ft/home-page-redesign
Warning: you are leaving 2 commits behind, not connected to
any of your branches:

  455d8bb resolving conflict on home-page-redesign
  2bff907 adding changes to conact page

If you want to keep them by creating a new branch, this may be a good time 
to do so with:

 git branch <new-branch-name> 455d8bb

Switched to branch 'ft/home-page-redesign'
PS C:\Users\user\TheGymExercises--2a-> git rebase main
fatal: It seems that there is already a rebase-merge directory, and
I wonder if you are in the middle of another rebase.  If that is the       
case, please try
        git rebase (--continue | --abort | --skip)
If that is not the case, please
        rm -fr ".git/rebase-merge"
and run me again.  I am stopping in case you still have something
valuable there.

PS C:\Users\user\TheGymExercises--2a-> rm -fr
Remove-Item : A parameter cannot be found that matches parameter name 
'fr'.
At line:1 char:4
+ rm -fr
+    ~~~
    + CategoryInfo          : InvalidArgument: (:) [Remove-Item], Paramet  
   erBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.PowerShell  
   .Commands.RemoveItemCommand

PS C:\Users\user\TheGymExercises--2a-> git rebase --abort
PS C:\Users\user\TheGymExercises--2a-> git push  
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a-> 
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/home-page-redesign
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/home-page-redesign
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign        
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.
PS C:\Users\user\TheGymExercises--2a->
PS C:\Users\user\TheGymExercises--2a->  git push --set-upstream origin ft/home-page-redesign
Everything up-to-date
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.
# exercises-bundle 3 (1)
PS C:\Users\user\TheGymExercises--2a-> git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding data to team"
[ft/team-page d0acd32] adding data to team
 1 file changed, 11 insertions(+)
 create mode 100644 team.html
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a-> git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 475 bytes | 237.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:    
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/team-page
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.
PS C:\Users\user\TheGymExercises--2a-> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\TheGymExercises--2a-> git checkout -b ft/contact-page
PS C:\Users\user\TheGymExercises--2a-> git log
commit 3885b21ad7b5803907a2aa1745c4234bbf6a37a0 (HEAD -> ft/contact-page, origin/main, origin/HEAD, main)
Author: queen <nsengaqueen123@gmail.com>
Date:   Mon Apr 22 15:22:34 2024 +0200

    adding new data

commit 8f83e04715e8f3af657c0987e9c1993b2ab4c82b
Author: nsengaqueen <99642525+nsengaqueen@users.noreply.github.com>        
Date:   Mon Apr 22 15:17:17 2024 +0200

    Initial commit
PS C:\Users\user\TheGymExercises--2a-> git checkout ft/contact-page        
Already on 'ft/contact-page'
PS C:\Users\user\TheGymExercises--2a-> git cherry-pick
usage: git cherry-pick [--edit] [-n] [-m <parent-number>] [-s] [-x] [--ff]
                       [-S[<keyid>]] <commit>...
   or: git cherry-pick (--continue | --skip | --abort | --quit)

    --quit                end revert or cherry-pick sequence
    --continue            resume revert or cherry-pick sequence
    --abort               cancel revert or cherry-pick sequence
    --skip                skip current commit and continue
    --cleanup <mode>      how to strip spaces and #comments from message   
    -n, --no-commit       don't automatically commit
    -e, --edit            edit the commit message
    -s, --signoff         add a Signed-off-by trailer
    -m, --mainline <parent-number>
                          select mainline parent
    --rerere-autoupdate   update the index with reused conflict resolution if possible
    --strategy <strategy> merge strategy
    -X, --strategy-option <option>
                          option for merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    -x                    append commit name
    --ff                  allow fast-forward
    --allow-empty         preserve initially empty commits
    --allow-empty-message allow commits with empty messages
    --keep-redundant-commits
                          keep redundant, empty commits

PS C:\Users\user\TheGymExercises--2a-> git cherry-pick 3885b21ad7b5803907a2aa1745c4234bbf6a37a0
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'
On branch ft/contact-page
You are currently cherry-picking commit 3885b21.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)      

nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "added contact-page data"
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'
On branch ft/contact-page
You are currently cherry-picking commit 3885b21.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)      

nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a-> git push --set-upstream origin ft/contact-page
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting: 
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/contact-page
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding changes to conact page"
[ft/contact-page e7d88c2] adding changes to conact page
 Date: Mon Apr 22 15:22:34 2024 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 495 bytes | 247.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   3885b21..e7d88c2  ft/contact-page -> ft/contact-page
PS C:\Users\user\TheGymExercises--2a-> git branch
* ft/contact-page
  ft/service-redesign
  ft/team-page
  main
PS C:\Users\user\TheGymExercises--2a-> git checkout -bft/faq-page  ft/contact-page
Switched to a new branch 'ft/faq-page'
PS C:\Users\user\TheGymExercises--2a-> git add -- all
fatal: pathspec 'all' did not match any files
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding data to faq page"
[ft/faq-page 708e3eb] adding data to faq page
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a-> git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads

Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 511 bytes | 255.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/faq-page
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/faq-page
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.
PS C:\Users\user\TheGymExercises--2a-> git revert 3885b21ad7b5803907a2aa1745c4234bbf6a37a0
hint: Waiting for your editor to close the file...

[ft/faq-page da7acf2] Revert "adding new data"
 1 file changed, 12 deletions(-)
 delete mode 100644 services.html
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 276 bytes | 276.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.       
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   708e3eb..da7acf2  ft/faq-page -> ft/faq-page
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "editing changes"
[ft/faq-page a3fd989] editing changes
 1 file changed, 1 insertion(+)
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 375 bytes | 375.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.       
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   da7acf2..a3fd989  ft/faq-page -> ft/faq-page
PS C:\Users\user\TheGymExercises--2a-> git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\user\TheGymExercises--2a-> git revert 3885b21ad7b5803907a2aa1745c4234bbf6a37a0
CONFLICT (modify/delete): services.html deleted in parent of 3885b21 (adding new data) and modified in HEAD.  Version HEAD of services.html left in tree.
error: could not revert 3885b21... adding new data
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
PS C:\Users\user\TheGymExercises--2a-> git revert --abort
PS C:\Users\user\TheGymExercises--2a-> git log
commit d0acd328d1846c5ae1c926505cc262a1569b0c59 (HEAD -> ft/team-page, origin/ft/team-page)
commit d0acd328d1846c5ae1c926505cc262a1569b0c59 (HEAD -> ft/team-page, origin/ft/team-page)
Author: queen <nsengaqueen123@gmail.com>
Date:   Mon Apr 22 15:40:04 2024 +0200

    adding data to team

commit 99d044344e7e37e10f10e496d6cb80556284f37c (origin/ft/service-redesign, ft/service-redesign)
Merge: cf23a94 3885b21
Author: queen <nsengaqueen123@gmail.com>
Date:   Mon Apr 22 15:28:41 2024 +0200

    merging

PS C:\Users\user\TheGymExercises--2a-> 
PS C:\Users\user\TheGymExercises--2a-> git checkout ft/team-page
Already on 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\user\TheGymExercises--2a-> git log
commit d0acd328d1846c5ae1c926505cc262a1569b0c59 (HEAD -> ft/team-page, origin/ft/team-page)
Author: queen <nsengaqueen123@gmail.com>
Revert "adding data to team"
Date:   Mon Apr 22 15:40:04 2024 +0200

    adding data to team

commit 99d044344e7e37e10f10e496d6cb80556284f37c (origin/ft/service-redesign, ft/service-redesign)
Merge: cf23a94 3885b21
Author: queen <nsengaqueen123@gmail.com>
Date:   Mon Apr 22 15:28:41 2024 +0200

    merging

PS C:\Users\user\TheGymExercises--2a->
PS C:\Users\user\TheGymExercises--2a-> git revert d0acd328d1846c5ae1c926505cc262a1569b0c59
[ft/team-page 171d44f] Revert "adding data to team"
 1 file changed, 11 deletions(-)
 delete mode 100644 team.html
PS C:\Users\user\TheGymExercises--2a-> git add --all 
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding data"
On branch ft/team-page
Your branch is ahead of 'origin/ft/team-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   d0acd32..171d44f  ft/team-page -> ft/team-page
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "q"
[ft/team-page 319cd31] q
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html
PS C:\Users\user\TheGymExercises--2a-> git push 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 486 bytes | 243.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   171d44f..319cd31  ft/team-page -> ft/team-page
PS C:\Users\user\TheGymExercises--2a-> 

# exercises-bundle 2 (2)

PS C:\Users\user\TheGymExercises--2a-> git checkout main 
Already on 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\TheGymExercises--2a-> git pull
Already up to date.
PS C:\Users\user\TheGymExercises--2a-> git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding changes"
[ft/service-redesign cf23a94] adding changes
 1 file changed, 11 insertions(+)
 create mode 100644 services.html
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "addinf new changes"
On branch ft/service-redesign
nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises--2a-> git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises--2a-> git push --set-upstream origin ft/service-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 440 bytes | 440.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/nsengaqueen/TheGymExercises--2a-/pull/new/ft/service-redesign
remote:
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.
PS C:\Users\user\TheGymExercises--2a-> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\TheGymExercises--2a-> git add .
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m "adding new data"
[main 3885b21] adding new data
 1 file changed, 12 insertions(+)
 create mode 100644 services.html
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 448 bytes | 448.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   8f83e04..3885b21  main -> main
PS C:\Users\user\TheGymExercises--2a-> git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.
PS C:\Users\user\TheGymExercises--2a-> git diff
PS C:\Users\user\TheGymExercises--2a-> git diff
PS C:\Users\user\TheGymExercises--2a-> git merge main 
Auto-merging services.html
CONFLICT (add/add): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\user\TheGymExercises--2a-> git add -all 
error: did you mean `--all` (with two dashes)?
PS C:\Users\user\TheGymExercises--2a-> git commit -m "resolving the conflicts"
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
U       services.html
PS C:\Users\user\TheGymExercises--2a-> git add --all
PS C:\Users\user\TheGymExercises--2a-> git commit -m ""
error: switch `m' requires a value
PS C:\Users\user\TheGymExercises--2a-> git commit -m "merging"
[ft/service-redesign 99d0443] merging
PS C:\Users\user\TheGymExercises--2a-> git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nsengaqueen/TheGymExercises--2a-.git
   cf23a94..99d0443  ft/service-redesign -> ft/service-redesign
PS C:\Users\user\TheGymExercises--2a-> 
# exercises-bundle 1 (1)

PS C:\Users\user\TheGymExercises-bundle1> git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\user\TheGymExercises-bundle1> git add -all
error: did you mean `--all` (with two dashes)?
PS C:\Users\user\TheGymExercises-bundle1> git add  --all
PS C:\Users\user\TheGymExercises-bundle1> git commit -m "committed the chages made "
[main (root-commit) 04f5cd7] committed the chages made
 1 file changed, 11 insertions(+)
 create mode 100644 index.html
PS C:\Users\user\TheGymExercises-bundle1> git remote add origin https://github.com/nsengaqueen/TheGymExercises-bundle1.git
PS C:\Users\user\TheGymExercises-bundle1> git push 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\user\TheGymExercises-bundle1> git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 380 bytes | 380.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises-bundle1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\user\TheGymExercises-bundle1> git branch dev
PS C:\Users\user\TheGymExercises-bundle1> git branch
  dev
* main
PS C:\Users\user\TheGymExercises-bundle1> git checkout dev
Switched to branch 'dev'
PS C:\Users\user\TheGymExercises-bundle1> git branch test
PS C:\Users\user\TheGymExercises-bundle1> git checkout dev
Already on 'dev'
PS C:\Users\user\TheGymExercises-bundle1> git branch -d test
Deleted branch test (was 04f5cd7).

# exercises-bundle 1 (2) 


PS C:\Users\user\TheGymExercises-bundle1> git push origin dev
Everything up-to-date
PS C:\Users\user\TheGymExercises-bundle1> git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\user\TheGymExercises-bundle1> git stash
No local changes to save
PS C:\Users\user\TheGymExercises-bundle1> git status 
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\user\TheGymExercises-bundle1> git stash
No local changes to save
PS C:\Users\user\TheGymExercises-bundle1> git add .
PS C:\Users\user\TheGymExercises-bundle1> git stash
Saved working directory and index state WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises-bundle1> git add .
PS C:\Users\user\TheGymExercises-bundle1> git stash
Saved working directory and index state WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git add .
PS C:\Users\user\TheGymExercises-bundle1> git stash
Saved working directory and index state WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git add .
PS C:\Users\user\TheGymExercises-bundle1> git stash
Saved working directory and index state WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git stash list
stash@{0}: WIP on dev: 04f5cd7 committed the chages made
stash@{1}: WIP on dev: 04f5cd7 committed the chages made
stash@{2}: WIP on dev: 04f5cd7 committed the chages made
stash@{3}: WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git stash pop
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (f158cf40aa8b6bc30edcfa94161f6c716375ef74)
PS C:\Users\user\TheGymExercises-bundle1> git stash apply
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

PS C:\Users\user\TheGymExercises-bundle1> git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

PS C:\Users\user\TheGymExercises-bundle1> git  stash list
stash@{0}: WIP on dev: 04f5cd7 committed the chages made
stash@{1}: WIP on dev: 04f5cd7 committed the chages made
stash@{2}: WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git stash pop 0
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Dropped refs/stash@{0} (5627a90e847b6cbdb3a97b1eedc5af7cf34aa386)
PS C:\Users\user\TheGymExercises-bundle1> git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

PS C:\Users\user\TheGymExercises-bundle1> git commit -m "commiting the data in stash"
[dev 6b0f642] commiting the data in stash
 2 files changed, 22 insertions(+)
 create mode 100644 about.html
 create mode 100644 team.html
PS C:\Users\user\TheGymExercises-bundle1> git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 529 bytes | 529.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/nsengaqueen/TheGymExercises-bundle1.git
   04f5cd7..6b0f642  dev -> dev
PS C:\Users\user\TheGymExercises-bundle1> git stash list
stash@{0}: WIP on dev: 04f5cd7 committed the chages made
stash@{1}: WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git stash pop 1
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html

Dropped refs/stash@{1} (13bc145ea196a62751f1dc538d9a345a686991eb)
PS C:\Users\user\TheGymExercises-bundle1> git reset
PS C:\Users\user\TheGymExercises-bundle1> git stash list
stash@{0}: WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git reset -hard
error: did you mean `--hard` (with two dashes)?
PS C:\Users\user\TheGymExercises-bundle1> git reset --hard 
HEAD is now at 6b0f642 commiting the data in stash
PS C:\Users\user\TheGymExercises-bundle1> git stash list
stash@{0}: WIP on dev: 04f5cd7 committed the chages made
PS C:\Users\user\TheGymExercises-bundle1> git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\user\TheGymExercises-bundle1> git add .
PS C:\Users\user\TheGymExercises-bundle1> git commit -m "setting up home"  
[dev 4825e64] setting up home
 1 file changed, 12 insertions(+)
 create mode 100644 home.html
PS C:\Users\user\TheGymExercises-bundle1> git push 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 509 bytes | 509.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nsengaqueen/TheGymExercises-bundle1.git
   6b0f642..4825e64  dev -> dev
PS C:\Users\user\TheGymExercises-bundle1> git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\user\TheGymExercises-bundle1>


 














