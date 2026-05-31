# 提示词构建方法论与万能公式

> 知识蒸馏来源：AI绘画提示词知识库（10篇核心文章）
> 蒸馏日期：2025年
> 作者：莫名智绘、一泽Eze、AI增效手册等

---

## 1. 核心构建法则

### 1.1 句子优先法（Sentence-First Method）

#### 核心法则

**一张图 = 一个句子。** 不是一个段落，不是一堆词汇堆砌，也不是视觉意图的商品目录。

"句子优先法"的起点不是干瘪的关键词，而是一个完整的视觉构思。这个句子应当已经包含了四要素，它读起来应该像是一句你能自然说出口的话，而不是在搜索引擎里敲下的冰冷词条。

**为什么这能改变一切？** 因为一个句子天然携带着：
- **层级感**（什么是最重要的）
- **连贯性**（万物融合为一）
- **意图**（它暗示着一个故事）

Midjourney 并不害怕复杂，它害怕的是矛盾。一个完整的句子能够彻底消除这种矛盾。

#### 四要素（核心句必须包含）

| 要素 | 说明 | 示例 |
|------|------|------|
| **主体 (Subject)** | 谁/什么是画面核心 | A lone deer |
| **动作或状态 (Action/State)** | 主体在做什么/处于什么状态 | standing |
| **背景环境 (Background)** | 在哪里 | in a foggy forest |
| **情感方向 (Emotion)** | 画面传递的情绪基调 | at dawn (静谧/希望) |

**错误写法（词汇堆砌）：**
> cinematic lighting, ultra detailed, 8k, forest, fog, dramatic sky, mystical, volumetric light

**正确写法（句子优先）：**
> A lone deer standing in a foggy forest at dawn

#### 三个受控修饰图层

一旦核心句确定，通过三个受控图层延伸：

**1. 视觉精度（镜头看到了什么）**
- 构图取景、镜头、距离、景深
- → 这是摄影逻辑介入的地方

**2. 光影语法（什么赋予了情感）**
- 一天中的时间、光线方向、对比度、氛围
- → 光影不是装饰品，它是画面的情感引擎

**3. 材质与纹理（什么让它变得真实）**
- 表面特性、纹理质感、物理属性表现
- → 这是让图像扎根于现实的基础

#### 操作步骤

```
Step 1: 构思核心句（包含四要素）
Step 2: 添加视觉精度（镜头逻辑）
Step 3: 添加光影语法（情感引擎）
Step 4: 添加材质精度（真实感基础）
Step 5: 做减法——删除无法强化核心句的元素
Step 6: 添加参数（--ar, --v, --style等）
```

#### 大师级提示词结构

```
[Sentence], [camera logic], [light grammar], [material precision] --ar [ratio] [other parameters]
```

**实战示例：**
> A child standing alone in a vast wheat field under a silent sky, eye-level framing, 50mm lens, shallow depth of field, soft evening light grazing the field, warm golden tones, gentle wind movement in the wheat --ar 16:9 --v 7 --style raw --s 200

> An abandoned house slowly being reclaimed by the forest, medium distance framing, 24mm lens, deep focus, soft overcast light, moss covering wood surfaces, muted earthy palette --ar 16:9 --v 7 --style raw --s 250

> A woman sitting by a window watching the rain fall, intimate indoor framing, 50mm lens, shallow depth, natural window light, soft shadows, textured glass with raindrops --ar 4:5 --v 7 --style raw --s 150

> A fisherman alone on a misty lake at dawn, wide composition, 85mm lens compression, dense fog atmosphere, diffused soft light, still water surface like glass --ar 16:9 --v 7 --style raw --s 200

> A cat sitting quietly on a windowsill overlooking a snowy city, medium framing, 50mm lens, shallow depth, cold blue ambient light, soft snow falling outside --ar 4:5 --v 7 --style raw --s 200

---

### 1.2 细节悖论

#### 核心机制

**在 MidJourney 中，增加越多细节，得到的反而越少。** 

MidJourney 并不会把你输入的提示词当成一个故事来理解，它将其视为一个**相互竞争的信号场**。每一个名词、形容词、风格参考、光影指令都被放在天平上衡量。当一切都显得重要时，就意味着没有什么是主导。

**过量细节的典型特征：**
- 多个权重相等的物体
- 相互矛盾的光影指令
- 过多风格的强行叠加
- 过度描述的材质
- 情绪词指向完全相反的方向

**错误示例（超载提示词）：**
> A cinematic portrait of a woman standing in a misty forest at night, surrounded by glowing flowers, birds flying around her, a distant futuristic city in the background, dramatic moonlight, neon rim light, candlelight glow, hyper-detailed textures, ultra-realistic skin, fantasy illustration style, oil painting texture, photorealistic lighting, surreal dream atmosphere, shot on a Canon EOS R5, 35mm lens, f/1.4, volumetric fog, magical realism, ethereal mood --ar 4:5 --raw

→ **失败原因：** 没有清晰的主体层级、光源相互矛盾、风格竞争而非相辅相成、观者眼睛不知道该落在哪里。

#### 减法的艺术

细节本身不是敌人，**失去次序的细节**才是。MidJourney 需要知道：
- 什么是主要的
- 什么是次要的
- 什么必须消融在静默中

**要像画家一样思考，而不是像收藏家那样贪婪。**

**受控细节版（相同构思，精简版）：**
> A solitary woman standing in the foreground of a misty forest at night, her face softly illuminated by a single moonlit rim light, background trees dissolving into deep blue haze, subtle fog drifting at ground level, muted color palette with restrained highlights, cinematic portrait photography, shot on Canon EOS R5, 85mm lens, f/1.8, shallow depth of field, low visual noise, quiet atmosphere --ar 4:5 --raw

→ **改变了什么：** 单一主体、单一主导光源、背景简化为意向性的暗示、更少形容词更强烈信号。

#### 统治句法则

如果你无法用一句干练的话描述你的画面，MidJourney 同样也做不到。在输入提示词之前，问自己：**"这个画面在视觉上是关于什么的？"**

**编写"统治句"**——你的意图变成了视觉法则。

**示例：**
> 统治句：「暴风雨中，一座孤独的灯塔矗立在岩石悬崖上。」
> 
> 这个句子已包含：一个主体、一个冲突、一个主导光源、一个情感轴心
>
> 扩展提示词：
> A lone lighthouse standing on a rocky cliff during a violent storm, powerful beam of light cutting through rain and darkness, ocean reduced to abstract motion below, dark muted color palette with one bright focal light, cinematic wide shot, shot on full-frame camera, 50mm lens, f/4, strong contrast, minimal secondary detail

