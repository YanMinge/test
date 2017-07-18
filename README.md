#  需要完成的任务 #

## 1. 创建一个命名为 test的远程库 ##

1. 需要创建 README.md 文件
2. 库的属性为 public


## 2. 建立本地库和远程库的联系 ##

1. 创建 test1.txt
2. 创建 test2.txt
3. 创建 test3.txt



## 3. 创建 dev dev_test 分支 ##

1. 创建两个本地分支，分别命名为 dev ，dev_test
2. 切换到 dev 分支，修改 test1.txt 的内容，增加 `1. dev分支的第一次修改`
3. 将 test1.txt的修改添加到暂存区，commit的注释为 `"dev分支的第一次修改"`
4. 切换到 master分支，修改 test2.txt的内容，增加 `1. master分支的第一次修改`
5. 将 test2.txt的修改添加到暂存区，commit的注释为 `"master分支的第一次修改"`
6. 把dev 和 master的修改都推送到远程库的各自分支。
7. dev_test 什么也不做，直接推送。


## 4. 把 dev 的修改 merge 到主库 ##
1. 完成merge 操作即可

## 5. 修改 master的 test2.txt ##
1. 切换到 master分支，修改 test2.txt的内容，增加 `2. master分支的第二次修改`
2. 将 test2.txt的修改添加到暂存区，commit的注释为 `"master分支的第二次修改"`
3. 修改 test2.txt的内容，增加 `3. master分支的第三次修改`
4. 将 test2.txt的修改添加到暂存区，commit的注释为 `"master分支的第三次修改"
5. 将master的修改推送到远程库。   

## 6. 修改 dev的 test1.txt ##
1. 切换到 master分支，修改 test1.txt的内容，增加 `2. dev分支的第二次修改`
2. 将 test1.txt的修改添加到暂存区，commit的注释为 `"dev分支的第二次修改"`
5. 将dev的修改推送到远程库的dev分支。 

## 7. 把dev的修改 rebase到 master ##

理解一下 merge 和 rebase的差别
http://blog.csdn.net/wh_19910525/article/details/7554489


## 8. 打一个V1.0的tag ##