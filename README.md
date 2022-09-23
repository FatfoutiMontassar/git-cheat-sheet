# git-cheat-sheet

# to rename the last commit:
git commit --amend -m "New commit message."
git push --force

# to merge the last N commits in one branche:
git rebase -i HEAD~N
git push --force
