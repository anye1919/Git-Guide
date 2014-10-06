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

   #你的本地仓库由 git 维护的三棵“树”组成。第一个是你的 工作目录，它持有实际文件；第二个是 缓存区（Index），它像个缓存区域，临时保存你的改动；最后是 HEAD，指向你最近一次提交后的结果。

   将文件添加到缓存区：git add README.md

   缓存提交并添加注释：git commit -m "test commit"

   现在，你的改动已经提交到了 HEAD，但是还没到你的远端仓库。

   添加远程仓库：git remote add origin https://github.com/anye1919/test.git #注意url格式，anye1919是你注册时的昵称，test是你刚才建立的版本仓库

   执行如下命令以将这些改动提交到远端仓库：git push origin master #可以把 master 换成你想要推送的任何分支

   

   

