# 一. github 一个完整流程
- git init / clone
- git add
- git commit -m ""
- git push
- git pull / fetch

# 二. 分支操作
### 1. 创建分支
- git branch [branchname]
- git checkout [branchname] 
- git checkout -b [branchname]

### 2. 合并/删除分支
- git merge [branchname]
- git branch -d [branchname]

### 3. stash 操作
- git stash list
- git stash apply
- git stash pop
- git stash clear

# 三. 团队协作
push 失败的原因及解决方法  
- git log --no-merges origin master
- git fetch origin
- git merge origin/master 

# 四. 三步开启 github pages 静态博客

- 以用户名为名创建仓库 (yourname.github.io)
- 上传静态源码
- setting 开启 github pages 功能
- [hexo 博客搭建及next主题配置](https://hexo.io/zh-cn/)
