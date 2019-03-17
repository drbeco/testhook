# Creation

This repository was created by:

* $ mkdir testhook
* $ git init
* $ vi README.md
* $ git add README.md
* $ git commit -S -m "added README.md"
* $ curl -u "drbeco:$(cat ./AUTHTOKEN)" https://api.github.com/user/repos -d '{"name":"testhook"}'
* $ git remote add origin git@github.com:drbeco/testhook.git
* $ git push -u origin master