**注意：** 没有装饰性的冗余，每一个细节都在强化那个"统治句"。

#### 层级化细节筛选框架

在构建好提示词后，请逐一审视每个元素，问自己三个问题：

| 问题 | 含义 | 操作 |
|------|------|------|
| 这个词是改变了图像，还是仅仅在装饰它？ | 是否对核心表达有实质贡献 | 装饰性则删 |
| 这个元素是强化了核心句，还是稀释了它？ | 是否与统治句一致 | 稀释则删 |
| 如果我删掉它，画面会变得更清晰吗？ | 是否制造了视觉噪音 | 更清晰则删 |

#### 留白即设计（Libée Lune 原则）

最顶级的 MidJourney 作品往往不是最喧闹的，它们是最安静的。它们留出空间、允许呼吸、信任缺失。**静默并非空洞，而是被保护的焦点。**

**极简力量示例：**
> An abandoned wooden chair standing alone in a foggy field, muted tones and diffused light, the horizon barely visible, minimalist landscape photography, shot on full-frame camera, 85mm lens, f/4 --ar 16:9

> A solitary figure walking through tall grass, face unseen, soft backlight separating the body from the field, cinematic natural light photography, shot on 85mm lens, f/2.8 --ar 16:9

> A single streetlamp standing in heavy rain, water streaks visible in the light cone, surroundings completely dark, cinematic night photography, shot on 50mm lens, f/1.8 --ar 9:16

---

### 1.3 5词定意法

#### 核心原理

MidJourney 是按层级构建图像的。当你的意图不明确时，模型会试图同时满足所有要求：主体、情绪、风格、象征意义、装饰——结果是一种"美丽的混乱"。

**五个单词迫使你做出选择。不是解释，不是装饰，而是选择。**

一个"五词意图"必须定义：
1. **主要主体**（谁/什么是核心）
2. **情感走向**（什么情绪）
3. **场景的视觉角色**（场景在视觉上起什么作用）

> **铁律：** 如果你无法用五个词表达出来，说明你还没想清楚。

#### 结构公式

```
[主体] + [状态] + [氛围或动作]
```

**薄弱意图：** A beautiful dreamy surreal scene（太模糊、太客气）
**强力意图：** Solitary woman dissolving into fog（MidJourney 能立即理解谁最重要、正在发生什么、什么必须主导图像）

#### 操作步骤

```
Step 1: 写下任何提示词之前，先问自己——"如果我只能保留五个单词，它们会是什么？"
Step 2: 写下这五个词
Step 3: 大声读出来——如果感觉模糊，就磨炼它们
Step 4: 将五词意图放在提示词最前面（位于风格、相机参数或形容词之前）
Step 5: 在此基础上扩展完整描述，所有元素服从意图
```

#### 五种意图 × 完整提示词示例

**① Water slowly carving fragile paths**
> Water slowly carving fragile paths, thin streams flowing gently across stone, shaping grooves over time. Movement minimal, surface reflective only in small highlights. Light directional but soft, emphasizing form without sparkle. Stone texture chalky and worn, water translucent and calm. Palette cool and restrained: soft grays, pale blues. Shot as contemplative nature photography, full-frame camera, 50mm lens, f/8, moderate shutter effect, controlled contrast, sense of gradual change --ar 16:9 --raw

**② Child watching stars from attic**
> Child looking at the stars from the attic, small figure sitting next to a dusty window under a roof, face gently illuminated by the light of distant stars. Night sky visible through the glass, deep indigo tones dotted with faint stars. The interior textures are worn, the wood matte and granular, the fabric fibers visible on the old covers. The warm inner darkness contrasts with the cool celestial light. Intimate and silent atmosphere. Shot as a cinematographic photograph, 85mm lens, f/1.8, low light exposure, soft falloff, soft diffusion, emotional restraint, poetic realism --ar 16:9 --raw

**③ Lonely tree enduring endless winter**
> Solitary tree bearing an endless winter, bare branches twisted against a pale and frozen sky, standing isolated in a vast snowy field. Subtle wind movement, fine snow particles suspended in the air. Textures are dry, brittle, chalky snow surface. Cold monochrome palette of muted whites, grays and blues. Distant horizon softened by atmospheric mist. Taken as a minimalist landscape photography, 70mm lens, f/8, large depth of field, soft and covert lighting, natural grain, restricted composition, silent endurance --ar 16:9 --raw

**④ Woman dissolving into falling leaves**
> Woman dissolving into falling leaves, human form gently breaking apart as autumn foliage drifts from her silhouette, motion slow and graceful. Warm amber and muted copper tones dominate the scene. Background softly blurred, suggesting a forest without detail. Light is diffused, low contrast, painterly softness. Shot as fine art conceptual photography, 50mm lens, f/2, shallow depth of field, motion blur on leaves, soft diffusion, emotional abstraction, poetic symbolism --ar 16:9 --raw

**⑤ Ancient door waiting to open**
> An ancient door waiting to open, cracked stone walls, worn surface by the centuries. A subtle light, particles of dust floating in the air. The textures of the altered stones a mineral discoloration. Atmosphere heavy with silence and anticipation. Color palette composed of muted earthy tones and soft golden highlights. Shot as a cinematographic architecture photograph, 24mm lens, f/5.6, deep focus, controlled lighting, volumetric dust burst, restricted drama, timeless ambience --ar 16:9 --raw

---

### 1.4 语义引力

#### 核心理论

**语言是有质量的。** AI 并不能真正"理解"词语，它衡量的是它们的引力——**语义密度（semantic density）**，即一个词承载了多少情感和文化重量。

像"光"、"家"或"寂静"这样的词，浸透了千百年的故事。它们将模型引向更丰富、更有质感的图像。

#### 轻词汇 vs. 重词汇

| 类型 | 特点 | 对图像的影响 | 示例词汇 |
|------|------|-------------|---------|
| **轻盈词** | 轻快、空灵、梦幻 | 色彩柔和、构图开阔、空气感强、画面呼吸 | feather, drifting, floating, gentle, soft, sheer, breeze, twilight, ethereal, pastel |
| **沉重词** | 厚重、内省、忧郁 | 构图密集、阴影拉长、纹理加深、色调变冷 | stone, worn, rain, muted, dark, buried, cracked, smoke, heavy, dense, closed |

**轻盈词示例：**
> a feather drifting in morning sunlight, pastel hues, soft focus, poetic atmosphere, 85mm lens, f/1.4, ISO 100, diffused natural light --ar 8:5
> → 图像会"呼吸"，色彩变得柔和，AI 描绘出动感与轻柔。

