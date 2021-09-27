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
