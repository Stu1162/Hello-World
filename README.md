Hello-World
===========
$ mkdir ~/Hello-World
# creates a directory for your directory called "Hello-World"

$ cd ~/Hello-World
# changes your working directory to the newly created directory

$ git init
# sets up the necessary git files

$ touch README
# creates a file called "README" in your Hello-World directory

$ git add README

$ git commit -m 'first commit'
# commits your files, adding the message "first commit"

$ git remote add origin https://github.com/username/Hello-World.git
# Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
# Sends your commits in the master branch to Github
