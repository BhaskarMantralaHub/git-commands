# git-commands
git-commands

Git


Current Branch	git branch --show-current
Switch to previous Branch	git checkout -
To remove previous commit	git reset --hard 32b0610010b
git push origin HEAD --force
Revert to old commit	git reset --hard 8ebe2b04624
git push origin hotfix/QAT-3387-update-okta-login-locators --force

**Reverse Merge**
	git reset --hard HEAD~1
Cherry Pick	https://stackoverflow.com/questions/45216144/how-do-i-move-unpushed-committed-code-to-another-branch/45216453

git branch newbranch
git reset --hard HEAD~1


**Fatal error - ref**

git gc --prune=now


**Delete untracked files**	

git clean  -d  -f .

**Stash - Merge with master** 

git pull
git merge origin/master
git stash pop (to restore stashed local changes)


**Add committed file to .gitignore**	

git rm --cached filename

Add file to .gitignore

git rm -r --cached .

git add .

git commit -m ".gitignore is now working"
	
