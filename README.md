# git-cheat-sheet

### to rename the last commit:
git commit --amend -m "New commit message."
<br/>
git push --force

### to merge the last N commits in one branche:
git rebase -i HEAD~N
<br/>
git push --force

### to pick a commit from a branch and apply it to another:
git cherry-pick commitSHHAcode

### to update a branch from it's parent branch (supposedly master) without messing logs:
git fetch
<br/>
git rebase origin/master

### to merge fixup commits in a PR:
git rebase -i HEAD~5 # 5 being the total number of commits
<br/>
than in the interactive window, squash the fixup commits

### to rename a commit in your PR
git rebase -i HEAD~3 # 3 being the number of commits
<br/>
than replace pick with reword for the commits that you want to rename
