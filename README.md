Hello-Spiders
=============
$ mkdir ~/Hello-World
$ cd ~/Hello-World
$ git init
$ touch README
$ git add README
$ git commit -m 'first commit'
$ git remote add origin https://github.com/efbarlow/Hello-Spiders.git
$ git push origin master
$ git clone https://github.com/efbarlow/Hello-Spiders.git
$ cd Hello-Spiders
$ git remote add upstream https://github.com/octocat/Hello-Spiders.git
$ git fetch upstream
$ git push origin master
$ git fetch upstream
$ git merge upstream/master
