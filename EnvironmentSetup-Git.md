# Manage Github by Git Commands

Record on setting up github repo, and commit file from local folder with git commands.

## Main tasks:

The main steps are:

1. Register a github account:<br>

2. set up ssh key (local, github, local)

  - cd ~/.ssh
  - ssh-keygen -t rsa -C "your_email@example.com"
  - vim name.pub
  - ssh -T git@github.com (This is to test ssh setup)

3. create a repo on git

4. clone repo to local folder

  - git clone git@github.com:username/foldername.git

5. modify something, say "readme.md"

6. make your first commit by git command!

  - cd repofolder
  - git add .
  - git commit -m 'commit note'
  - git remote add origin git@github.com:username/foldername.git
  - git push -u origin master

Have fun with it! :)

## Reference

1. [ssh setup](http://www.cnblogs.com/ayseeing/p/3572582.html)
2. [link repo with local folder and push](http://www.jianshu.com/p/deb5eddbffb8)
