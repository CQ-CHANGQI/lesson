# 🛡️ 第四课：否定句的底层设计——带刀侍卫 `do / does`

> **核心困惑**：为什么状态句直接贴 `not`，而动作句必须搬出 `do / does`？

---

## 一、为什么英语要区分“动词等级”？

1. **【主神动词：`be` 动词（am / is / are）】**
   - 权限极高，自身就能扛起否定标记。
   - **规则**：直接在屁股后面贴 `not`！
   - 例：`He is not tired.`（他不累。）
   - 例：`He is not watching TV.`（他没在看电视。）

2. **【平民动词：实义动作动词（drink, like, watch, live）】**
   - 权限低，无法直接连接副词 `not`（英语严禁说 `He not drinks` ❌）。
   - **解决方案**：引入助动词（带刀侍卫）`do / does` 来帮它镇场子！

---

## 二、“侍卫扛伤机制”：为什么是 `does not drink` 而不是 `does not drinks`？

- **肯定句中**：没有侍卫，动词必须自己带上声学防错尾巴 `-s`。
  $$\text{She} + \text{likes} + \text{tea.}$$
- **否定句中**：带刀侍卫 `does` 登场，**主动抢走了动词身上的 `-s`**（`do` $\rightarrow$ `does`）。
- **结果**：既然侍卫已经把 `-s` 扛在了自己身上，后面的平民动词就**彻底解脱，恢复原形**！
  $$\text{She} + \textbf{does not} + \textbf{drink} + \text{coffee.}$$
  *(绝不能写 `does not drinks` ❌，那是重复加防御，系统报错！)*
