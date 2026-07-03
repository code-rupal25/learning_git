## RUN IN CMD PROMPT

### In Terminal to change folder 
cd /path/to/folder

or you can create folder from the file system and open in visual studio code

### Check whether the existing folder is Git Repository or not
git status

~ if output : datal : not a git repository 

### In case it does not show branch cloning a repo locally 
git clone https://github.com/code-rupal25/learning_git/repo.git

#### move to repo
cd repo

#### list branches
git branch -a

#### switch to required branch
git checkout dev or prod   OR git switch branch

#### Pull Latest Changes
git pull origin branch

### IF BRANCH Exists Already

git branch --show-current

#### check if pointing to remote branch
git branch -vv

git fetch --all

git push (to push changes in branch)




