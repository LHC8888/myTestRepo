1.在仓库目录中使用 git init 命令来生产git仓库
2.使用 git add filename 把filename文件添加到git仓库中
3.使用 git commit -m "msg" 把已经添加到git仓库中的文件提交到git仓库中并添加msg说明
4.使用 git status 查看当前仓库的状态
5.提交修改和提交新文件一样，即2，3步
6.使用 git reset --hard HEAD^/commitId 来回退版本，在cmd中需要在HEAD^两边加双引号，或者可以跳到commitId版本，ver是git log打印出来的历史纪录中的commit id，使用git reflog可以找到所有的版本