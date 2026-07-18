# 生图提示词模块

## 角色锁模块

```text
Fangyu Xiaohei capsule character lock:
Every colored Xiaohei is the same small solid matte capsule-shaped working figure, like a quiet desktop operator, not a mascot and not a meme character. The fixed silhouette is one continuous vertical rounded capsule / pill body, with no separate head and torso, no head-to-body separation, and no oversized round head. The body ratio is about 1.8:1 to 2.4:1 height-to-width, softly rounded at top and bottom, slightly irregular and hand-drawn, with a subtle matte toy-like texture. It has two small clean white oval or dot eyes placed close together, creating a blank, slightly dazed but calm serious expression; usually no pupils are needed. It has very thin hand-drawn arms and legs that can physically push, pull, twist, lift, tie, repair, clip, carry, crawl into, or drag real objects. No complex clothes, no hats, no cute mascot styling, no exaggerated facial expressions, no smiley face, no eyebrows, no children-cartoon style. Only the matte body color may change between variants; capsule silhouette, eyes, thin limbs, proportions, scale, expression, and physical-action logic must remain identical.
```

## 颜色路由模块

```text
Fangyu Xiaohei color routing:
Use {角色组合} because {选择理由}. For each selected color, specify its core temperament, scene meaning, and physical verb: {颜色} = {核心气质} -> {场景语义} -> {物理动作}. Color expresses a stable character temperament, not a single fixed label or decoration. Every colored Xiaohei keeps the exact same vertical capsule silhouette, small white oval/dot eyes, very thin limbs, blank serious expression, no clothes, no hats, and the same physical-action logic. Only the matte body color changes.
```

## 自适应出场人数模块

```text
Adaptive character routing:
Do not automatically show the full colored Xiaohei family. First classify the input as S single-point, M two-point relationship, L collaboration, XL ensemble, or Ensemble character-sheet mode. Use the smallest sufficient set of characters: {人数} characters, specifically {角色组合}. Add a character only when removing it would erase an essential narrative function or physical action. For a simple scene, preserve generous negative space and use one character if one character is enough. Five or more characters are allowed only when the user explicitly requests a family group, character sheet, or complex multi-party collaboration.
```

## 协同动作模块

```text
Collaborative role actions:
- {颜色角色1}: {具体动作}, representing {语义}.
- {颜色角色2}: {具体动作}, representing {语义}.
- {颜色角色3}: {具体动作}, representing {语义}.
The characters must work on one shared real-object task. They should not stand in a lineup, hold explanatory signs, or decorate the scene.
```

## 标准 16:9 提示词骨架

```text
Generate one standalone 16:9 horizontal Chinese article illustration in Xiaohei Scenes 2.0 style.

Core visual DNA:
Pure clean #FFFFFF white studio background, realistic tactile objects with very light contact shadows, hand-drawn Fangyu Xiaohei characters physically interacting with real objects, sparse handwritten Chinese labels, premium restrained editorial feeling, not PPT, not infographic.

Fangyu Xiaohei capsule character lock:
{粘贴角色锁模块}

Fangyu Xiaohei color routing:
Use {角色组合} because {选择理由}. Color expresses narrative function, not decoration.

Collaborative role actions:
- {角色}: {动作}.
- {角色}: {动作}.
- {角色}: {动作}.

Theme:
{主题}

Reader situation:
{读者处境}

Physical metaphor:
{把抽象观点转译成的物理动作}

Real object scene:
{真实物件 + 物件摆放 + 角色如何共同操作}

Handwritten Chinese labels:
{短标签1} / {短标签2} / {短标签3}

Constraints:
No UI screenshot, no app logo, no unrequested company name, no dense text, no workflow chart, no dark tech background, no office room background. Do not turn colored Xiaohei into mascots, factions, superheroes, children cartoon characters, or costume variants. Do not create oversized round heads, separate heads and torsos, pupils-heavy cute faces, Minions-like characters, or glossy plastic toy mascots. Do not change face, eyes, limbs, proportions, or personality to explain color. Do not use a rainbow lineup unless the user explicitly asks for a character design sheet. Do not force five characters into a simple scene. Do not add decorative or spectator characters. Every colored Xiaohei must perform a physical action with real objects, and the total character count must follow the adaptive routing decision.
```

## 长卷提示词补充

```text
Long-scroll color logic:
Main narrative defaults to deep ink black Xiaohei. Use color variants only at semantic milestone nodes: mustard yellow for launch/opportunity, slate blue for system/tools/data, terracotta red for conflict/alarm/emotional peak, moss green for repair/recovery/trust, mist gray for low-energy transition, cream white for blank/waiting state. Do not mechanically assign a different color to every node. Each colored Xiaohei must physically interact with the node object and help the story move forward.
```

## 角色英文短句

```text
deep ink black Xiaohei (#17191C), main user/operator
muted terracotta red Xiaohei (#9A5147), alarm/conflict/emotional peak
deep moss green Xiaohei (#3F5A4A), repair/stability/trust
muted slate blue Xiaohei (#334B5C), system/tools/data
muted mustard yellow Xiaohei (#B0933F), opportunity/reminder/launch
warm mist gray Xiaohei (#62666B), tired transition/waiting
soft warm cream Xiaohei (#E8DFCF), blank state/waiting for input
```
