### 强制pull

1. git fetch --all
2. git reset --hard origin/main
3. git pull

### 清除已经跟踪的文件（如：dist）

1. git rm -r --cached dist
2. 在.gitignore添加 dist/
3. 重新提交

### 撤销commit和add 的文件

git reset --soft HEAD~1

git add . （只添加修改的文件夹）

git add -A（添加所有文件）

### 强制撤销commit的文件，回到某一次commit（清除所有add)

git reset --hard HEAD~1

### 切换分支

git checkout xxx

### 提交





