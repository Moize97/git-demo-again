# git-demo-again
GitHub Steps:

1) create a repo on GitHub account
2) created a same name folder in local in your pc.
3) create any file in that folder for versions.
	- eg: eco "# git-demo-again" >> README.md
4) initialize git in your local folder.
	- eg: git init
5) to check the status (untracked - 'red' / track file - 'green') of your GitHub repo.
	eg: 'git status'
6) to move file from untracked to track .
	 'git add README.md' (add only specific file to tracking)
	 'git add .' or 'git add -A' ( add all the file into Tracking
	 'git add *.csv' (add only specific files)
 	-let suppose you want to move file from tacking to untracking again. (ticket wapis krdo)
		eg: 'git rm --cashed <file>'
7) to make file ready to push we do commit (send to airport)
	eg: git commit -m "any meaninfull comment"
8) to rename the bracnh from 'master' to 'main'
	eg: 'git branch -M main'
9) to set the origin for your local repo for gihub repo (travelling destination setting)
	eg: git remote add origin 'https://github.com/Moize97/git-demo-againt.git'
10) to push file from local to github repo. (in flight from Khi to Islamabad)
	eg: 'git push -u origin main'





## Second time when we work on it.:
- 'git add .'
- 'git commit -m "Any Message"'
- 'git push'

## Branching:

1) To check on which branch you are 
	eg: git branch
2) To move & create new branch 
	eg: git checkout -b task/development-branch 
	if branch already exist: 
		eg: 'git checkout <Bracnh-name>'
3) git add .
4) git commit -m "Branch commit"
5) git push -u origin task/development-branch