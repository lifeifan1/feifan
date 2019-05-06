### 分支的操作
- 创建并切换分支  git checkout -b branchName
- 在当前分支下进行开发
- 在当前分支下add和commit
- 开发完成之后切换分支，合并分支
- 删除新新创建的分支
### 测试冲突
- 找一个团队成员的GitHub仓库作为公共仓库
- 该仓库的负责人把团队成员的公钥放到SSH那个菜单里
- 所有的团队成员从远程仓库里拉取最新的代码
- 进行冲突测试
# 分支处理
1. 创建分支
	> git checkout -b dev
2. 创建远程分支
	> git push origin dev:dev
3. 删除分支
	> git branch -d dev
4. 删除远程分支
	> git push origin --delete dev
5. 合并分支
	> git merge dev
6. 本地创建并与远程分支关联
	> git checkout -b dev origin/dev
