### 安装git
默认安装

### Linux命令
- pwd，显示当前目录
- ls，显示当前目录下的内容
- ll，详细列表显示当前目录下的内容，等同ls -l
- cd 目录路径，切换目录
- cd ..，进入上一级目录
- mkdir 文件夹名称，新建文件夹
- ls -ah，显示隐藏文件。
- rm 文件名，删除文件。
- rm -r 文件夹名称，删除文件夹。
- clear，清屏。
- touch 文件名，新建一个文件。
- mv 要移动的文件 目标文件夹
- exit，退出。
  
### 进入Git Bash
- git --version，检查版本。
- 切换到仓库目录
- 新建仓库文件夹
- git init，初始化仓库。
- git clone 仓库clone，克隆远程仓库。
- git config --global user.name "用户名"，给所有仓库指定用户名。
- git config --global user.email "电子邮件"，给所有仓库指定用户的电子邮件。
- git config user.name，查看仓库用户名。
- git config user.email，查看仓库用户电子邮件。

### 配置文件
- gitconfig，系统配置文件、用户配置文件。

### 四个工作区域
- 工作目录 working directory
- 暂存区 stage
- 本地仓库 local repository
- 远程仓库 remote repository

### 文件四种状态
- untracked，未跟踪，此文件在工作目录，可以通过git add使文件状态变为staged。
- modified，文件已修改，可以通过git add使文件状态变为staged
- staged，暂存状态
### 添加文件到仓库
- git add 文件名，把文件添加到暂存区。
- git add .，添加所有文件到暂存区。
- git commit -m "本次提交的说明"，把暂存区的的内容提交到当前分支。

### 忽略文件
- .gitignore
- touch .gitignore
### 查看仓库变化
- git status
- git diff 文件名，比较文件变化的内容。
- git diff HEAD -- 文件名，比较工作区和版本库的区别。

### 查看提交记录
- git log
- git log --pretty=oneline，按行显示提交记录。

### 退回到之前的版本
- git reset --hard HEAD^

### 回到指定的版本
- git reset --hard 版本号

### 查看历史版本
- git reflog

### 撤销修改
- git restore 文件名
> add后，restore回到工作区；commit后，restore回到暂存区。

