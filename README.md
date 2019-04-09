# git操作的一些步骤

1、本地创建版本库 （创建一个版本库非常简单，首先，选择一个合适的地方，创建一个空目录：）
  mkdir gitdemo
  cd gitdemo

2、通过git init命令把这个目录变成Git可以管理的仓库：
  git init

3、把文件添加到版本库
  git add filename
  git commit -m "文件说明"

二、克隆一个远程仓库  git clone git@github.com:yowhat/notes.git

三、修改远程库的文件并推送给远程库  
   git add filename
   git commit -m "文件说明"
   git push -u origin master






