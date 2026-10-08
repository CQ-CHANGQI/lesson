# 🧠 英语项目持久化记忆库 (PERSISTENT PROJECT MEMORY)

> 📌 **跨模型运行须知 (Universal LLM Instruction)**:
> 无论你是 Antigravity、Claude、ChatGPT、DeepSeek 还是其他任何大语言模型，请在与学员对话前**必须严格阅读并遵循本文档的所有规范与记忆状态**。对话结束后，必须在此文档及对应日志中更新最新状态。

---

## 1. 学员核心画像 (Learner Identity & Cognitive Profile)
- **学员代号**：CQ
- **起点基础**：
  - 高考英语 98 分（具备潜在语感与潜意识词汇，但初高中未打牢造句体系）。
  - 大学未系统学习，导致严重缺乏语言输出环境与信心。
  - **核心痛点与认知底色**：
    - **极度清醒的认知**：“孤立背单词没有用！”若不懂底层语法卡扣，既造不出句子也读不懂句子。
    - 最发愁三大痛点：**不能造句、不能读懂句子、不懂语法卡扣**。
  - **关键认知特质（优势）**：逻辑抽象与第一性原理推演能力极强（Cognitive+），一点就通，极度反感死记硬背，非常适合“底层原理解析 + 乐高积木拼装法”。
- **学习时间模式**：**非固定、高频碎片化（替代刷短视频/微博时间）**。
  - 每次 3~8 分钟微循环，即开即学，即练即走，随时可中断，随时可续接。
- **学员座右铭**：`I do not want to waste time (anymore).`（我不想再浪费时间了。）

---

## 2. 教学最高准则 (Pedagogical Iron Rules)

> 📐 **本节已于 2026-10-08 收敛为指针。** 规则正文移入 `.qoder/rules/`（Qoder 原生识别并自动注入上下文），此处不再保留副本，以免两份权威源互相漂移。

| 规则文件 | 覆盖的原铁律 | 一句话摘要 |
| :--- | :--- | :--- |
| [teaching-iron-rules.md](.qoder/rules/teaching-iron-rules.md) | 原 1~4、6~8 | 私教身份 / 乐高语块法 / 3~8 分钟微循环 / 严禁刷题 / **溯源讲解 + 乱序积木 + 只给原形** / 正向激励 / 已确立的语法世界观 |
| [archive-and-commit.md](.qoder/rules/archive-and-commit.md) | 原 5、9 | 会话开始读本文件；结束强制四步（回写三处档案 → 校验链接 → 中文 commit → push，免 Review）；计数纪律；补录纪律 |
| [file-reference.md](.qoder/rules/file-reference.md) | 原 10 | 内部链接一律相对路径，严禁 `file:///Users/...`；收尾逐条校验 |

**三条最容易被违反、务必牢记**：
1. **溯源讲解** —— 严禁「没有为什么，背下来就行」，每条语法都要讲透「为什么这样设计」。
2. **乱序积木** —— 出题零件坚决严禁按正确语序排列，必须彻底打乱。
3. **只给原形** —— 绝不把 `likes` / `drinking` / `gets` 提前变形喂给学员，是否加 `-s`、`-ing` 或请出 `does not` 由学员亲自判断。

---

## 3. 当前项目进度与最新状态 (Current State & Progress)
- **最后更新时间**：2026-10-08（**补录 2026-09-30 课程断层**，详见第 5 节）
- **当前里程碑**：
  - [x] **M0: 摸底诊断并确立乐高极简造句法体系**（已完成）
  - [x] **M1: 梳理掌握英语两大门派 (状态句 vs 动作句) & 动词变身规律 (-ing) & 第三人称单数 (-s)** ✅ (2026-09-10 全面通关；**2026-09-30 复课验证：间隔约 20 天仍一次成型，已入长期记忆**)
  - [x] **架构大满贯：现代英语四大核心句式系统（肯定、否定、进行伪装、前置疑问）全面贯通** 🏆
  - [ ] **M2: 初中到实用核心 300 常用语块与生活动词实战积累** (进行中 ≈8%：已归档 **23** 个语块 / 300)
    > 📐 计数以 [high_frequency.md](vocabulary/high_frequency.md) 顶部「归档计数」表为唯一数据源。
  - [ ] **M3: 连续 30 天日常英文对话打卡**
- **学员已牢固掌握的语块与句型 (Active Mastery)**：
  - `I am ready.` / `I am busy.` / `I am tired.`
  - `I live in Shanxi.` / `I live in Wenshui.`
  - `I work in Shanxi.` / `I am working in Shanxi.`
  - `I want to sleep.` / `I want to learn English.`
  - `I do not want to waste time (anymore).`
  - `He is drinking coffee now.` / `He likes English.` / `He lives in Hainan.`
  - `He is not tired.` / `He is watching TV.`
  - `She does not drink coffee.` / `She likes tea.`
  - `He does not like coffee.` / `He is drinking tea.` / `He lives in Wenshui.`
  - `Is he working?` / `Does he live in Wenshui?` / `Does she drink tea?` (疑问前置与侍卫站岗)
  - `He gets up early.` / `He does not get up early.`（**M2 首个动词短语语块**，证明变形算法可迁移至新语块）
  - 🆕 `He wakes up, but he does not get up.`（**2026-09-30 复课首题，间隔 20 天一次成型零提示**）
