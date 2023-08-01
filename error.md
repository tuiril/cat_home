## 无法push
### 显示的错误
  remote: Support for password authentication was removed on August 13, 2021.
  
  remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
  
  fatal: Authentication failed for 'https://github.com/tuiril/cat_home.git/'
### solve
  git remote -v (查看远程仓库）：origin	git@github.com:tuiril/cat_home.git (fetch) —— 仓库名 地址（允许的操作）
  
  git remote rm 仓库名 - git remote rm origin (移除远程仓库origin）

  git remote add 仓库名 ssh-url - git remote add origin git@github.com:tuiril/cat_home.git (设置远程仓库地址） 
   
