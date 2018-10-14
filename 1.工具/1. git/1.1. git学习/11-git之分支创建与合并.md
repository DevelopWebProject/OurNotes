操作总流程：
- 1、[创建分支](#git-01)
- 2、[查看分支情况](#git-02)
- 3、[修改文件，使用分支提交数据](#git-03)
- 4、[切换回主分支](#git-04)
- 5、[合并分支](#git-05)
- 6、[删除分支](#git-06)
- 7、[查看分支情况](#git-07)

----------

# <a name="git-01" href="#" >1、创建分支</a>
- 命令：
```shell
git checkout -b dev
```
# <a name="git-02" href="#" >2、查看分支情况</a>
- 命令：
```shell
git branch
```
# <a name="git-03" href="#" >3、修改文件，使用分支提交数据</a>
- 命令：
```shell
git add readme.txt
git commit -m "branch test"
```
# <a name="git-04" href="#" >4、切换回主分支</a>
- 命令：
```shell
git checkout master
```
# <a name="git-05" href="#" >5、合并分支</a>
- 语法：
```shell
git merge 选项 dev
```

选项：

--no-ff：可以用普通模式合并，合并后的历史有分支，能看出来曾经做过合并

# <a name="git-06" href="#" >6、删除分支</a>
```shell
git branch -d dev
```
# <a name="git-07" href="#" >7、查看分支情况</a>
```shell
git branch
```