**沉重词示例：**
> a worn stone resting in the rain, muted tones, cinematic realism, 35mm lens, f/4, ISO 400, moody overcast lighting --ar 8:5
> → 构图变得密集，阴影拉长，纹理加深。

#### 平衡对比的魔力

将沉重与轻盈并置，创造情感张力——这是构图的精髓。

**平衡对比示例：**
> a feather lying on wet stone, delicate yet grounded, cinematic natural light, 50mm f/2.8, ISO 200, soft drizzle --ar 8:5
> → 沉重与轻盈并存，羽毛与石头之间的对比创造了情感张力。

更多对比：

| 轻盈词 | 沉重词 | 平衡对比 |
|--------|--------|---------|
| a white door floating among clouds, golden morning light, ethereal glow | an old wooden door half-buried in the earth, cracked surface, dark soil | an open door standing in a foggy meadow, faint light streaming through |
| a small candle flickering in gentle twilight, warm amber tones | a candle burning in total darkness, thick smoke curling upward | a candle burning in the rain, surrounded by night mist, flame trembling yet alive |
| an open window facing the sea breeze, sheer curtains floating in sunlight | a closed window streaked with rain, reflections of a dark room | a half-open window at dusk, warm interior glow, soft light meeting shadow |

#### 实践法则

- 每一个修饰词都会改变 MidJourney 的语义坐标
- 用词越"厚重"，模型越会压缩视角并加深色调
- 增加"开放性"，画面就会变宽、色彩饱和度提高
- 将"flicker"（闪烁）替换为"burn"（燃烧），光线便增强强度
- 添加"smoke"或"stone"，情绪便因重力而下沉

---

## 2. 万能公式模板大全

### 2.1 S.C.A.M.P. 五层公式（创意总监公式）

> 来源：Midjourney V8 最强出图指南，综合表现最佳王牌

**适用场景：** 品牌视觉塑造、故事感表达、高质量视觉大片

**公式结构：**
```
A [subject] placed in [environment], featuring [key visual elements], illuminated by [lighting], creating a [mood/emotion] atmosphere, using a [color palette], captured in a [camera/composition style]
```

| 要素 | 填写内容 | 示例 |
|------|---------|------|
| Subject | 主体描述 | a cozy pastel café interior |
| Environment | 环境背景 | filled with soft cherry blossoms gently falling outside the window |
| Key Visual Elements | 关键视觉元素 | featuring a wooden table arranged with delicate desserts and warm tea |
| Lighting | 光线 | illuminated by warm afternoon sunlight |
| Mood/Emotion | 情绪氛围 | creating a romantic and comforting atmosphere |
| Color Palette | 色调 | using a soft pink and cream color palette |
| Camera/Composition | 相机/构图 | captured in a cinematic close-up composition |

**完整示例：**
> A cozy pastel café interior filled with soft cherry blossoms gently falling outside the window, featuring a wooden table arranged with delicate desserts and warm tea, illuminated by warm afternoon sunlight that creates a romantic and comforting atmosphere, using a soft pink and cream color palette, captured in a cinematic close-up composition

---

### 2.2 摄影思维公式

**适用场景：** 所有类型的 AI 绘画（核心法则：停止像作家一样思考，开始像相机一样观察）

**万能公式：**
```
[摄影风格] + [主体] + [光线表现] + [镜头] + [焦点]
```

**五种摄影思维对照表：**

| 思维类型 | 核心诉求 | 推荐镜头 | 画面效果 | 示例提示词 |
|---------|---------|---------|---------|-----------|
| **纪实思维** | 真实至上 | 35mm | 真实、有瑕疵、具有观察感 | documentary photography, woman exploring a cathedral, natural light filtering through stained glass, realistic shadows, handheld camera feel, slight motion blur, 35mm lens, candid moment, unposed, muted tones --ar 2:1 --raw |
| **电影思维** | 情感至上 | 50mm | 精心设计的场景、亲密感 | cinematic still, woman exploring a cathedral, dramatic volumetric light rays, deep shadows, high contrast lighting, slow contemplative mood, 50mm lens, shallow depth of field, atmospheric haze, film grain --ar 2:1 --raw |
| **商业品牌思维** | 清晰至上 | 85mm | 干净、优雅、高端 | brand photography, elegant woman exploring a cathedral, clean composition, balanced framing, soft diffused lighting, high detail, sharp focus, premium aesthetic, controlled environment, 85mm lens --ar 2:1 --raw |
| **街头摄影思维** | 随性至上 | 35mm | 充满生命力、毫无计划感 | street style photography, woman exploring a cathedral, dynamic angle, slightly off-center framing, natural movement, ambient lighting, urban documentary feel, 35mm lens, candid capture --ar 2:1 --raw |
| **人像思维** | 主体至上 | 85mm | 强烈情感焦点、奶油焦外 | portrait photography, close-up of a woman inside a cathedral, soft light on face, blurred background, shallow depth of field, 85mm lens, emotional expression, natural skin texture --ar 2:1 --raw |

**镜头选择速查表：**

| 镜头 | 核心理念 | 最佳场景 |
|------|---------|---------|
| 24mm | 夸张深度和瑕疵 | 大场景、建筑、风景 |
| 28mm | 自然广角 | 风景、环境人像 |
| 35mm | "我就在现场" | 纪实、街头、环境叙事 |
| 50mm | "这是一个精心设计的场景" | 电影感、标准叙事 |
| 70mm | 适中压缩 | 风景中焦、人像 |
| 85mm | "聚焦于完美" | 商业、人像、高端视觉 |
| 100mm | 微距细节 | 纹理、微观 |
| 200mm+ | 远摄压缩 | 野生动物、主体隔离 |

**核心思维转变：**
- ❌ 别再问："我想要看到什么？"
- ✅ 开始问："**摄影师会如何拍下这一幕？**"

---

### 2.3 句子优先法公式

**公式结构：**
```
[Sentence], [camera logic], [light grammar], [material precision] --ar [ratio] [other parameters]
```

**四段式详解：**

| 段落 | 内容 | 示例 |
|------|------|------|
| **Sentence** | 核心句（主体+动作+背景+情感） | A narrow street in the rain reflecting neon lights at night |
| **Camera Logic** | 镜头逻辑（构图、镜头、距离、景深） | low angle perspective, 35mm lens, wet pavement reflections |
| **Light Grammar** | 光影语法（时间、方向、对比度、氛围） | strong contrast lighting, saturated neon colors bleeding into the ground |
| **Material Precision** | 材质精度（表面特性、纹理） | 隐含在场景描述中 |
| **Parameters** | 参数 | --ar 16:9 --v 7 --style raw --s 300 |

