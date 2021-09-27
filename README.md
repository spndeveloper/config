# Config

######################
##### SSH CONFIG #####
######################
# Generate new key ssh
ssh-keygen
# Default dir key
~/.ssh/
# Adding ssh
ssh-add ~/.ssh/{name}
# Getting key
cd {dir}
cat {name}
# Create new ssh key github 
setting -> ssh and gpg key
# Checking ssh agent run
eval $(ssh-agent)
# Adding key to workspace
ssh-add {dir}/{name}
# Cloning file
close {url}
# Add remote
remote add {name} {url}
#######################
##### GIT COMMAND #####
#######################
# Initial
git init
# Adding Remote
git remote add {initial} {branch} {url}
# Remote check
git remote -v
# Remote delete
git remote rm {initial}
# Log
git log
git log --all --decorate --oneline --graph
# Add branch & check
git branch {name}
# Creating alias
git alias {initial}="{command}"
# Getting commit
git checkout {5 digit id}
# Change branch
git checkout {branch}
git checkout -b {newbranch}
# Joining branch
git merge
# Check merge
git branch --merged
# Delete branch
git branch -d {branch}
git branch -D {branch} = force delete
# FETCH
checking file update
# PULL
getting file update
