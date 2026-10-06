# 我的 Git 学习笔记

## 第一次 Git 实验总结
1. `git add` 的作用是：把工作区的改动加入暂存区 (stage)，标记哪些文件准备提交
2. `git commit` 的作用是：把暂存区的改动保存到本地 Git 仓库，生成一条 commit 记录
3. 本次实验中 `git restore notes.md` 的作用是：用仓库里的版本覆盖工作区文件，撤销工作区未暂存的修改
4. `commit` 与 `push` 的区别是：commit 只提交到本地仓库；push 把本地提交上传到远程 GitHub 仓库