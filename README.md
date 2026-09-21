# git-practice

> Git 基础命令练习仓库 · 用于实操 `clone` / `add` / `commit` / `branch` / `push` / `pull` 等工作流。

这是一个专门的练习场，放心大胆地试，弄乱了也不影响任何真实项目。

## 练习目标

- 熟悉本地仓库与远程仓库的关系
- 掌握日常提交闭环：`add → commit → push`
- 理解分支（branch）的创建、切换与合并
- 学会从远程同步：`clone` 与 `pull`

## 仓库信息

- 远程地址：`https://github.com/Aermberry/git-practice.git`
- 默认分支：`main`
- 可见性：Public

## 常用命令速查

```bash
# 1. 克隆（把远程仓库拉到本地）
git clone https://github.com/Aermberry/git-practice.git

# 2. 查看状态与改动
git status
git diff

# 3. 暂存与提交
git add <文件>        # 或 git add . 暂存全部改动
git commit -m "描述这次改动"

# 4. 分支
git branch            # 查看分支
git branch feature-x  # 新建分支
git switch feature-x  # 切换分支（也可用 git checkout feature-x）
git switch main       # 切回主分支

# 5. 推送到远程
git push origin <分支名>

# 6. 从远程拉取更新
git pull
```

## 推荐练习流程

1. `git clone` 把仓库克隆到本地。
2. 新建一个以你名字/日期命名的分支，例如 `git switch -c practice-2026`。
3. 修改本 README 或新增一个 `notes.md`，写点练习记录。
4. `git add .` → `git commit -m "..."` 完成一次提交。
5. `git push origin practice-2026` 推送到远程。
6. 回到 GitHub 看看你的分支和提交，再 `git pull` 体验同步。

## 练习清单

- [ ] 成功 clone 本仓库
- [ ] 新建并切换到一个练习分支
- [ ] 完成至少一次 add + commit
- [ ] 把分支 push 到远程
- [ ] 执行一次 pull 同步

---

祝练习顺利 🎯 有任何命令拿不准，先 `git status` 看看当前状态。
