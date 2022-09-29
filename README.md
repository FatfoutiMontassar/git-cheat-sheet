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
