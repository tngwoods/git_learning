# GitHub 项目管理学习记录（2026-09-13）

这份文档用于记录我准备系统学习 GitHub 项目管理的内容与顺序，目标是先会用、再会协作、最后能独立治理项目。

## 学习目标
- 掌握 Git 的核心命令与工作流
- 能在 GitHub 上完成规范化协作（Issue、PR、Review）
- 能搭建并维护小型到中型项目的协作流程
- 能使用基础自动化（CI）提升协作质量

## 学习顺序（按阶段）

### 1. Git 基础（先学）
- 仓库概念：工作区 / 暂存区 / 本地仓库 / 远程仓库
- 常用命令：`git init`, `clone`, `add`, `commit`, `status`, `log`, `push`, `pull`, `fetch`
- 分支入门：`branch`, `checkout`, `merge`, `rebase`（先用 merge，再学习 rebase）

### 2. GitHub 入门
- 注册与身份认证（SSH 或 Token）
- 创建仓库、配置 `README.md`、`.gitignore`、许可证文件
- 配置远程仓库：`git remote add origin`、`git push` / `git pull`

### 3. 提交规范与基础协作
- Commit Message 规范（如 Conventional Commits）
- 处理冲突（merge conflict）
- Git 标签（tag）和版本发布基础

### 4. Issue 与讨论
- Issue 创建与管理（标题、描述、标签、里程碑、指派）
- Discussion 使用场景（需求确认、方案讨论）
- 从需求到实施的闭环思路

### 5. Pull Request（核心）
- Fork 与同库分支两种协作方式
- 发起 PR、Review、修改反馈、合并（merge / squash）
- CI 失败的排查与修复流程

### 6. 分支策略与团队规范
- 常见流程：Git Flow、GitHub Flow、Trunk-based Development
- 保护分支（Protected Branch）
- 审核规则与提交权限管理

### 7. GitHub Project 与项目看板
- 看板列设置：To Do / In Progress / Review / Done
- 里程碑（Milestone）管理
- 迭代与任务可视化管理

### 8. GitHub Actions 入门
- workflow 文件结构与触发器
- 自动化测试、代码检查、构建、部署
- PR / push 场景下的自动检查

### 9. 安全与团队治理
- 仓库角色与权限控制
- Secrets 安全管理、依赖安全检测、分支保护
- 审计与安全事件响应

### 10. 发布与文档治理
- Release 与 CHANGELOG 管理
- PR/Issue 模板、`CODEOWNERS`、协作规范沉淀
- 文档体系建设（README + docs）

## 推荐学习节奏（4 周）
- 第1周：第1-3部分
- 第2周：第4-5部分
- 第3周：第6-7部分
- 第4周：第8-10部分（持续迭代）

## 下一步实践任务
- 新建一个练习仓库
- 按任务拆分写 3 个 Issue
- 在不同分支上完成两个小功能
- 发起 PR 进行互评式合并
- 配置一个最小 GitHub Actions（如静态检查）
