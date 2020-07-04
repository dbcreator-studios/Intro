# Intro
GitHub Step by Step 

<br />
Git: configurations <br />
$ git config --global user.name "FirstName LastName" <br />
$ git config --giobal user.email "your-email@email-provider.com" <br />
$ git config --global color.ui true <br />
$ git config --list <br />

<br />
Git: starting a repository <br />
$ git init <br />
$ git status <br />

<br />
Git: staging files <br />
$ git add file-name <br />
$ git add file-name <another-file-name> <yet-another-file-name> <br />
$ git add <br />
$ git add --all <br />
$ git add -A <br />
$ git rm --cached <file-name> <br />
$ git reset <file-name> <br />

<br />
Git: committing to a repository <br />
$ git commit -m "Add three files" <br />
$ git reset --soft HEAD <br />
$ git commit --amend -m <enter your message> <br />

<br />
Git: pulling and pushing from and to repositories <br />
$ git remote add origin <link> <br />
$ git push -u origin master <br />
$ git clone <clone> <br />
$ git pull <br />

<br />
Git: branching <br />
$ git branch <br />
$ git branch <branch-name> <br />
$ git checkout <branch-name> <br />
$ git merge <branch-name> <br />
$ git checkout -b <branch-name> <br />
