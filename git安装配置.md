# 安装并配置
<!-- 
1、git 安装
2、git配置
    1）用户信息（配置个人的用户名称和电子邮件地址）
        $ git config --global user.name "runoob"
        $ git config --global user.email test@runoob.com
3、初始化仓库
    1）git init
    2）git init newrepo
4、添加新文件
    git add filename
5、提交版本
    1）git commit -m "Adding files" # 已经添加了这些文件，我们希望它们能够真正被保存在Git仓库
    2）git commit -a -m "Changed some files" # 对所有修改的文件一次性提交
6、发布版本
    1）从服务器克隆一个库并上传
        git clone ssh://example.com/~/www/project.git
    2）我们修改之后可以进行推送到服务器
        git push ssh://example.com/~/www/project.git
7、取回更新
    1) 已经按上面的进行push，下面命令表示，当前分支自动与唯一一个追踪分支进行合并。
        git pull
    2) 从非默认位置更新到指定的url
        git pull http://git.example.com/project.git
8、删除
    1）如何你想从资源库中删除文件，我们使用rm
        git rm file
9、分支与合并
    1）创建一个新的分支，使用branch命令
        git branch test
    2）branch命令不会将我们带入分支，只是创建一个新分支。所以我们使用checkout命令来更改分支
        git checkout test
    3）第一个分支，或主分支，被称为"master"。
        git checkout master
    4）对其他分支的更改不会反映在主分支上。如果想将更改提交到主分支，则需切换回master分支，然后使用合并
        git checkout master
        git merge test
    5）删除分支
        git branch -d test
 -->