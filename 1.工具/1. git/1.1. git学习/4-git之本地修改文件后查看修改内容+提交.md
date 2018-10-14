操作总流程：
- 1、[修改test.txt文件内容](#git-01)
- 2、[git status命令看仓库当前的状态](#git-02)
- 3、[git diff命令看修改了什么内容](#git-03)
- 4、[git add命令提交修改文件](#git-04)
- 5、[git status看当前仓库的状态](#git-05)
- 6、[git commit命令提交](#git-06)
- 7、[git status看当前仓库的状态](#git-07)

----------

`注：要进入文件存放文件夹里进行命令`

# <a name="git-01" href="#" >1、修改test.txt文件内容</a>
- 操作过程：

![](image/4-1.png)

- 改前：
```shell
这是一个测试文件
```

- 改后：
```shell
这是一个测试文件
这是修改的部分
```
# <a name="git-02" href="#" >2、git status命令看仓库当前的状态</a>

- 命令：
```shell
git status
``` 

- 效果展现：

![](image/4-2.png)

# <a name="git-03" href="#" >3、git diff命令看修改了什么内容</a>

- 命令：
```shell
git diff test.txt
```
- 效果展现：

![](image/4-3.png)

# <a name="git-04" href="#" >4、git add命令提交修改文件</a>

- 命令：
```shell
git add test.txt
```
![](image/4-4.png)

# <a name="git-05" href="#" >5、git status看当前仓库的状态</a>

- 命令：
```shell
git status
```

- 效果展现：

![](image/4-5.png)

# <a name="git-06" href="#" >6、git commit命令提交</a>

- 命令：
```shell
git commit -m "add distributed"
```
- 效果展现：

![](image/4-6.png)

# <a name="git-07" href="#" >7、git status看当前仓库的状态</a>

- 命令：
```shell
git status
```

- 效果展现：

![](image/4-7.png)

