# Git

版本管理软件

---

## 命令

### checkout --- 跳转到某一分支

```shell
git checkout master     # switch to master
git checkout master foo.txt    # merge master's foo.txt
```

### stash --- 隐藏当前更改

```sh
git stash   # 隐藏当前更改
git stash pop # 恢复更改
```

### reset --- 重置

```sh
git reset --hard $commit_identification   # 重置到 commit
```

### revert --- 撤销提交

```sh
git revert HEAD~3   # 撤销倒数第四次提交
```

### tag --- 添加标签

```sh
git tag -a v0.0.1 -m 'version 0.0.1'    # 增加标签
git tag     # 显示所有标签
git show v0.0.1
git push origin --tags  # 推送到服务器
```

## 技巧