**完整示例：**
> A narrow street in the rain reflecting neon lights at night, low angle perspective, 35mm lens, wet pavement reflections, strong contrast lighting, saturated neon colors bleeding into the ground --ar 16:9 --v 7 --style raw --s 300

> A deserted highway stretching endlessly through a desert at sunset, centered composition, 24mm lens, deep focus, warm directional light, long shadows cutting across the road --ar 16:9 --quality 2 --raw --stylize 300

> A crowded subway where one person stands still while everything moves around them, dynamic motion blur, 35mm lens, slow shutter effect, artificial fluorescent lighting, urban tones --ar 16:9 --v 7 --style raw --s 350

> A small boat drifting slowly under a sky filled with stars, wide composition, 24mm lens, deep focus, long exposure effect, soft reflections on water, cool blue night tones --ar 16:9 --v 7 --style raw --s 300

---

### 2.4 大师级风景公式

**适用场景：** 摄影级真实风景图

#### 四大核心支柱

| 支柱 | 说明 | 关键技巧 |
|------|------|---------|
| **深度** | 空间构建方式 | 三层法则：前景(锚点) → 中景(视觉通道) → 背景(气场) |
| **大气/氛围** | 距离感表现 | 空气透视：远处对比度更低、色温更冷、边缘更柔和 |
| **光线** | 场景展现方式 | 永远只选择一种主光源（侧光/逆光/漫射光/黄金时刻/蓝调时刻） |
| **材质** | 物质对环境条件的反应 | 材质与天气匹配（湿岩石有反射、干沙哑光、雪散射光等） |

#### 三层法则结构

| 层次 | 角色 | 示例元素 |
|------|------|---------|
| **前景** | 定海神针（锚点） | 岩石、青草、沙纹、浮木、雪地纹理 |
| **中景** | 视觉通道 | 河湾、小径、海岸线、林木线 |
| **背景** | 气场所在 | 群山、地平线、风暴墙、远处的山脊 |

#### 材质-天气匹配对照表

| 天气条件 | 材质反应 | 提示词关键词 |
|---------|---------|-------------|
| 雨后 | 湿岩石有反射、颜色变深、出现高光 | wet stones reflecting soft light, damp soil textures, puddles |
| 干燥 | 哑光质感、漫反射光 | dry sand, matte texture, diffused light |
| 雪天 | 明亮、柔和、光线散射 | bright snow, soft light, scattered reflection |
| 雾天 | 降低微观对比度 | mist, reduced contrast, soft edges |
| 雨天 | 增加光泽感和水面反射 | rain, glossy surfaces, water reflections |

#### 主光源选择指南

| 光线类型 | 效果 | 提示词 |
|---------|------|--------|
| 侧光 (Side Light) | 展现纹理和地形起伏 | side lighting, textured shadows |
| 逆光 (Backlight) | 创造光晕和氛围感 | backlight, rim light, atmospheric glow |
| 阴天/漫射光 (Overcast) | 消除强烈对比，展现细节 | overcast, diffused light, even illumination |
| 蓝调时刻 (Blue Hour) | 柔和深邃 | blue hour, soft cool light |
| 黄金时刻 (Golden Hour) | 拉长阴影，增强立体感 | golden hour, long shadows, warm directional light |

#### 大师级完整示例

> Landscape photograph of a wide valley, textured grass and small rocks in the foreground, winding river leading through the midground, distant mountains fading into soft atmospheric haze, early morning side light creating gentle shadows, slight mist in low areas, natural color palette, high detail but soft distance, Sony A7R V, 28mm, f/11, ISO 100

> Landscape photograph of a coastal cliff, sharp textured rocks in the foreground with wet reflections, curved shoreline guiding through the midground, distant ocean horizon fading into light haze, soft side lighting, natural tones, Nikon Z8, 24mm, f/11, ISO 100 --ar 2:1 --raw --stylize 150 --hd --v 8.1

> Mountain landscape photograph with layered ridgelines, rocky foreground in sharp focus, midground forest slightly softened, distant mountains fading into blue atmospheric haze, natural daylight, Sony A1, 70mm, f/11, ISO 100 --ar 2:1 --raw --stylize 150 --hd --v 8.1

> Landscape photograph at golden hour, low sun coming from the side casting long shadows across textured grassland, gentle haze softening distant hills, warm highlights balanced with cool shadows, Canon R5, 35mm, f/11, ISO 100

> Landscape photograph after rainfall, wet stones in the foreground reflecting soft light, damp soil textures, shallow puddles creating subtle reflections, overcast sky diffusing light evenly, distant hills softened by mist, Nikon D850, 35mm, f/11, ISO 200

---

### 2.5 商业广告公式

#### 精准控制公式（搭配 --raw 使用）

**适用场景：** 产品摄影、极简干净视觉、商业用途素材

**公式：**
```
A [object/product] made of [materials and details], placed against a [background], lit with [lighting setup], composed in a [composition style], with a realistic and clean aesthetic, high clarity
```

**示例：**
> A luxury skincare serum bottle made of frosted glass with gold metallic accents, placed against a clean beige gradient background, lit with soft diffused studio lighting and subtle reflections, composed in a centered product shot with minimal shadows, with a realistic and clean aesthetic, high clarity

#### 商业摄影风格模板库

| 风格 | 公式 | 示例关键词 |
|------|------|-----------|
| **奢华暗调** | Deep black backdrop + dramatic rim lighting | deep black backdrop, dramatic rim lighting, reflective surface placement, premium material emphasis, sophisticated mood |
| **干净影棚** | Pure white background + controlled shadow | pure white seamless background, controlled shadow falloff, product-centered composition, professional lighting |
| **护肤清透** | Soft pastel + diffused gentle lighting | soft pastel background, diffused gentle lighting, clean fresh aesthetic, smooth surface quality, wellness mood |
| **科技未来** | Glossy reflections + cool blue accent | glossy surface reflections, cool blue accent lighting, sleek modern design, futuristic aesthetic, innovation emphasis |
| **电商标准** | Centered + even shadowless lighting | centered product placement, even shadowless lighting, neutral backdrop, true color accuracy, retail ready |

---

### 2.6 电影感公式

**核心公式：** 对比法框架

**一个主导元素 + 一股对立力量 = 视觉张力**

**10种对抗类型及示例：**

