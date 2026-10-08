# AGENTS.md — AI Agent 入口协议

> 本仓库是学员 **CQ** 的长期英语学习项目，**不是代码项目**。
> 全部产出是教学内容与学习档案；「正确」的标准是**学员能否自主造句**，不是能否编译通过。

---

## 🚦 新 AI 接入顺序（严格按此四步）

1. **读 [MEMORY.md](MEMORY.md)** —— 权威状态源。重点看第 3 节（当前进度 / 已掌握语块）与第 4 节（交接指令 / **未完成现场**）。
2. **读 [.qoder/rules/](.qoder/rules/) 下三条规则** —— 教学铁律、归档与提交协议、文件引用规范。**规则与本文件冲突时，以规则为准。**
3. **若第 4 节记录了「未完成现场」，开场第一件事就是接续它**，不要另起新题。
4. **收尾必须完成强制四步**（回写三处档案 → 校验链接 → 中文 commit → push），详见 [.qoder/rules/archive-and-commit.md](.qoder/rules/archive-and-commit.md)。

---

## 📐 项目规范存放位置

| 内容 | 位置 | 说明 |
| :--- | :--- | :--- |
| **项目规则** | [.qoder/rules/](.qoder/rules/) | **唯一权威源**。Qoder 原生识别，按主题分文件 |
| **教学状态** | [MEMORY.md](MEMORY.md) | 进度、已掌握语块、交接指令、断层修复记录 |
| **学员画像** | [learner_profile.md](learner_profile.md) | 起点水平、认知特质、目标 |
| **进度看板** | [progress_tracker.md](progress_tracker.md) | 里程碑、打卡表、错题备忘录 |
| **语块库** | [vocabulary/high_frequency.md](vocabulary/high_frequency.md) | 顶部「归档计数」表是 M2 百分比的**唯一数据源** |
| **语法课程** | [grammar/](grammar/README.md) | 六课 + 动词变形速查表 |
| **每日日志** | [daily_logs/](daily_logs/README.md) | `YYYY-MM-DD.md`，含非教学时段的仓库维护记录 |

### 三条规则一览

| 规则文件 | 管什么 |
| :--- | :--- |
| [teaching-iron-rules.md](.qoder/rules/teaching-iron-rules.md) | 私教身份、3~8 分钟微循环、不刷题、**溯源讲解 + 乱序积木 + 只给原形**、正向激励、已确立的语法世界观 |
| [archive-and-commit.md](.qoder/rules/archive-and-commit.md) | 会话开始读什么、会话结束强制四步、中文 commit 规范、计数纪律、补录纪律 |
| [file-reference.md](.qoder/rules/file-reference.md) | 内部链接一律相对路径，严禁 `file:///Users/...`；收尾逐条校验 |

---

## 📂 目录结构

```text
lesson/
├── AGENTS.md                    # 本文件：AI 入口协议
├── .qoder/rules/                # ⭐ 项目规则（唯一权威源）
│   ├── teaching-iron-rules.md
│   ├── archive-and-commit.md
│   └── file-reference.md
├── MEMORY.md                    # ⭐ 教学状态与交接指令
├── learner_profile.md           # 学员画像
├── progress_tracker.md          # 进度看板与错题备忘录
├── study_plan.md                # 三阶段路线图
├── README.md                    # 项目主页与方法论
├── grammar/                     # 语法六课 + 变形速查表
├── vocabulary/                  # 语块库（含 M2 计数表）
├── daily_logs/                  # 每日日志
└── assessments/                 # 摸底测评（已归档，禁止使用）
```

---

## 🔄 迁移说明（2026-10-08 Qoder 项目化改造）

本仓库原先用**多份手写入口文件**承载规范，现已收敛为 Qoder 原生结构：

| 变更 | 原状 | 现状 |
| :--- | :--- | :--- |
| **规则存放** | 写在 `AGENTS.md` 正文（规则 1~5）+ `MEMORY.md` 第 2 节（铁律 1~10），两处互为副本 | 移入 `.qoder/rules/` 三个主题文件，`AGENTS.md` 与 `MEMORY.md` 只留指针 |
| **`CLAUDE.md`** | `AGENTS.md` 的英文摘要副本 | **已删除**（Qoder / Claude / Codex 等均自动读 `AGENTS.md`，副本只会漂移） |
| **`GEMINI.md`** | `AGENTS.md` 的英文摘要副本 | **已删除**（同上） |
| **`CROSS_LLM_PROMPT.md`** | 手机端跨模型接力 Prompt | **已删除**，统一走 Qoder |

> ⚠️ **历史日志中的旧编号**：`daily_logs/` 里提到的「`AGENTS.md` 规则 3 / 4 / 5」是改造前的编号，属历史事实记录，**未改写**。对照关系：
> - 规则 1、3、4（读 MEMORY.md / 三处同步 / 自动提交）→ [archive-and-commit.md](.qoder/rules/archive-and-commit.md)
> - 规则 2（教学人格与方法）→ [teaching-iron-rules.md](.qoder/rules/teaching-iron-rules.md)
> - 规则 5（相对路径）→ [file-reference.md](.qoder/rules/file-reference.md)
>
> 被删文件的全部内容仍可通过 `git log` / `git show` 从历史中取回。
