-   ls/ll   查看当前目录
    
-   cat    查看文件内容
    
-   touch  创建文件
    
-   vi    vi编辑器
    

  

1.  设置用户信息
    

  

git config —global user.name "用户名"

git config -global user.email "邮箱"

  

  

  

  

` git config --list `  查看配置

  

设置指令别名

touch ~/.bashrc

在 .bashrc 文件中输入下面内容

# 用于输出 git 提交日志

alias git-log='git log --pretty=oneline --all --graph --abbrev-commit'

# 用于输出当前目录所有文件及基本信息

alias ll='ls -al'

执行 ` source ~/.bashrc `

2.  基本操作指令
    

  

-   git add ( 工作区 -> 暂存区 ) *
    
-   git commit ( 暂存区 -> 本地仓库 ) *
    

  

-   git status 查看当前状态 *
    
-   git log  查看提交日志 *
    

  

版本回退

-   版本切换 ` git reset  --hard commit ID `
    
-   查看版本日志  ` git reflog
    

  

  

3.  分支
    

-   查看本地分支 ` git branch `
    
-   创建本地分支  
    
-   -   ` git checkout 分支名 `
        
    -   创建并切换到一个不存在的分支   ` git checkout -b 分支名 `
        
-   合并分支（merge）` git merge 分支名 `
    
-   删除分支 
    
-   -   ` git branch -d 分支名 `
        
    -   强制删除 ` git branch -D 分支名 `
        

  

  

远程仓库操作

  

git branch -vv  查看本地仓库与远程仓库的关联

  

-   将本地仓库关联远程仓库
    
-   -   ` git remote add origin  <仓库地址> `
        
-   查看远程仓库
    
-   -   ` git remote `
        
-   将本地代码推送至远程仓库  git push [ -f ] [ --set-upstream ] [ 本地分支名 ] : [ 远端分支名 ]
    
-   -   ` git push origin master `
        
    -   -   -f  强制覆盖
            
        -   --set-upstream  推送到远端的同时并且建立起和远端分支的关联关系