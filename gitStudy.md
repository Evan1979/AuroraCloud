# Git学习

## Git安装

## 初始化Git仓储（/仓库）
- 这个仓库会存放，git对我们的项目代码进行备份的文件
- 在这个项目右键打开 git bush
- 初始化命令“git init”

## 配置个人信息
- 在git中配置当前使用的用户是谁
- 命令： 
 + $ git config --global user.name "evan"
 + $ git config --global user.email "928946604@qq.com"
 
## 将代码放置到git仓库
- 1、预添加 
	+ $ git add ./目录路径
- 2、提交代码  
	+ $ git commit -m "本次提交改变说明"
 
## 命令查看状态
- git status
	+ modified（绿色）：表示已经放置到暂存区域  即已经执行add
	+ modified（红色）：已修改文件但是未执行任何指令

## 添加多个文件
- git add ./    //将当前的所有文件都提交

## 
## 
 