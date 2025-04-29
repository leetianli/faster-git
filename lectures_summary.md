# Git课程lecture01-lecture10主要内容总结

## 第一章 Git简介
- Git是什么：分布式版本控制系统
- Git的特点：速度快、设计简单、完全分布式、支持非线性开发
- Git与SVN等集中式版本控制系统的区别

## 第二章 Git基础命令
- 基本工作流程：工作区 → 暂存区 → 本地仓库 → 远程仓库
- 常用命令：
  - `git init` - 初始化仓库
  - `git add` - 添加到暂存区
  - `git commit` - 提交到本地仓库
  - `git push` - 推送到远程仓库
  - `git pull` - 从远程拉取更新

## 第三章 Git分支管理
- 分支的概念：轻量级指针，指向某次提交
- 分支操作：
  - `git branch` - 查看/创建分支
  - `git checkout` - 切换分支
  - `git merge` - 合并分支
- 解决合并冲突的方法

## 第四章 Git工具
- `git stash` - 暂存当前修改
- `git rebase` - 变基操作
- `git cherry-pick` - 选择特定提交
- `git bisect` - 二分查找问题提交

## 第五章 Git内部原理
- `.git`目录结构：
  - `objects` - 存储所有数据内容
  - `refs` - 存储指向数据的指针
  - `HEAD` - 当前检出的分支
  - `config` - 配置信息
- Git对象模型：commit、tree和blob

## 第六章 GitFlow工作流实战
- GitFlow工作流模型：
  - 主分支：master、develop
  - 辅助分支：feature、release、hotfix
- 完整Git-Flow流程演示：
  1. 初始化项目，创建develop分支
  2. 开发阶段：创建feature分支开发
  3. 发布阶段：创建release分支
  4. 合并到master并打tag

## 第七章 Git提交规范
- 提交信息格式：`<type>: <short summary>`
- 常见type：
  - feat: 新功能
  - fix: 修复bug
  - docs: 文档变更
  - style: 代码格式变更
  - refactor: 代码重构

## 第八章 Github/Gitee使用说明
- Github核心功能：
  - 仓库管理
  - Pull Request工作流
  - Issues跟踪
  - Wiki文档
- Gitee国内镜像使用
- 探索Github技巧：
  - 使用awesome系列
  - 关注优质项目

## 第九章 Git图形工具
- 常用GUI工具：
  - Github Desktop
  - TortoiseGit
  - VSCode Git集成
- 图形工具与命令行的比较

## 第十章 Git团队协作
- 代码推送方式：
  - 直接推送
  - Pull Request方式
- 代码比较与冲突处理
- 团队协作工作流：
  - Forking工作流
  - 集中式工作流
  - GitFlow工作流