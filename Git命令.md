## git命令

#### git add . 添加所有文件

```bash
	
	# 添加所有文件	
 	$ git add .
	# 添加单个文件
	$ git add filename
	
```

#### git commit 将文件更新或者添加到本地仓库
```bash
	# 如果是新添加的文件
	$ git commit -am "this message is a notice for todo"
	# 如果是修改文件
	$ git commit -m "this is notice for todo"
```

远程分支拉去并合并

```bash
git fetch origin master
```

