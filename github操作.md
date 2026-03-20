初始化仓库

```
git init
```

关联远程仓库（去`github`新建一个仓库）

```
git remote add origin https://github.com/你的用户名/仓库名.git
```

核心三部曲（日常更新）

```
第一步添加文件

git add .
添加当前目录下所有修改

git add 文件名称.md
只添加特定文件

第二步提交说明

git commit -m "记录内容"
给这次上传打一个标签，做个记录，自己做了哪些修改

第三步推送至github

git push origin master
(注意：早期的仓库默认分支可能是 master，现在 GitHub 多为 main)
```

