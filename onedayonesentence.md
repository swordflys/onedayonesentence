2022年10月18日

 # 一、Git

 ## （一）git初始设置

git config --global user.name

git config --global user.email

git config --global color.ui

（二）github。

1.创建SSH key。

2.github中添加公开密钥。

3.用私钥与github进行认证和通信。

（三）公开代码

1.克隆仓库代码。git clone

通过

2.添加文件至git仓库。仓库文件夹中添加文件，并将文件，git add加至暂存区，git commit提交至仓库

3.更新推送至github。git push



2022年10月19日

一、Git

（一）文件状态

1.未跟踪。

2.已跟踪。一是未修改。二是已修改。三是已暂存。

（二）文件处理

1.跟踪新文件，将文件添加至暂存区。git add

2.暂存已修改文件，将修改添加至暂存区。git add

3.提交更新。git commit

（三）文件状态查询

1.状态检查。git status

2.状态简览。git status -s

3.查看跟踪文件中未暂存的修改。git diff

4.查看已暂存但未提交的更新。git diff --staged



2022年10月20日

一、Git

（一）查看文件

1.查看工作目录文件。ls

2.查看已暂存文件。git ls-files



2022年10月21日

（二）移除文件

1.移除目录中文件。rm <filename>

2.移除已暂存且未提交的文件。

暂存后未修改：git rm --cached/-f <filename>

暂存后已修改（the file has local modifications）：git rm -f <filename>

3.移除已提交文件。

(1)提交后未修改：git rm <filename>，会同时执行rm <filename>

(2)提交后已修改并暂存（the file has changes staged in the index）：git rm --cached/-f <filename>







2022年10月22日

二、bash

（一）bashrc文件

1.更改默认目录。echo "~/termux/onedayonesentence" >> ~/.bashrc。























