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

![image-20221124155234256](C:\Users\Santa\AppData\Roaming\Typora\typora-user-images\image-20221124155234256.png)

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

  ![image-20221124161005302](C:\Users\Santa\AppData\Roaming\Typora\typora-user-images\image-20221124161005302.png)

#### 6、克隆仓库

```
git clone <url>
```

