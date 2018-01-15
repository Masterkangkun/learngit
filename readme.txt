Git is a version control system. checkout？
Git is free software distributed under the GPL
Git has a mutable index called stage or index
Git tracks changes of files.

//提交
$ git add readme.txt    提交所有：$ git add .
$ git commit -m "append GPL"

//撤销修改(总之，就是让这个文件回到最近一次git commit或git add时的状态。)
$ git checkout -- readme.txt

//删除文件
$ rm test.txt
1删除提交
$ git rm test.txt
$ git commit -m "remove test.txt"
2删错了撤回
$ git checkout -- test.txt

生成ssh秘钥：
http://blog.csdn.net/zxd0328/article/details/42403749
上传：
git remote add origin https://github.com/Masterkangkun/learngit.git
git push -u origin master
git push origin master

//从远程库克隆
git clone 地址


//分支
Create a new branch is quick and simple

git checkout -b dev
=生成后切换
git branch dev
git checkout dev

git branch查看
git merge dev合并
git branch -d dev删除

