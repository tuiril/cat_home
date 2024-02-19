
# md 文件使用
- 按i进入编辑
- 按esc退出编辑
- 按英文冒号可输入命令
- w 保存
- q 退出
- q! 强制退出
- set paste 粘贴模式,在粘贴模式下进入编辑用复制粘贴不会乱码
- u 撤销一次修改

# shell 基础语法
---
## mkdir xx
创建'xx'文件夹

## cd xx
打开'xx'文件夹

## ls
### ls：列出当前文件夹中的内容
### ls -a：列出当前文件夹的内容（包括隐藏文件）
- 隐藏文件：以.开头的文件
  1.'.'当前文件夹
  2.'..'上一级文件夹
  3.'.aa'名字为.aa的文件或文件夹
### ll（ls -l）：以list形式显示文件更多的属性

## ssh-keygen
（ssh是一种协议）生成ssh的公钥和私钥，私钥不能泄漏

## pwd
查看当前路径

## rm/rm -r
删除文件/删除文件夹

## cat 'xx'
显示xx文件内容

## vim/vi
编辑文件，vi xx_md：打开xx_md文件进入编辑

## git
### git init
将当前文件夹变为git文件夹，使其能执行git操作
### git status
查看当前目录下各文件的状态：修改后/修改并被加入缓存区的文件会展示出来
### git add 'xxx'
把'xxx'的修改加入缓存区
### git commit -m "xx"
将当前缓存区的修改同步到电脑中的git仓库，注释为xx，本操作之前必须先git add 
### git push
将本地git仓库中的修改同步到远程，本操作之前必须先git commit -m "xx"
### git clone '链接地址'
将远程链接的git仓库克隆到本地，有权限时可以修改远程仓库

## mv 
mv a.txt b.txt 将a.txt文件重命名为b.txt

mv a/c.txt b/c.txt 将a文件夹中的c.txt移动到b文件夹中，名字仍为c.txt

mv a/c.txt b/d.txt 将a文件夹中的c.txt移动到b文件夹中，改名为d.txt

## *
所有文件 eg：lin/* lin文件夹下所有文件；rm *.csv 删除当前目录下所有csv文件 
