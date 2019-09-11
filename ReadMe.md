# ReadMe.md

This is my git cheat sheet

## Git commands

```bash
git init REPO-NAME
```
- creates a repositrory called REPO-NAME

```bash
git status
```
- shows the status of the repositrory

```bash
git shows
```
- shows the commit history and changes

```bash
git add FILENAME ANOTHERFILENAME
```
- adds the file FILENAME amd ANOTHERFILENAME to the stash

```bash
git commit -m "MESSAGE"
```
- commits the stashed files to the repo, and adds the MESSAEGE that describd what was done

## Other git things

**.gitignore** is a file that tells git files/folder that are not to be a part of the repoditotry 
.(that is - ignored when ading/committing')

```bash
git config --global alias.adog "log --all -decorate --oneline --graph"
```
- creates a git alias for the log all decorarte oneline graph command.
- use this alias by typing "adog"

```bash
git remote add orgin URL
```
- assign the remote "origin" repository to the URL given
- replae URL with the relevent github/etc location

```bash
git push -u origin master
```

- push the commited up to the "origin"