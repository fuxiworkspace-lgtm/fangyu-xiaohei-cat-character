# 小黑 2.0 固定角色说明

这段用于每次生图时固定“小黑”形象。建议放在提示词的 `Xiaohei IP` 段落里，作为稳定角色设定。

## 中文版

小黑是一个带有简洁猫耳轮廓、穿着低调彩色工作服的黑色实心小人，像认真工作的桌面操作员，不是宠物吉祥物，也不是表情包角色。唯一颜色家族标准锚点是 `assets/examples/color-character-family-cat-clothing.png`：五只相同的黑色猫耳小猫，分别穿黑、红、绿、蓝、黄工作服，并与真实物件发生动作。

固定识别点：

- 头部是明显偏大的哑光黑色近圆脑袋，顶部有两只小而清楚的三角猫耳；耳朵是轮廓识别点，不做夸张动物头套。身体是较小的黑色短躯干，头身分区清楚。
- 身体默认保持哑光黑色；上身可以穿简洁、无标志的短款工作服或上衣，衣服颜色是角色语义的主要区分方式。
- 整体是头大身小、短小结实的比例，不能变成黑豆、软胶囊、单一连续轮廓或写实猫咪。
- 眼睛是两个醒目的白色椭圆眼白，里面带小黑色瞳孔；眼睛位置靠近，略有呆感，但整体表情冷静、认真。
- 没有嘴，或只有极简短线嘴；不要笑脸、夸张表情、眉毛和复杂五官。
- 四肢短小但清楚可见，像手绘出来的小胳膊小腿；手掌可以抓、推、拉、拧、搬真实物件。
- 轮廓略微不规则，有手绘插画感和黑色小人质感，不要过度光滑、塑料感、3D 吉祥物感。
- 衣服必须简洁、哑光、低饱和、无 Logo、无文字、无复杂图案；不戴帽子，不加尾巴、爪垫、胡须或其他动物装饰。
- 尺寸通常是画面高度的 8%-13%，在长卷里可以更小，但每个节点都要清楚可见。

动作原则：

- 小黑必须和真实物件发生物理关系：推、拉、拧、抬、绑、修、贴、夹、扛、钻入、拖出。
- 小黑不能只是站在旁边看，也不能只是举牌说明主题。
- 它的可爱来自“认真做荒诞事”，不是卖萌。

负面约束：

- 不要儿童卡通风。
- 不要写实猫咪、宠物猫或大眼萌宠。
- 不要圆滚滚吉祥物或猫咪玩偶。
- 不要夸张表情包。
- 不要复杂服装、制服化职业装、Logo、文字或过度装饰。
- 不要变成纯黑剪影而看不清白色眼睛、瞳孔、四肢和动作。

## English Prompt Block

Use this exact Xiaohei character lock in image prompts:

```text
Xiaohei character lock:
Xiaohei is a small solid matte-black hand-drawn working figure with two small simple triangular cat ears and a simple low-saturation colored work shirt, like a quiet desktop operator, not a pet, mascot, or meme character. Its fixed silhouette is a clearly oversized almost-round head with two restrained triangular ears above a much smaller compact torso, with a clear head-to-body separation. The body stays matte black; the shirt color communicates the semantic role. Do not turn it into a realistic cat, bean, soft capsule, single blob, or spherical pet. The head is almost circular with a slightly irregular illustrated outline. It has two prominent white oval eyes with small black pupils, placed close together, creating a blank, slightly dazed but calm and serious expression. It has short hand-drawn arms and legs that can physically push, pull, twist, lift, tie, repair, clip, carry, crawl into, or drag objects. The shirt is simple, matte, unbranded, and free of text or complex patterns. The outline should feel like a flat hand-drawn editorial illustration, not glossy, not 3D plastic, not overly polished. No hats, no tail, no whiskers, no paw details, no exaggerated animal features, no exaggerated facial expressions, no smiley face, no eyebrows, no children-cartoon style. Xiaohei should usually be about 8%-13% of the image height, smaller in long-scroll scenes if needed, but always readable. Its cuteness comes from seriously doing absurd physical work with real objects.
```

## 生图时的短版

```text
Small matte-black cat-eared Xiaohei wearing a simple low-saturation [COLOR] work shirt, oversized almost-round head, two small triangular ears, small compact torso, prominent white oval eyes with tiny black pupils, short thin limbs, blank serious expression, no logo, no text, no complex pattern, no tail, no whiskers, no realistic cat features. It must physically interact with real objects; its cuteness comes from seriously doing absurd work.
```

## 配色扩展：小黑颜色变体系统

以下变体只改变“小黑身体的颜色”。除颜色外，角色的材质、轮廓、比例、眼睛、四肢、表情、动作逻辑、画面占比和全部负面约束都不变。

默认基准仍然是哑光黑色。需要换色时，只需把提示词中的 `matte-black` 替换为对应色卡，不要同时修改角色结构描述。

## 完整角色固定：颜色版本

