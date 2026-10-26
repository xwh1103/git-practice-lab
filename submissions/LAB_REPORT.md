# 实验报告 / LAB_REPORT

> 做题者填写本文件后，随功能分支一并提交，并在 PR 中带上。

## 基本信息

- **GitHub 用户名：xwh1103 <!-- 填写 -->
- **功能分支名：** `lab/xwh1103`<!-- 填写用户名 -->
- **PR 链接：** <!-- 开好 PR 后粘贴 -->

## 阶段清单

- [ ] Stage 0 — Fork、clone、upstream、创建 `lab/<username>`
- [ ] Stage 1 — 工作区 / 暂存区 / commit
- [ ] Stage 2 — 分支、merge、冲突解决
- [ ] Stage 3 — 坏提交 + revert
- [ ] Stage 4 — 添加 submodule `third_party/kit`
- [ ] Stage 5 — fetch upstream、push、开 PR

## 简答题

### 1. 工作区、暂存区、已提交（commit）分别是什么？

<!-- 你的回答 -->
工作区是编辑文件的地方，使用git diff命令可以看出本次修改了哪些文件
暂存区是所有准备提交的文件的地方，需要讲工作区的代码进行git add命令进入暂存区，使用使用git diff --status命令可以看出本次修改了哪些文件
已经由git commit提交的文件，可以使用git log -1 online查看
### 2. `git pull` 和 `git fetch` 有何不同？你通常何时用哪个？

<!-- 你的回答 -->
git fetch 只从远程仓库下载最新提交和分支信息，不会修改当前分支或工作区
git pull 它不仅从远程仓库下载最新提交和分支信息，而且立即合并到当前分支，相当于比git fetch多了一个merge操作
### 3. 什么情况下不应该对已推送的共享分支使用 `git reset --hard`？为什么？

<!-- 你的回答 -->

### 4. 带 submodule 的仓库 clone 后子目录是空的，常见原因是什么？怎么处理？

<!-- 你的回答 -->

## 关键 commit（填写短 hash 或完整 hash）

| 说明 | Hash |
|------|------|
| Stage 1 第一次较好的 commit | |
| Stage 2 冲突解决（或合并）commit | |
| Stage 3 revert 产生的 commit | |
| Stage 4 submodule add 的 commit | |

## Stage 2 补充

- 普通 merge 结果：□ 快进（fast-forward）　□ 合并提交（merge commit）　□ 其他：
- 冲突解决简述：

## Stage 5 补充

- 同步 `upstream/main` 时使用：□ merge　□ rebase
- 选择理由：

## 其他备注（可选）

<!-- 例如：只用了非交互式 add、环境限制、踩过的坑等 -->
