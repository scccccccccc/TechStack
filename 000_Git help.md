空项目文件夹下

## 创建.git文件夹，开始管理

```
git init
```

## 将项目文件夹下所有文件进入准备commit状态

```
git add .
```

同理单个文件进入准备commit状态只要：

```
git add example.py
```

## 提交至.git文件夹内并加备注

```
git commit -m "功能1已完成"
```

## 查看所有commit记录

```
git log
```

### 从最后一次commit中将example.py复制到项目文件夹

```
git checkout HEAD example.py
```

### 远程修改仓库

```
先用git clone --recursive 把远程仓库下下来

然后git bash进入文件夹，git add、git commit -m提交修改后，

git push origin main在远程仓库上同步修改
```

### 本地当前仓库与远程仓库建立跟踪联系

```
git push origin HEAD -u
```

