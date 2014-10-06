test
====

a repository for learning git


一、初识git

1、安装git

2、git命令

  git --version #查看git版本（#代表注释）
  
  git --help    #查看git命令帮助
  
  git config -l #列出git全部配置
  
  git config --global user.name "anye1919"           #设置用户名
  git config --global user.email "1066242324@qq.com" #设置邮箱

3、假设把代码仓库(repository)都放在文件夹 D:\github\ 下

   打开cmd命令窗口，切换到该目录下：d: -> cd github (箭头->代表操作步骤)

   建立一个 test 文件夹：mkdir test  #test文件夹就是存放代码的仓库

   列出github文件夹下所有的仓库：dir

   切换到我们的test仓库：cd test

   初始化版本仓库：git init

   建立一个空文件：type nul>README.md 

   将文件添加到缓存区：git add README.md

   缓存提交并添加注释：git commit -m 'test commit'



