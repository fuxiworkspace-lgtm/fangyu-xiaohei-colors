---
name: fangyu-xiaohei-colors
description: |
  房语彩色小黑角色协同系统。Use when the user wants to generate, design, refine, or route colored Xiaohei characters for Chinese article illustrations, Xiaohei 2.0 scenes, real-object metaphor images, long-scroll story images, or character design sheets. Trigger on 彩色小黑, 房语小黑, 小黑颜色, 小红小绿小蓝小黄, 颜色分身, 角色分工, 角色协同, 小黑家族, Xiaohei colors, or when content needs Xiaohei variants to express alarm, repair, system, opportunity, trust, conflict, growth, workflow, or team collaboration. This skill fixes the colored Xiaohei IP, assigns semantic roles by input scene, and composes multiple colored Xiaohei figures into coordinated physical actions while preserving the original Xiaohei silhouette and Xiaohei 2.0 real-object style.
---

# 房语彩色小黑角色协同系统

## 核心定位

彩色小黑不是“把小黑涂成不同颜色”，也不是一组新的吉祥物。

它是一套小黑角色协同系统：颜色让几个小人之间出现了工作分配，角色体之间有了协同关系，也让原本单一的小黑形象拥有更传神、更有人格饱满度的表达。

核心公式：

```text
同一形体 + 不同身体颜色 + 明确角色分工 + 真实物件协同动作
```

始终保留小黑的本体识别：竖向胶囊身体、一体化圆角轮廓、白色小椭圆眼、极细四肢、冷静认真、低调笨拙、认真做荒诞事。颜色只改变身体色，不改变角色结构。

## Before Starting

按需读取：

- `references/character-lock.md`：房语小黑固定形体，所有颜色角色必须继承。
- `references/role-system.md`：颜色角色、语义路由、协同组合和场景判断。
- `references/prompt-blocks.md`：可直接用于生图提示词的角色锁、颜色路由和协同动作模块。
- `references/qa-checklist.md`：生成前后检查，防止变成彩虹吉祥物或无意义装饰。
- `assets/examples/`：彩色小黑家族和协同场景参考图，只作为质量锚点，不机械复刻。

如果用户同时要求“小黑 2.0 / 真实物件 / 长卷故事图 / 正文配图”，应结合原有 Xiaohei Scenes 2.0 工作流：先做内容提炼、母版锁定、真实物件隐喻，再用本 skill 做颜色角色路由和协同动作设计。

## Core Flow

### 1. 提炼输入场景

先判断内容里真正需要谁出场：

- 谁是主叙事角色？
- 谁在推动系统、工具、数据或流程？
- 谁代表风险、冲突、警报或情绪高点？
- 谁负责修复、稳定、信任、恢复或连接？
- 谁代表机会、提醒、启动、点亮或灵感？
- 这些角色之间是否真的需要协同，还是一个默认小黑就够？

不要为了颜色丰富而增加角色。颜色必须让画面更容易 3 秒读懂。

### 2. 选择颜色角色

默认只用小黑。只有内容出现明确的语义分工，才引入彩色角色。

基本角色：

- 小黑：主叙事、普通用户、默认行动者、复杂长卷主线。
- 小红：警报、冲突、风险、商战、情绪峰值、中国股市红涨。
- 小绿：修复、恢复、通过、稳定、信任、连接、中国股市绿跌。
- 小蓝：系统、工具、代码、数据、AI 工作流、理性操作。
- 小黄：机会、提醒、预热、启动、点亮、灵感。
- 小灰：疲惫、过渡、低能量、等待、模糊状态。
- 小白：空状态、纯净、未开始、等待确认、留白角色。

完成标记：

```text
角色颜色：
选择理由：
每个角色的工作：
角色之间如何协同：
不用哪些颜色以及为什么：
```

### 3. 设计协同动作

彩色小黑最有价值的地方，是让角色在同一个真实物件现场里分工合作。

优先设计这些关系：

- 接力：小黄点亮，小蓝接入，小黑推进，小绿收束。
- 拉扯：小红制造压力，小黑被拉住，小绿修复断点。
- 系统协作：小蓝调参，小黑搬任务，小绿确认稳定。
- 商战场景：小红拉警报线，小蓝拧额度旋钮，小黑试图继续工作。
- 成长长卷：小黑贯穿主线，关键节点用小黄启动、小蓝系统化、小红冲突、小绿修复。

每个角色都必须和真实物件发生物理关系：推、拉、拧、接、托、修、夹、绑、抬、递、点亮、稳住、拖出。

失败动作：

- 几个彩色小黑排排站。
- 每个颜色举一个牌子解释自己。
- 彩色角色只是围观。
- 换色但动作没有分工。
- 颜色角色之间没有共同任务。

### 4. 输出 Shot List

如果用户要方案，按这个格式输出：

```text
主题：
核心场景：
读者共鸣点：
真实主物件：
角色颜色：
选择理由：
每个角色的动作：
协同关系：
短中文标签：
画面 3 秒读懂句：
颜色负面约束：
```

如果用户明确要“生成 / 出图 / 看看效果”，可以直接进入生图提示词，但必须在内部完成以上判断。

### 5. 生成提示词

提示词必须包含：

- 角色形体锁：同一竖向胶囊身体、一体化圆角轮廓、白色小椭圆眼、极细四肢、无衣服无帽子。
- 颜色路由：为什么使用这些颜色。
- 协同动作：每个角色具体正在做什么。
- 真实物件：角色和物件发生什么物理关系。
- 颜色负面约束：只改变身体颜色，不改变五官、服装、性格和比例。

直接复用 `references/prompt-blocks.md` 中的模块。

### 6. QA

交付前读取或检查 `references/qa-checklist.md`。关键问题：

- 颜色是否来自输入语义？
- 每个颜色角色是否有独立工作？
- 角色之间是否真的协同？
- 是否仍然是同一个房语小黑 IP？
- 是否保持 Xiaohei 2.0 的真实物件、物理动作和留白叙事？

如果不通过，优先删减颜色角色，而不是继续增加解释。

## Output Style

给用户的解释保持短而准。重点说清：

- 用了哪些颜色角色；
- 为什么这样分工；
- 这些角色如何协同；
- 图片文件路径或可复制提示词。

不要把理论讲成长篇。让小黑们先干活。