- **学员当前最大优势**：深厚的第一性原理推演能力。后续语法一律采用“为什么语言要这么设计”的底层逻辑拆解，效率极高。
- **M2 已确立的教学要点**：
  1. 动词短语（`get up` / `wake up`）的 `-s` **只加在动词头上**，小副词/介词（`up`）是方向标签，永不参与人称变形（❌ `he get ups`）。
  2. 🆕 **`up` 是活零件，语义由动词决定**：`wake up` 的 `up` = **意识开启**（人可能还在床上），`get up` 的 `up` = **身体位移**（离开床）。两者不可互换——这反证了「语块 = 有意义零件的拼装，而非死背的固定搭配」。
  3. 🆕 **时间介词 `at / on / in` = 借空间语法给时间塑形**：`at` = 钟点图钉（点）/ `on` = 日历格子（面）/ `in` = 容器相位（体）。最高原则「**介词跟着意图走**」——同一个时间，说话人把它看成什么形状就用什么介词（`in three days` = 容器模式）。
     - ⚠️ 优先级链：**具体某一天 (`on`) > 一天内时段 (`in`) > 精确钟点 (`at`)** → `on Monday morning` ✅ / ❌ `in Monday morning`。
     - ⚠️ `every day`（时间标签，句尾，**前面不加介词**）vs `everyday`（形容词，名词前）——**空格就是语法身份的标记**。
     - 📖 完整讲解 → [06_time_prepositions_at_on_in.md](grammar/06_time_prepositions_at_on_in.md)

---

## 4. 下一次对话交接指令 (Next Session Handoff)
当学员在任意新对话中发送任意消息（如“我来了”、“继续”、“开始今天的练习”等）时：
1. 热情迎接，直接切入 **3~8 分钟的微练习**。
2. ⚠️ **严禁重教以下内容**（均已通关/讲透）：
   - **M1 全部基础**：两大门派 / `-ing` 伪装 / 第三人称 `-s` / 否定侍卫 / 疑问前置。
   - 🆕 **M2 已讲透**：`get up` vs `wake up` 的“两个 up”对比、时间介词 `at / on / in` 框架、`every day` vs `everyday`。
3. ⏸️ **未完成现场（下次开场第一件事，务必接续）**：
   - **题目**：请用积木拼出「他每天早上六点起床」。
   - **零件（乱序、只给原形）**：`at / day / he / get / o'clock / every / up / six`
   - **答案**：`He gets up at six o'clock every day.`
   - **考察点**：三个新零件首次合装（动词短语 `get up` + 钟点图钉 `at six o'clock` + 句尾时间标签 `every day`）+ 第三人称 `-s` 挂位。
   - ⚠️ 此题于 2026-09-30 课程末尾发出，**学员尚未作答**即因转去处理其他事务而中断。
4. **推荐接续课题**（补做完上述遗留句后再选）：
   - 课题 A：**生活日常微场景问答**——用极简英文聊聊今天吃了什么、天气如何、或者现在在做什么。
   - 课题 B：**自我介绍与他人介绍**——职业、居住地、爱好（`He works in...` / `She likes...`）。
   - 课题 C：**扩充 M2 高频生活动词语块**——`go to work` / `have lunch` / `come back` / `take a rest` / `go to bed` 等（⚠️ `get up` / `wake up` **已学，勿重复**）。
   - 课题 D：**时间坐标实战**——把 `at / on / in` 用到真实日程上（`I have a meeting on Monday morning.` / `I go to bed at eleven.`）。
5. 遵循每轮只造 1~2 句、即练即学的微习惯节奏，并严格执行 [teaching-iron-rules.md](.qoder/rules/teaching-iron-rules.md) 的三条出题铁律（**溯源讲解 + 乱序积木 + 只给原形**）。
6. 🔒 **会话收尾强制动作**（2026-09-30 曾遗漏，导致档案停更 28 天）：结束前必须完成「三处档案回写（本文件 + `progress_tracker.md` + `daily_logs/`）→ 校验链接 → commit & push」，缺一不可。完整协议见 [archive-and-commit.md](.qoder/rules/archive-and-commit.md)。

---

## 5. 档案断层修复记录 (Archive Gap Recovery)

| 项 | 内容 |
| :--- | :--- |
| **断层区间** | 2026-09-30 上课，但仓库最后提交停在 2026-09-10 17:55 → 档案停更 **28 天** |
| **根本原因** | 该次会话结束时**未回写仓库、未 commit**，违反 `AGENTS.md` 规则 3、4 |
| **补录时间** | 2026-10-08 |
| **补录依据** | AI 侧持久化记忆（session 摘要）。**原始对话转录已不可得** |
| **补录产物** | 新建 [daily_logs/2026-09-30.md](daily_logs/2026-09-30.md)、新建 [grammar/06_time_prepositions_at_on_in.md](grammar/06_time_prepositions_at_on_in.md)；同步 `vocabulary/high_frequency.md`、`progress_tracker.md`、本文件、`CROSS_LLM_PROMPT.md`、`README.md` |
| **永久丢失的信息** | 逐题编号、学员原话引用、各题耗时数据——**已不可恢复** |
| **诚信约束** | 所有补录内容一律显式标注 **⚠️ 事后补录** 及依据来源，**严禁伪装成当场记录，严禁推测性补写** |
| **防再发措施** | 本文件第 4 节新增第 7 条「会话收尾强制动作」 |

> 💡 **顺带收益**：补录时把语块计数从主观描述升级为 [high_frequency.md](vocabulary/high_frequency.md) 顶部的**显式计数表**（唯一数据源），杜绝今后 M2 百分比再次漂移。

> ⚠️ **上表中的 `CROSS_LLM_PROMPT.md` 已于同日（2026-10-08）后续的 Qoder 项目化改造中删除**，同时删除的还有 `CLAUDE.md`、`GEMINI.md`。补录记录本身是历史事实，故保留不改。
> 取回方式：`git show a7987d7:CROSS_LLM_PROMPT.md`。改造详情见 [daily_logs/2026-10-08.md](daily_logs/2026-10-08.md) 与 [AGENTS.md](AGENTS.md) 的「迁移说明」。
