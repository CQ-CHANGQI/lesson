# 🌟 英语重启进阶计划 (English Reboot & Mastery Project)

欢迎开启你的系统化英语学习之旅！本项目旨在将英语学习转化为一个长期的、可量化、可持续且有反馈的工程。

---

## 📌 项目定位与愿景
- **学习者**：CQ (Lifelong Learner)
- **起点基础**：高考英语 98分（具备潜意识词汇与基础语感，大学阶段输入较少，需系统重构体系）
- **核心理念**：
  1. **刻意输入 + 真实输出 (Comprehensible Input + Real Output)**：拒绝死记硬背，结合语境与实用表达。
  2. **每日微习惯 (Atomic Habits)**：每天保持高频互动、对话演练与知识沉淀。
  3. **数据化追踪 (Tracking & Accountability)**：所有生词、语法短板、日常对话与纠错实时归档。
  4. **语法设计溯源 (Design Rationale First)**：不讲“背下来就行”，只讲“语言为什么这样设计”。

---

## 📂 项目目录架构

```text
/Users/changqi/lesson/
├── MEMORY.md               # ⭐ 跨模型持久化记忆库（任何 AI 必读的第一份文件）
├── AGENTS.md               # AI Agent 工作协议（通用入口）
├── CLAUDE.md               # Claude Code 入口协议
├── GEMINI.md               # Gemini 入口协议
├── CROSS_LLM_PROMPT.md     # 📱 手机端/网页端一键接力 Prompt（复制即用）
├── README.md               # 项目主页与核心方法论（当前文件）
├── learner_profile.md      # 个人学习画像与能力雷达
├── study_plan.md           # 分阶段长远学习规划与每日执行规程
├── progress_tracker.md     # 学习进度看板、每日打卡记录与里程碑
├── assessments/            # 阶段性水平测评档案
│   └── 01_diagnostic_test.md  # 初始摸底测试（已归档，仅作历史留档）
├── vocabulary/             # 个人高频核心词库与高频易错词库
│   ├── README.md
│   └── high_frequency.md   # 黄金语块归档
├── grammar/                # 骨架语法精讲（乐高体系）
│   ├── README.md
│   ├── 00_verb_transformation_cheatsheet.md   # 动词变形速查卡
│   ├── 01_sentence_lego.md                    # 两大门派
│   ├── 02_the_secret_of_ing.md                # -ing 变身术
│   ├── 03_third_person_and_s.md               # 第三人称 -s
│   ├── 04_negation_and_helper_verbs.md        # 否定与助动词
│   └── 05_questions_and_inversion.md          # 疑问与倒装
└── daily_logs/             # 每日互动复盘、对话练习与纠错记录
    ├── README.md
    └── 2026-09-10.md
```

---

## 🔄 每日协作模式
1. **Daily Check-in (每日互动对话)**：用英语进行 **3~8 分钟**日常话题或工作学习交流（碎片化，替代刷短视频）。
2. **Real-time Feedback (实时精修纠错)**：分析表达中的语法错误、用词不地道处，提供地道替换句型。
3. **Knowledge Logging (沉淀归档)**：自动将今日新学词汇、重点句型存入对应目录。
4. **Milestone Review (阶段性复盘)**：每阶段进行能力测试与计划动态调优。

---

## 📖 新人/新 AI 接入顺序
1. 先读 `MEMORY.md`（当前进度与教学铁律）
2. 再读 `learner_profile.md`（学员画像与能力雷达）
3. 需要出题时，严格遵循 `MEMORY.md` 第 2 节的全部准则（**溯源讲解 + 乱序积木 + 只给原形**）
4. 会话结束：更新 `MEMORY.md` + `progress_tracker.md` + `daily_logs/YYYY-MM-DD.md`，随后**自动 commit & push**（中文提交信息）
5. **文件引用一律使用相对路径**，严禁 `file:///Users/...` 绝对路径（详见 `AGENTS.md` 规则 5）
