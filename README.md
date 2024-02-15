# topmate-gitlinux
Feb14th -20240 Learning git-linux demo-saurabh/sanjay
created new repo in github.com -- repo name:topmate-gitlinux
now, installed git in ubuntu-wsl- mrahul27-wsl user id
created a directory for git projects under  /tmp/git-dir/topmate-gitlinux
git config cmds--then git init
git clone remote repo topmate-gitlinux to local repo under /tmp/git-dir  -- TRy it both via ssh and https method and see .
create 2 files in default main branch --file1 and file2
now , git add .
git status
git commit -m "First commit"
git push --set-upstream origin main
create new branch git checkout -b feature-- you will automatically switch to new branch
create 2 files feature1.txt and feature2.sh   --these files are now in local workspace in local computer -ubuntu-wsl
now , git add . -->after this, files will be moved to staging area
git status
git commit -m "second commit" --after this , files are moved to local repository
git push --set-upstream origin feature  --here origin is remote server  ..feature is to push to feature branch contents to remote repo.
Now , edit the README.md file for tesing pupose from github ie remote repo.Once changes are committed via GUI ,now your remote repo is ahead of local. so, do a git pull from local to keep it upto date.
If you want to merge the changes of feaure branch to main branch , we can still do it via GUI.and delete the feature branch.

15thFeb-2024:
Added new line to check pull request with reviewer approval process



