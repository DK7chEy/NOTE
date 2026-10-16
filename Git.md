# Git

* 作用：保存项目历史 可以用于回退历史 不怕项目改坏 查看项目历史

* 基本使用命令

1.cd ~+文件夹地址：进入文件夹

2.git init：创建git仓库（.git文件）

3.git status：查看当前仓库状态（显示未跟踪文件）

4.git add+文件（将文件加入==暂存区==）

5.git commit  （-m“”）：将暂存区中的文件加入==历史版本==（永久保存）-m“添加注释”

6.git log：查看commit历史（按q退出）

7.git diff：查看代码修改部分（一般用于git status检测出项目变化后）

8.git restore：撤销工作区改动(现有文件与历史版本不同 )

9.git restore –staged+文件：撤销暂存区中的文件的改动

10.git reset –hard HEAD~1：将所有状态回退到上一个commit保存时的状态（包括工作区 暂存区，历史版本）

11.git reset (–mixed)：只保留==工作区==

12.git reset –soft：保留==工作区==和==暂存区==

