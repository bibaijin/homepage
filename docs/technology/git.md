# Git

版本管理软件

---

## 技巧

### 合并另一个分支的某个文件

#### 语法

```shell
git checkout source_branch <paths>...
```

#### 例子

```shell
git checkout master Makefile    # now in branch banking
```

### 标签的使用

```sh
git tag -a v0.0.1 -m 'version 0.0.1'    # 增加标签
git tag     # 显示所有标签
git show v0.0.1
git push origin --tags  # 推送到服务器
```
