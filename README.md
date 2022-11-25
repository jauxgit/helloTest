### Git常用指令

#### 1、将文件加入暂存区

```
git add <filename>
```

#### 2、将文件移除暂存区或者切换指定版本

```
git reset <filename>
```

```
git reset --hard <commit>
```


#### 3、将暂存区的文件提交到版本库

```
git commit -m "<message>" <filename>
```

#### 4、查看日志

```
git log
```

#### 5、远程仓库

- 查看远程仓库

  `git remote -v`

- 添加远程仓库

  `git remote add <name> <url >`

- 向远程仓库上传文件/创建分支/标签

  `git push <short-name> <brach-name/tag-name>`

- 从远程仓库拉取

  `git pull <short-name> <brach-name>`

#### 6、克隆仓库

```
git clone <url>
```

#### 4、分支

- 查看分支

  ```
  git branch 列出所有分支
  git branch -r 列出所有远程分支
  git branch -a 列出本地分支和远程分支
  ```

- 创建分支

  ```
  git branch <branch-name>
  ```

- 切换分支

  ```
  git checkout <branch-name>
  ```

- 合并分支

  ```
  git merge <name>
  ```

#### 5、标签操作

- 查看标签

  `git tag`

- 创建标签

  `git tag <name>`

- 检出标签

  检出标签时需要新建一个分支来指向某个标签，检出标签的命令格式

  `git checkout -b <brach> <name>`

