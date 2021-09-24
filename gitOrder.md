# Git操作指南

PS：下述所有操作对象都为<.git>文件所在的文件夹

## 1.将指定目录变成Git仓库

```
git init       # 目录初始化未Git仓库
git clone url  # 直接在线平台复制仓库
```

生成<.git>文件夹

## 2.将文件添加到Git仓库

```
git add readme1.txt readme2.txt readme3.txt  # 添加多个文件，文件之间以空格隔开
git config/*                                 # config目录下及子目录下所有文件
git home/*.php                               # home目录下的所有.php文件
git add .                                    # 添加所有的文件
git add --all                                # 添加所有的文件 
git add 文件夹名                              # 添加文件夹 
```

错误处理：

```
Error:fatal: not a git repository (or any of the parent directories)
```
==>确认git 命令有没有在仓库所在的文件夹执行

```
fatal: pathspec 'readme.txt' did not match any files
```
==>添加某个文件时，该文件必须在当前目录下存在，用ls或者dir命令查看当前目录的文件，看看文件是否存在，或者是否写错了文件名。

## 3.将修改提交到本地版本库

```
git commit -m "add  comments"                #双引号内容未本次提交的备注
```

PS:git add 目的是将修改文件由工作区提交到暂存区，可以多次提交,然后commit操作，将文件从暂存区提交到版本库。

## 4.将修改合并到线上仓库

```
git push url  #将本地版本库内容合并到在线分支
git pull url  #将在线分支与本地版本库内容合并
```