| # | 对抗类型 | 示例提示词 |
|---|---------|-----------|
| 1 | **光与暗** | A lone figure standing in a vast dark landscape, illuminated by a single soft spotlight, deep shadows surrounding, cinematic lighting, high contrast atmosphere, shot on ARRI Alexa, 50mm lens, f/1.8, ultra realistic --ar 16:9 --v 7 --style raw |
| 2 | **柔和与冷硬** | A delicate silk fabric flowing in a brutalist concrete environment, sharp architectural lines contrasting with soft motion, diffused light vs hard shadows, editorial photography, 85mm lens, f/2 --ar 3:4 --raw |
| 3 | **静止与运动** | A perfectly still human figure surrounded by chaotic motion blur of a rushing crowd, long exposure effect, dynamic streaks, emotional tension, cinematic realism, 35mm lens --ar 16:9 --v 7 --style raw |
| 4 | **渺小与宏大** | A tiny silhouette standing in an immense desert under a dramatic sky, overwhelming scale, minimal composition, strong negative space, cinematic wide shot, 24mm lens --ar 21:9 --v 7 --style raw |
| 5 | **暖调与冷调** | A warm glowing light source inside a frozen blue icy environment, strong color contrast, emotional atmosphere, volumetric lighting, shot on RED camera, 50mm lens --ar 16:9 --v 7 --style raw |
| 6 | **锐利与模糊** | A sharply focused subject in the foreground with a heavily blurred abstract background, shallow depth of field, bokeh, high detail vs softness, portrait photography, 85mm lens, f/1.4 --ar 2:3 --v 7 --style raw |
| 7 | **秩序与混乱** | A perfectly symmetrical subject disrupted by chaotic elements breaking the frame, fractured composition, tension, high contrast lighting, conceptual photography --ar 1:1 --v 7 --style raw |
| 8 | **光泽与纹理** | Smooth reflective surface interrupted by rough cracked textures, interplay between clean and damaged materials, macro photography, extreme detail, 100mm macro lens --ar 1:1 --v 7 --style raw |
| 9 | **孤立与密集** | A single subject isolated in empty space surrounded by a dense overwhelming environment in the distance, layered depth, atmospheric perspective, cinematic composition --ar 16:9 --raw |
| 10 | **宁静与喧嚣** | A quiet minimal scene invaded by dynamic particles, wind, or motion, contrast between calm and agitation, emotional storytelling, long exposure combined with still subject --ar 16:9 --v 7 --style raw |

#### 电影感通用模板

```
cinematic still, [核心场景], [镜头], [景深], [光线], [氛围], [色调], film grain --ar [比例] --v [版本] --style raw
```

**示例：**
> cinematic still, woman exploring a cathedral, dramatic volumetric light rays, deep shadows, high contrast lighting, slow contemplative mood, 50mm lens, shallow depth of field, atmospheric haze, film grain --ar 2:1 --raw

---

### 2.7 PBR 超写实公式

**适用场景：** 极致真实感的图像输出

**核心要素：**
- PBR（Physically Based Rendering，基于物理的光影渲染）
- 专业镜头公式
- 光学效果模拟

**超写实输出模板库：**

| 风格 | 公式 | 示例 |
|------|------|------|
| **影棚人像** | Three-point lighting + seamless backdrop + 85mm compression + catchlight in eyes | Studio Portrait Mastery: Three-point lighting setup, seamless backdrop, 85mm portrait lens compression, catchlight in eyes |
| **胶片摄影** | 35mm film grain + subtle color shifts + soft highlight rolloff + vintage lens character | 35mm film grain texture, subtle color shifts, soft highlight rolloff, vintage lens character |
| **黄金时刻** | Warm directional sunlight + long dramatic shadows + soft golden glow + backlit rim lighting | Warm directional sunlight, long dramatic shadows, soft golden glow, backlit rim lighting |
| **环境叙事** | Natural ambient light + subject in authentic context + documentary candidness | Natural ambient light, subject in authentic context, documentary candidness, environmental details |
| **街头决定性瞬间** | Urban backdrop layers + motion blur suggestion + gritty contrast + 35mm focal length | Urban backdrop layers, motion blur suggestion, gritty contrast, 35mm focal length |
| **野生动物远摄** | 200mm+ lens compression + subject isolation + natural behavior moment | 200mm+ lens compression, subject isolation from environment, natural behavior moment |
| **风景大视野** | Wide angle perspective + deep depth of field + natural color accuracy + atmospheric perspective layers | Wide angle perspective, deep depth of field, natural color accuracy, atmospheric perspective layers |

---

## 3. 参数配置指南

### 3.1 Midjourney 核心参数对照

#### 基础参数

| 参数 | 说明 | 取值范围 | 使用建议 |
|------|------|---------|---------|
| `--ar` | 画面宽高比 | 如 16:9, 4:5, 2:1, 9:16, 21:9, 1:1 | 根据平台选择：横版16:9电影感，竖版9:16社交媒体，1:1均衡 |
| `--v` | 模型版本 | 6, 7, 8.1 | V8自然语言理解更强，支持文字渲染和情绪板 |
| `--style raw` | 降低艺术滤镜 | raw / 无 | 追求真实感和准确性时必加 |
| `--stylize` (--s) | 艺术化程度 | 0-1000 (默认100) | 数值越低越忠于提示词，数值越高越艺术化 |
| `--profile` | 个性化代码 | 自定义代码串 | 固定个人审美偏好 |
| `--sref` | 风格参考 | 图片URL或ID | 参考特定图片的风格 |
| `--cref` | 角色参考 | 图片URL或ID | 保持角色一致性 |
| `--q` (--quality) | 渲染质量 | 1, 2 | 越高细节越丰富 |
| `--hd` | 高清晰度模式 | 开关参数 | V8.1风景图专用 |
| `--no` | 负面参数 | 排除的元素 | 如 --no cake 排除蛋糕 |
| `--iw` | 图像权重 | 0.5-2.0 | 控制参考图的影响力 |

#### 参数搭配策略

| 目标效果 | 推荐参数组合 |
|---------|-------------|
| 摄影级真实感 | `--style raw --stylize 150-250 --v 8.1` |
| 电影感叙事 | `--style raw --stylize 250-400 --ar 16:9 --v 7/8` |
| 商业产品图 | `--style raw --stylize 100-200 --v 8` |
| 艺术插画风 | `--stylize 400-600 --v 7` |
| 风格化创作 | `--stylize 600-800 --sref [style]` |
| 超写实风景 | `--style raw --stylize 150 --hd --v 8.1` |
| 社交媒体爆款 | `--stylize 300-500 --ar 9:16 (竖屏)` |

---

