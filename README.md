# MJGitStudy

### 一、Git配置

#### config

````shell
git config --list
git config user.name
git config user.email
````

### 二、Git状态

#### status

````
git status
git status -s
````

####  rm

````shell
#删除缓存
git rm --cached README.md
````

#### mv

````shell
#文件重命名
git mv README.MD README.md
````

#### log

````shell
#查看最近2个更新的差异，－p:patch补丁　2:最近两项
git log -p -2
#查看最近更新的统计:stat
git log --stat 
#图形化显示
git log --graph
#查看日志格式　cn:commit name cd:commit date s:commit string 
git log --pretty=format:"%cn %cd %s"
#查看提交信息中包含"日志内容"
git log --grep　"日志内容"
#查看代码修改中包含　"代码更新"
git log -S "代码更新"
````

#### reset－stage

````
````



#### diff查看修改内容

````shell
git diff
````

