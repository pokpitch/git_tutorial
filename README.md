Git Introduction!!

Setup Git 
git config --global user.email "nuboat at gmail " 
git config --global user.name "nuboat"

Create Local Repo
git init
Create new README.md
git status
Display show Untracked files:
git add README.md
git status
Display Changed to be commited
git commit -m "Create Project & README.md"

Add Remote Repo
git remote add origin git@github.com:nuboat/gittutorial.git
git remote -v
Display remote url
git push origin master

Clone Repo
git clone git@github.com:nuboat/gittutorial.git gittutorial