### 3.2 Nano Banana Pro 参数

#### 核心能力参数

| 功能 | 说明 |
|------|------|
| **默认思考模式** | 模型会先推理草图再画最终作品，草图推理不收费 |
| **参考图数量** | 最多 14 张 |
| **人物一致性数量** | 最多 5 个人物 |
| **高清输出分辨率** | 支持 1K 到 4K 原生高分辨率 |
| **中文文字渲染** | 支持，需强调 2K/4K 高清画质 |
| **谷歌搜索集成** | 可调用实时数据生成图像 |
| **自然语言编辑** | 无需蒙版，通过描述完成修复、上色、风格转换 |
| **2D→3D 转换** | 支持户型图、表情包等 |
| **分镜生成** | 一次会话可创建风格统一的连贯故事（如 9 集 16:9 横版） |
| **结构控制** | 支持草图、线框、网格图输入来控制构图 |

#### 提示词黄金法则

| 法则 | 说明 |
|------|------|
| **别重新生成，直接改** | 如果图片已80%完美，直接告诉模型修改细节，它会在原图上局部调整 |
| **越具体越好** | 明确描述主体、场景、光线、氛围，避免模糊表达 |
| **给它上下文** | 提供足够的背景信息（用途、平台、风格），让模型做出更合理判断 |

#### 5个专家技巧

1. **主体优先**：在添加任何风格化修饰语之前，务必先定义核心主体
2. **光影是关键**：使用如"Golden hour"或"Volumetric light"等术语瞬间提升画面深度
3. **1-2 原则**：不要堆砌过多的风格，选择一到两个截然不同的参考风格效果最好
4. **构图取景**：利用"Dutch angle"或"Rule of thirds"来掌控观众的视觉焦点
5. **材质至上**：加入如"Brushed titanium"或"Weathered oak"等材质描述，增加画面触感丰富度

---

### 3.3 平台选择决策树

```
你的需求是什么？
│
├── 摄影级真实风景 / 艺术创作 / 电影感
│   └── → Midjourney V7/V8 (推荐：--style raw + 摄影思维公式)
│
├── 商业产品图 / 家装设计 / 实用设计
│   └── → Google ImageFX / Nano Banana Pro (推荐：精准控制公式)
│
├── 需要文字渲染 / 海报设计 / 信息图
│   └── → Midjourney V8 或 Nano Banana Pro (支持中文文字)
│
├── 需要人物一致性 / 品牌视觉IP
│   └── → Midjourney V8 (sref + 情绪板) 或 Nano Banana Pro (14张参考图)
│
├── 需要实时数据可视化 / 信息图表
│   └── → Nano Banana Pro (集成谷歌搜索)
│
├── 新手入门 / 快速出图 / 多个领域探索
│   └── → 使用「万能AI文生图提示框架」+ Gemini 2.5 Pro 推理 → 再发送给目标生图AI
│
└── 创意构思 / 风格探索 / 灵感发散
    └── → Midjourney (profile + sref 组合实验)
```

---

## 4. 常见错误与破解

### 4.1 塑料感的7种来源与破解

#### 三种过度平滑类型

| 类型 | 表现 | 根源 |
|------|------|------|
| **表面平滑** | 边缘被柔化，瑕疵被抹除 | 训练数据偏好"完成度高"的图像 |
| **光线平滑** | 光影无层次，缺乏对比 | 扩散模型渐进式清理逻辑 |
| **情感平滑** | 技术上完美但情感扁平 | 默认风格化逻辑统一表面、调和色彩 |

#### 7种来源与破解方案

| # | 来源 | 破解方法 | 提示词技巧 |
|---|------|---------|-----------|
| 1 | **AI默认抛光本能** | 将不完美声明为意图 | 加入"uneven texture", "visible grain", "imperfect surfaces", "raw, unpolished aesthetic" |
| 2 | **缺乏材质语言** | 使用材质类提示词 | 加入"rough concrete", "oxidized metal", "frayed fabric", "dust particles in the air" |
| 3 | **光线过于柔和均匀** | 控制光线条件 | 使用"harsh directional light", "strong shadows", "rim lighting", "low-angle sunlight" |
| 4 | **镜头选择不当** | 选择合适镜头 | 85mm→更平滑；35mm→更自然质感；24mm→夸张深度和瑕疵 |
| 5 | **完美信号过强** | 减少完美类提示词 | 避免"ultra clean", "perfect lighting", "studio quality"；替换为"documentary style", "unfiltered", "cinematic realism" |
| 6 | **材质与天气不匹配** | 材质与天气对应 | 湿岩石有反射、干沙哑光、雪散射光、雾降低对比度 |
| 7 | **微观细节替代了宏观质感** | 追求粗糙感和不规则性 | 加入"roughness", "irregularity", "unpredictability", "textured" |

#### 对比示例

**默认状态（过度平滑）：**
> Cozy living room, soft lighting, clean composition, modern interior, neutral tones, cinematic photography, 50mm lens, f/2.8 --ar 16:9 --v 7
> → 很美……但很平庸

**质感增强版：**
> Lived-in living room, worn linen sofa with visible creases, wooden table with scratches and uneven surface, scattered books, dust particles in warm directional sunlight, strong shadow contrast, documentary interior photography, 35mm lens, f/4 --ar 16:9 --v 7 --style raw --s 150
> → 不完美……但极具真实感

**进阶实战示例：**
> Abandoned subway tunnel, wet concrete walls with mineral streaks, rusted metal beams, puddles reflecting broken fluorescent lights, dripping water captured mid-motion, harsh side lighting carving deep shadows, cinematic urban documentary photography, 24mm lens, f/5.6 --ar 16:9 --raw --stylize 300

> Old leather workshop, cracked hides hanging from wooden racks, worn tools scattered on dusty surfaces, visible scratches and patina, directional window light creating sharp contrast, textured air particles, 35mm lens, f/4 --ar 16:9 --raw --stylize 220

> Storm-battered coastline, jagged rocks covered in algae and salt crust, chaotic wave impact with fragmented foam, strong wind distortion, low-angle sunlight creating aggressive contrast, 28mm lens, f/8 --ar 16:9 --raw --stylize 260

> Wet cobblestone street after heavy rain, uneven stones with varied reflectivity, puddles forming irregular shapes, subtle reflections of surrounding architecture, low-angle directional light enhancing texture, 35mm lens --ar 16:9 --raw --stylize 230

---

### 4.2 提示词超载诊断

#### 超载症状清单