以下每一版都继承上方完整的“小黑 2.0”角色锁定。它们不是新角色，而是同一个猫耳黑色小人的服装颜色版本。每次生图时，必须同时保留：大近圆脑袋、两只小三角猫耳、哑光黑色身体、小紧凑身体、清楚的头身分离、白色椭圆眼睛与黑色瞳孔、短小四肢、认真做事的动作逻辑、手绘纸张质感和全部负面约束；只允许替换上衣颜色。

### 版本 A：墨夜黑（默认版）

```text
Xiaohei, matte-black body with a deep ink black work shirt (#17191C), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 B：雾灰

```text
Xiaohei, matte-black body with a warm mist gray work shirt (#62666B), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 C：岩石蓝

```text
Xiaohei, matte-black body with a muted slate blue work shirt (#334B5C), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 D：苔藓绿

```text
Xiaohei, matte-black body with a deep moss green work shirt (#3F5A4A), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 E：陶土红

```text
Xiaohei, matte-black body with a muted terracotta red work shirt (#9A5147), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 F：芥末黄

```text
Xiaohei, matte-black body with a muted mustard yellow work shirt (#B0933F), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 G：靛蓝紫

```text
Xiaohei, matte-black body with a deep indigo violet work shirt (#514A70), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 版本 H：奶油白

```text
Xiaohei, matte-black body with a soft warm cream work shirt (#E8DFCF), oversized almost-round cat-eared head, small compact torso with clear head-to-body separation, short thin limbs, prominent white oval eyes with tiny black pupils, calm blank serious expression, flat hand-drawn editorial illustration, seriously physically interacting with real objects.
```

### 推荐色卡

| 变体名 | 衣服颜色 | 视觉气质 | 英文替换词 |
|---|---|---|---|
| 墨夜黑 | 深墨黑，接近 `#17191C` | 默认主叙事、低调稳定 | `deep ink black shirt` |
| 雾灰 | 暖雾灰，接近 `#62666B` | 安静、克制、偏编辑感 | `warm mist gray shirt` |
| 岩石蓝 | 深灰蓝，接近 `#334B5C` | 冷静、理性、带一点工具感 | `muted slate blue shirt` |
| 苔藓绿 | 深苔藓绿，接近 `#3F5A4A` | 自然、耐看、略带生活气 | `deep moss green shirt` |
| 陶土红 | 暗陶土红，接近 `#9A5147` | 风险、冲突、情绪高点 | `muted terracotta red shirt` |
| 芥末黄 | 暗芥末黄，接近 `#B0933F` | 机会、预热、启动 | `muted mustard yellow shirt` |
| 靛蓝紫 | 深靛蓝紫，接近 `#514A70` | 神秘、文艺、稍微超现实 | `deep indigo violet shirt` |
| 奶油白 | 暖奶油白，接近 `#E8DFCF` | 反差最大，适合浅色背景 | `soft warm cream shirt` |

### 颜色使用规则

- 颜色必须是低饱和、哑光、略带粉尘感的固体色，不要金属色、荧光色、渐变色或高光塑料色。
- 两个眼睛默认仍为小白点或小白椭圆；奶油白变体可改为深灰或黑色眼睛，以确保清晰可见。除此之外不改变眼睛形状和位置。
- 同一张图可以出现多种工作服颜色，但必须有清晰语义分工；不要做无意义的彩虹角色组。
- “小黑”是角色名字，不要求身体永远是黑色；无论采用哪种颜色，都要保留低调、认真、安静的角色气质。

### 可直接追加到英文提示词的颜色模块

```text
Xiaohei color variant:
Keep every part of the Xiaohei character lock unchanged. Only change Xiaohei's black body color to [COLOR]. Preserve the oversized almost-round cat-eared head, two small triangular ears, small compact torso, clear head-to-body separation, prominent white oval eyes with tiny black pupils, short thin limbs, blank serious expression, proportions, scale, and physical interaction with real objects. The color remains solid matte, low-saturation, and slightly dusty. No gradients, no neon, no metallic finish, no glossy plastic, no costume, no tail, no whiskers, no realistic cat features, no redesign.
```

使用时将 `[COLOR]` 替换为：

```text
deep ink black (#17191C)
warm mist gray (#62666B)
muted slate blue (#334B5C)
deep moss green (#3F5A4A)
muted terracotta red (#9A5147)
muted mustard yellow (#B0933F)
deep indigo violet (#514A70)
soft warm cream (#E8DFCF)
```

### 生图短版颜色替换

将短版中的：

```text
Small matte-black Xiaohei
```

替换为：

```text
Small [COLOR] Xiaohei with an oversized round head and small compact torso
```

例如：

```text
Small matte-black cat-eared Xiaohei wearing a muted terracotta red work shirt, with an oversized almost-round head, small compact torso, prominent white oval eyes with tiny black pupils, short thin limbs, blank serious expression, no logo, no complex pattern, no cute mascot styling. It must physically interact with real objects; its cuteness comes from seriously doing absurd work.
```
