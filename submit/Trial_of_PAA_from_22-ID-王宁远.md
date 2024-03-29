# Trial of PAA from 22-ID-王宁远

## 什么是Git？

Git是程序员常用的分布式版本控制系统，同时也是一个内容管理系统。相比于SVN，它是分布式的，意味着没有中心服务器。用户可以从各个作为服务器的远程仓库中获取该仓库的内容。Git的另一优点是便于团队协作。一个用户进行代码更改后，更改保存在暂存区（stage），用户可将更改添加至HEAD，随后``Push``到远程仓库。通过选择不同的分支（branch），用户可阶段性维护（一个实践是增加 features）和分角色开发，最后与主分支``合并（merge）``。Git可随时回调版本，这是由 SHA-1 算法保证的，可确保内容完整性。

## 为什么要用Git？

如前文所述，Git便于团队协作和版本管理。此外，有许多可用的代码托管平台，如Github、Gitee等，我们也可以用Gitea在自己的服务器上搭建私有平台，这便利了我们建立远程仓库。

## 使用Git的注意事项

### 通常从``克隆（clone）``仓库开始
在代码托管平台创建远程仓库后，克隆到本地的工作区。在工作区做出改动后``push``到远程仓库。
### 合理建立分支

### 填写有效的提交日志（commit message）
提交日志用于说明本次``push``的内容。
### 使用README文档确保可读性
### 确保网络联通性
部分代码托管平台位于境外服务器，需要确保国际互联网连接。
### 使用.gitignore文件屏蔽不需要``git``的文件
### 遵循开源协议
引用开源库时，注意该库遵循的开源协议，可能对其上开发的程序提出开源要求。