| 症状 | 表现 | 诊断 |
|------|------|------|
| 画面视觉犹豫不决 | 不知道焦点在哪 | 多个权重相等的物体 |
| 光源互相矛盾 | 阴影方向不一致 | 同时指定了多个冲突的光源 |
| 风格打架 | 画面风格杂乱 | 过多风格强行叠加（>2种） |
| 情感中性化 | 没有情绪冲击力 | 情绪词指向完全相反的方向 |
| 有细节无重点 | 横向铺开而非纵向深挖 | 过度描述材质但没有层级 |
| AI"塑料感" | 技术完美但情感空洞 | 过度使用"perfect", "clean", "ultra"等抛光信号 |

#### 自检清单

在提交提示词前，逐一检查：

- [ ] 我能否用一句干练的话描述这个画面？（统治句测试）
- [ ] 画面是否有单一明确的主体？（主体测试）
- [ ] 是否只有一个主导光源？（光源测试）
- [ ] 风格是否控制在1-2种以内？（风格数量测试）
- [ ] 每个词都在强化核心句吗？（必要性测试）
- [ ] 删掉这个词，画面会更清晰吗？（减法测试）
- [ ] 形容词是否控制在3-6个？（形容词数量测试）
- [ ] 是否混合了不同类别的形容词而非堆砌近义词？（多样性测试）
- [ ] 情绪词是否指向一致的方向？（情绪一致性测试）
- [ ] 材质是否与场景天气匹配？（物理逻辑测试）

#### 超载修复对照表

| 问题 | 修复前（超载） | 修复后（受控） |
|------|--------------|--------------|
| 多主体 | A cinematic portrait of a woman standing in a misty forest at night, surrounded by glowing flowers, birds flying around her, a distant futuristic city in the background | A solitary woman standing in the foreground of a misty forest at night |
| 多光源 | dramatic moonlight, neon rim light, candlelight glow | her face softly illuminated by a single moonlit rim light |
| 多风格 | fantasy illustration style, oil painting texture, photorealistic lighting, surreal dream atmosphere | cinematic portrait photography |
| 无层级 | hyper-detailed textures, ultra-realistic skin… | background trees dissolving into deep blue haze, subtle fog drifting at ground level |

---

### 4.3 情感空洞修复

#### 通感魔法（Synesthetic Prompting）

**核心法则：** 用一种感官去描述另一种感官

- 与其描述物体 → 不如描述感觉
- 与其描述场景 → 不如描述感知

**对比：**
- ❌ 不要说："soft light"
- ✅ 要说："light that feels like warm skin"
- ❌ 不要说："blue tones"
- ✅ 要说："a quiet blue that hums slowly"

#### 通感提示词5层结构

| 层级 | 内容 | 示例 |
|------|------|------|
| **1. 核心感觉** | 情感+状态 | melancholic calm, electric tension, warm nostalgia |
| **2. 感官转译** | 跨感官描述 | "a silence that glows", "a color that vibrates softly", "a shadow that feels cold" |
| **3. 物理锚点** | 让画面落地（可选但强大） | forest, ocean, figure, architecture |
| **4. 光线表现** | 光就是情感 | diffused glow, flickering highlights, heavy shadows |
| **5. 相机写实** | 稳定画面 | lens (50mm, 85mm), depth of field, film grain |

#### 通感提示词库

**静谧氛围：**
> a vast landscape filled with glowing silence, pale golden light humming softly across the horizon, gentle atmospheric diffusion, cinematic realism, 50mm lens, shallow haze --ar 16:9 --raw

> fog drifting like a slow whisper, soft blue tones vibrating through empty space, quiet atmosphere, fine film grain, long exposure feeling, 35mm lens --ar 2:1 --raw

**声化作光：**
> abstract sound waves transforming into flowing neon colors, liquid motion, vibrant gradients, long exposure streaks, cinematic glow, macro lens --ar 2:1 --raw

> floating ribbons of light echoing through darkness, gentle waves of color moving like sound, abstract minimalism, soft diffusion --ar 2:1 --raw

**触觉视觉化：**
> a soft landscape where everything appears velvety, muted colors, smooth gradients, gentle blur, tactile atmosphere, macro lens --ar 2:1 --raw

> a room filled with thick, heavy air, shadows pressing against surfaces, warm low light, cinematic depth, 35mm lens --ar 2:1 --raw

**光即情感：**
> a melancholic blue landscape, dim light fading slowly into darkness, subtle grain, emotional stillness, 50mm lens --ar 2:1 --raw

> a peaceful environment where light feels weightless, soft white glow, minimal shadows, ethereal clarity, 50mm lens --ar 2:1 --raw

**抽象感知：**
> memories drifting like colored fog, blurred forms, pastel tones, emotional diffusion, cinematic softness --ar 2:1 --raw

> a landscape bending gently as if breathing, soft distortions, fluid perspective, dreamlike realism, 35mm lens --ar 2:1 --raw

#### 感知创作法

**核心转变：** 从"描述画面里有什么"到"描述观看者的体验"

**创作前自问：**
1. 焦点是什么？
2. 它的周围是什么？（留白/负空间）
3. 哪些地方是刻意留白的？
4. 观看者第一眼应该感受到什么？

**框架：**
```
[孤立的主体] + [周围的空旷感] + [可控的光线] + [清晰的焦点]
```

**感知创作示例：**
> A photograph of a single wooden chair alone in a vast empty room, soft diffused window light, long shadows stretching across the floor, muted neutral tones, strong negative space, minimalist composition, cinematic stillness, low contrast, fine art photography --ar 2:1 --stylize 600

> A lone tree standing in an open foggy field, barely visible horizon, desaturated palette, soft atmospheric haze, subject slightly off-center following rule of thirds, gentle light diffusion, contemplative mood, shallow depth of field, fine art photography --ar 2:1 --stylize 600

> A narrow street at dawn with a single distant figure walking away, large empty foreground, subtle leading lines guiding the eye, cool blue tones of early morning, soft shadows, quiet urban atmosphere, cinematic framing --ar 2:1 --stylize 600

> A wide coastal landscape with a tiny human silhouette, vast sky occupying most of the frame, soft pastel colors, gentle wind movement implied, expansive negative space, peaceful cinematic tone, blue hour fine art photography --ar 2:1 --stylize 600

---

## 5. 提示词组合黄金法则

### 5.1 组合顺序

**正确顺序：**
```
五词意图 / 核心句 → 主体细节 → 环境背景 → 光线 → 镜头 → 构图 → 材质 → 色调/氛围 → 风格参考 → 参数
```

**详细说明：**

