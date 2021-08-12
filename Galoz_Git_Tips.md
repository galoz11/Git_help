## Here is how I rename a tag old to new:

git tag new old

git tag -d old

git push origin new :old


## Generating pair of keys

ssh-keygen -t ed25519 -C "myname@hotmail.com"

## check key i have

ls -al ~/.ssh

## Adding your SSH key to the ssh-agent

ssh-add ~/.ssh/id_ed25519

## Start your ssh-agent

eval "$(ssh-agent -s)"