# school
Do not use. I don't have a paid account to make private. 
## Setup
In terminal...
```
cd ~
git config --global user.name "anderson.noah2@gmail.com"
git config --global user.email "anderson.noah2@gmail.com"
git clone https://github.com/andersonnoah/school.git
```

## Push changes
After creating or editing files...
```
git add *
```
or
```
git add name_of_file_you_want_wildcards_allowed
```
Then...
```
git commit -m "Write commit message here. Quotes necessary."
git push -u origin master
```
(Obviously change "master" to name of different branch if working on other branch.)

## Useful commands
```
git status        // see if unstaged changes exist
git pull          // get latest changes
git stash save --keep-index --include-untracked // discard local changes (save them for later)
```