| 顺序 | 类别 | 示例 | 作用 |
|------|------|------|------|
| 1 | **意图/核心句** | Solitary lighthouse resisting violent storm | 锚定画面核心 |
| 2 | **主体细节** | standing alone on jagged black cliffs | 明确主要物体 |
| 3 | **环境背景** | enormous waves crashing against rocks | 建立空间关系 |
| 4 | **光线** | dramatic moonlight, volumetric light | 赋予情感基调 |
| 5 | **镜头** | 35mm lens, full-frame camera | 确定观看视角 |
| 6 | **构图** | wide shot, shallow depth of field | 控制视觉焦点 |
| 7 | **材质** | wet rocks, sea spray, rough textures | 增加真实触感 |
| 8 | **色调/氛围** | cool blue palette, cinematic realism | 统一情绪色调 |
| 9 | **风格参考** | --sref [id] --profile [code] | 固定风格基调 |
| 10 | **参数** | --ar 16:9 --raw --s 250 | 技术控制 |

### 5.2 数量控制

| 要素 | 最佳数量 | 上限 |
|------|---------|------|
| 核心意图词 | 5个 | 不超过7个 |
| 形容词 | 3-6个 | 不超过10个（超载风险） |
| 风格参考 | 1-2种 | 不超过3种 |
| 光源 | 1种主导 | 绝对不超过2种 |
| 主体 | 1个主导 | 不超过2个 |
| 情绪指向 | 1个方向 | 保持一致 |

### 5.3 类别混合策略

#### 形容词混合法则

**正确做法：** 混合不同类别，不要堆砌近义词

**可混合的类别：**
- 颜色（warm amber, pale blue, muted gray）
- 纹理（rough, smooth, velvety, cracked）
- 材料（wood, stone, metal, glass, fabric）
- 灯光风格（dramatic, soft, harsh, diffused）
- 设计美学（minimalist, brutalist, baroque）
- 物理属性（heavy, light, dense, brittle）

**正确示例（电影感肖像）：**
> dramatic lighting, shallow depth of field, intense gaze, cinematic color grading, film grain
→ 混合了光线、镜头、情感、调色、材质 5个不同类别

**错误示例（超载求救）：**
> dramatic, cinematic, epic, emotional, intense, powerful, beautiful, stunning, unreal, insane
→ 全部是同类别（抽象赞美词）堆砌，AI无法区分优先级

#### 风格混合1-2原则

- 选择**1个主导风格** + **1个辅助风格**（可选）
- 风格之间应有**明显差异**以产生有趣的化学反应

**示例：**
- boho-nouveau（波西米亚+新艺术）
- driftwood-deco（浮木+装饰艺术）
- knit-brutalism（针织+野兽主义）

#### 完整提示词构建清单

```
□ 五词意图（锚定核心）
□ 核心句（主体+动作+背景+情感）
□ 镜头逻辑（1种镜头）
□ 光影语法（1种主光源）
□ 材质精度（与场景匹配）
□ 3-6个形容词（混合不同类别）
□ 1-2种风格（不要堆砌）
□ 参数配置（--ar, --v, --style raw等）
□ 做减法（逐一检查每个词的必要性）
□ 情感检查（画面是否有情绪感染力）
```

---

## 附录：邪修词库速查（50个核心指令）

### 光影与氛围
| 指令 | 作用 |
|------|------|
| Cinematic lighting | 电影级光照，营造大片感 |
| Volumetric lighting | 体积光/丁达尔效应，增加空间通透感 |
| Rim light | 轮廓光，勾勒主体边缘，增强立体感 |
| Bioluminescence | 生物荧光，适合奇幻或夜景 |
| God rays | 耶稣光/神圣光线 |
| Soft illumination | 柔和照明，适合人像或静物 |
| Neon ambiance | 霓虹氛围，赛博朋克必备 |
| Chiaroscuro | 明暗对照法，强烈的明暗对比 |
| Global illumination | 全局光照，模拟真实光线反射 |
| Moody lighting | 情绪化打光，营造忧郁或神秘氛围 |

### 画质与渲染
| 指令 | 作用 |
|------|------|
| 8k resolution | 8K超清分辨率 |
| Unreal Engine 5 | 虚幻引擎5渲染，极致3D质感 |
| Octane render | OC渲染器风格 |
| Hyper-realistic | 超写实主义 |
| Highly detailed | 高度细节 |
| Sharp focus | 清晰对焦 |
| Ray tracing | 光线追踪 |
| Intricate details | 错综复杂的细节 |
| Masterpiece | 杰作，提升整体画面质量权重 |
| HDR | 高动态范围 |

### 摄影与镜头
| 指令 | 作用 |
|------|------|
| Wide angle lens | 广角镜头 |
| Macro shot | 微距摄影 |
| Bokeh | 背景虚化/散景 |
| Depth of field | 景深 |
| Fish-eye view | 鱼眼视角 |
| Low angle shot | 低角度仰拍 |
| Bird's eye view | 鸟瞰图/上帝视角 |
| Dutch angle | 荷兰倾斜角 |
| Telephoto lens | 长焦镜头 |
| Isometric view | 等轴测视图 |

### 艺术风格
| 指令 | 作用 |
|------|------|
| Cyberpunk style | 赛博朋克风格 |
| Steampunk aesthetic | 蒸汽朋克 |
| Ukiyo-e style | 浮世绘风格 |
| Oil painting | 油画质感 |
| Watercolor sketch | 水彩速写 |
| Concept art | 概念艺术 |
| Matte painting | 遮罩绘画 |
| Pixel art | 像素艺术 |
| Gothic fantasy | 哥特奇幻 |
| Minimalist design | 极简主义设计 |

### 材质与特殊修饰
| 指令 | 作用 |
|------|------|
| Translucent skin | 半透明皮肤/次表面散射 |
| Iridescent texture | 彩虹色/珠光纹理 |
| Metallic sheen | 金属光泽 |
| Porcelain texture | 陶瓷质感 |
| Fluid simulation | 流体模拟 |
| Double exposure | 双重曝光 |
| Knolling layout | 零件平铺/强迫症排列 |
| Dispersion effect | 破碎/消散效果 |
| Chromium finish | 镀铬表面 |
| Filigree pattern | 金银丝细工/掐丝图案 |

---

> **最终心法：** Midjourney 是一面镜子。如果你的视线是分散的，你的图像也会是散乱的。如果你的感知是清晰的，你的图像就会充满呼吸感。你不需要更复杂的提示词，你需要的是更清晰的意图。
>
> 最顶级的创作者早已不再"写词"——他们开始"导戏"。
>
> **停止搜索提示词，开始指挥 AI。**
