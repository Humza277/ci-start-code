# README.md added

# Why should we use SSH with Git-Hub
# Two Methods to clone a Repo

SSH and HTTPS

One is public/ other is private

generate SSH keys on your local system 

copy the ley from local system to the specific repo on github

.ssh folder where ssh keys are available

use this code 
    
    ssh-keygen -t rsa -b 4096 -C "your email here"

name the new key as your name 

cd into the new .pub folder

copy the key

go onto your git hub repo that you want to secure

click on settings

click on keys - click on deploy keys - add the key - then click add key 

## essential to write descriptive names for your keys 
if you  do not, it will be hard to keep track of your keys 
