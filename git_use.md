git init

git commit -m "first commit"

//该命令将当前的分支名称修改为 main。-M 是强制重命名选项，即使目标分支名称已存在也会覆盖它。
git branch -M main 

git remote add origin https://github.com/unknownpe12138/git_use.git
git push -u origin main

//git代理设置
git config --global http.proxy http://localhost:7897
git config --global https.proxy http://localhost:7897
