# LearnGit

> List of all common git commands

```git
git status
```
Status of all files in the current repo.

```git
git add <filename.ext>
```
Add all changes to commit list.
you can also use * to use all changed files

```git
git commit -m "Changes"
```
Should open a file editor window with the commit information if param m is not present. Else it will use the message in the param m.

```git
git push origin main
```
Send all commited files to the repo.

```git
git pull
```
Update your local files of the repo the the latest version

```git
git fetch
```
Get all repo related infos without getting files (ex, branches)

```git
git checkout
```
Switch branches

```git
git push --set-upstream origin bigfix/texturefix
```
Push to new branch
