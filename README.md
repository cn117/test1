niuhao@niuhao-OptiPlex-390:~/GitHub$ mkdir test1
niuhao@niuhao-OptiPlex-390:~/GitHub$ cd test1/
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ ls
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ touch README.md
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ git init
初始化空的 Git 版本库于 /home/niuhao/GitHub/test1/.git/
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ git add README.md
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ git commit -m "first commit"
[master （根提交） 24bbe5d] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ git remote add origin git@github.com:cn117/test1.git
niuhao@niuhao-OptiPlex-390:~/GitHub/test1$ git push -u origin master 
Counting objects: 3, done.
Writing objects: 100% (3/3), 205 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To git@github.com:cn117/test1.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
