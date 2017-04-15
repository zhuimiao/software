#git
##本小节知识点
1. 为什么要掌握git 命令？
2. 配置全局 username 和 email
3. 代码仓库提交到 github
---
### 为什么要掌握git？
直接用 sourcetree 也可以进行 git 操作， 但是掌握 git 命令是很必要的。
* git 命令 面试时候会问。
* git 命令 了解命令，容易理解 git 操作的本质。

### 配置全局 username 和 email

```
git config --global user.name "Your Name"
git config --global user.email you@example.com
```

### 代码仓库提交到 github
```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/zhuimiao/software.git
git push -u origin master
```
