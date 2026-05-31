# 光影与氛围知识体系

> 知识来源：AI绘画提示词知识库（10篇核心文章蒸馏）
> 内容涵盖：光线类型、时段、布光方案、天气氛围、四大核心支柱、三层法则、空气透视

---

## 1. 光线类型分类

### 1.1 按光源性质分类

| 光线类型 | 英文关键词 | 效果描述 | 适用场景 |
|---------|-----------|---------|---------|
| **自然光** | natural light | 源于太阳/月亮，最真实的光线 | 风景、人像、纪实 |
| **人造光** | artificial light | 人为可控的光源 | 影棚、夜景、创意 |
| **硬光** | hard light / harsh direct light | 来自小而远的光源，产生锐利阴影、高对比度 | 时尚、戏剧、黑白、强调轮廓 |
| **柔光** | soft light | 来自大面积/漫射光源，平滑边缘，降低对比度 | 人像、静物、电影感 |
| **漫射光** | diffused lighting | 失去了方向性的光，无生硬阴影，均匀柔和 | 阴天人像、室内、氛围 |
| **直射光** | direct sunlight | 强烈的定向光源，阴影清晰 | 正午外景、纪实 |
| **侧光** | side light | 从侧面照射，展现纹理和地形起伏 | 风景、人像、质感表现 |
| **逆光** | backlight | 从背后照射，创造光晕和氛围感 | 梦幻、轮廓、剪影 |
| **顺光** | front light | 从正面照射，揭示细节 | 人像、产品 |
| **顶光** | top light | 从上方照射 | 舞台、戏剧 |
| **底光** | bottom light / underlight | 从下方照射 | 恐怖、神秘、戏剧 |
| **轮廓光** | rim light | 放置在主体后方，创造发光边缘 | 分离主体、空灵效果 |
| **补光** | fill light | 辅助照明，柔和阴影 | 所有场景 |
| **体积光** | volumetric light | 可见的光束/光柱，丁达尔效应 | 神圣、电影感、氛围 |
| **全局光照** | global illumination | 模拟真实光线反射和散射 | 超写实、3D渲染 |
| **霓虹光** | neon light | 人造彩色光源，取代自然光 | 赛博朋克、夜生活、未来主义 |
| **烛光** | candlelight | 温暖、微弱的点光源 | 复古、浪漫、亲密氛围 |
| **月光** | moonlight | 低强度冷色光源 | 夜景、静谧、神秘 |
| **耶稣光/神光** | god rays | 穿透云层或障碍物的光线束 | 神圣、宏大、史诗 |
| **生物荧光** | bioluminescence | 生物自发光 | 奇幻、夜景、水下 |

### 1.2 按光线效果分类

| 效果类型 | 关键词 | 描述 |
|---------|-------|------|
| **高调光** | high-key lighting | 明亮均匀，阴影极少，画面干净 |
| **低调光** | low-key lighting / moody lighting | 暗调为主，高光稀少而珍贵 |
| **明暗对照** | chiaroscuro | 强烈明暗对比，艺术感强 |
| **柔和衰减** | soft falloff | 从亮到暗的温和过渡，如呼吸般自然 |
| **定向光束** | directional beam | 紧凑聚焦的光柱，选择性显露 |
| **光晕** | glow / halo / bloom | 光线在边缘扩散 |
| **光斑** | light flare / lens flare | 镜头反射形成的光斑 |
| **丁达尔效应** | tyndall effect / volumetric rays | 光线穿过胶体或雾气的可见路径 |
| **背光柔和光晕** | backlit soft glow | 主体边缘梦幻发光效果 |
| **反射光** | reflected light / bounce light | 环境反射的自然补光 |
| **剪影** | silhouette | 主体全黑，背景明亮 |

### 1.3 11种漫射氛围（光影胶囊）

| 氛围类型 | 关键词 | 特点 | 视觉感受 |
|---------|-------|------|---------|
| **迷雾** | misty | 细微悬浮水分散射光线，边缘渐次消失 | 距离感逐渐溶解，静谧 |
| **朦胧/霾** | hazy | 充满颗粒的空气，远处褪色柔化 | 大气透视，空间阻隔感 |
| **乳白光** | opalescent | 光线折射出微妙变幻的色调 | 虹彩效果，不稳固的色彩 |
| **去饱和** | desaturated | 有意去除色彩强度，保留色调和明度 | 克制、距离、情感宁静 |
| **漫射** | diffused | 失去方向性的光，均匀柔和铺开 | 统一和谐，万物各得其所 |
| **乳白/奶质感** | milky | 光线变厚成为发光物质，白色晕开 | 光线有触感，如液体般 |
| **面纱/含蓄** | veiled | 观者与场景间有半透明层 | 被保留的存在，克制 |
| **珍珠光泽** | pearlescent | 珍珠般柔和内部光泽 | 珍贵、静谧、亲密 |
| **漂白/过曝** | bleached | 被光线淹没，色彩因曝光剥离 | 干旱、失去强度 |
| **柔化** | softened | 锐度被轻柔磨圆，边缘放松 | 舒适、亲密、视觉仁慈 |
| **水洗/冲淡** | washed | 均匀抽离对比度和色彩 | 被阳光耗尽，安静擦除 |

---

## 2. 光线时段

| 时段 | 英文关键词 | 特点 | 色温 | 最佳应用 |
|-----|-----------|------|------|---------|
| **黄金时刻** | golden hour | 日出后/日落前1小时，温暖的橙金色光线，长阴影 | 暖色(3000-4000K) | 风景、人像、氛围大片 |
| **蓝调时刻** | blue hour | 日出前/日落后，深邃蓝色天空，柔和光线 | 冷色(9000-12000K) | 城市夜景、静谧氛围 |
| **黎明** | dawn / daybreak | 光线从暗到亮的过渡期，薄雾弥漫 | 冷转暖 | 梦幻、清晨风景 |
| **黄昏** | dusk / twilight | 日落后的光线过渡期 | 暖转冷 | 浪漫、剪影 |
| **正午** | noon / midday sun | 强烈顶光，高对比度，阴影短 | 中性(5500K) | 纪实、高对比风格 |
| **清晨柔光** | early morning soft light | 低角度柔和光线，薄雾常见 | 暖(3500-4500K) | 风景、田园 |
| **傍晚暖光** | late afternoon warm light | 角度低，拉长阴影，温暖色调 | 暖(3000-4000K) | 人像、生活记录 |
| **深夜** | midnight / deep night | 仅有月光或人造光源 | 冷色为主 | 夜景、神秘、孤独 |
| **阴天** | overcast / cloudy | 云层作为天然柔光箱，光线均匀 | 中性偏冷 | 人像、静物、细节 |
| **魔幻时刻** | magic hour | 黄昏与夜晚交界，天空色彩丰富 | 冷暖交织 | 任何场景都极佳 |

---

## 3. 布光方案

### 3.1 经典摄影布光

| 布光方案 | 英文关键词 | 描述 | 适用场景 |
|---------|-----------|------|---------|
| **三点布光** | three-point lighting | 主光(key) + 补光(fill) + 轮廓光(rim/back) | 标准人像、访谈 |
| **伦勃朗布光** | Rembrandt lighting | 45度侧光，在面部暗侧形成三角形高光 | 经典肖像、戏剧人像 |
| **环形光** | loop lighting | 主光略高于眼睛，鼻影呈环形 | 商业人像、日常人像 |
| **蝴蝶光** | butterfly lighting | 主光在相机正上方，鼻下形成蝴蝶形阴影 | 时尚、女性人像 |
| **分割光** | split lighting | 光源来自正侧方，面部一半亮一半暗 | 戏剧、男性、神秘 |
| **环形灯** | ring light | 环形光源从相机位置照明 | 美妆、自拍、网红 |
| **宽光** | broad lighting | 面部朝向相机的一侧被照亮 | 让脸显宽 |
| **窄光** | short lighting | 面部远离相机的一侧被照亮 | 让脸显瘦、雕塑感 |
| **侧逆光** | side-backlight | 光从主体侧后方照射 | 梦幻、轮廓强调 |

### 3.2 单光艺术（Single Light Anatomy）

| 要素 | 变量 | 效果 |
|-----|------|------|
| **方向** | 侧光(side light) | 创造神秘感，雕刻轮廓 |
| | 顺光(front light) | 揭示真理，平坦细节 |
| | 逆光(backlight) | 唤起记忆，梦幻氛围 |
| **距离** | 近光(near light) | 柔和情感，平滑渐变，会呼吸的纹理 |
| | 远光(far light) | 边缘对比，鲜明情感存在 |
| **大小** | 大面积光源 | 柔光效果 |
| | 点光源 | 硬光效果 |

### 3.3 Meta Tokens — 光影渲染信号

光影类Meta Tokens可引导AI的渲染行为：

| 类别 | 关键词 |
|------|-------|
| **核心真实感** | photorealistic, natural lighting, HDR photography, global illumination, physically accurate materials |
| **光影特定** | natural directional sunlight, soft interior bounce light, warm ambient light, subtle shadow gradients |
| **相机特定** | 24mm wide-angle lens, deep depth of field, eye-level perspective |

---

## 4. 天气氛围

### 4.1 各种天气的氛围关键词

| 天气 | 关键词 | 光线特点 | 材质响应 |
|-----|-------|---------|---------|
| **晴天** | sunny / clear sky | 方向明确，高对比度 | 色彩鲜艳，阴影锐利 |
| **阴天** | overcast / cloudy | 天然柔光，低对比度 | 细节丰富，色彩均匀 |
| **雾天** | foggy / misty / hazy | 光线散射，对比度降低 | 微观对比降低，距离感模糊 |
| **雨天** | rainy / wet / rain | 光线折射，反射增多 | 表面光泽感增强，水坑倒影 |
| **雪天** | snowy / frost / ice | 光线散射，明亮柔和 | 雪面散射光，材质明亮 |
| **风暴** | stormy / thunder | 戏剧性光线，明暗强烈 | 动态感强，对比极端 |
| **雨后** | after rain | 空气清新，反射丰富 | 湿润质感，水珠/水坑 |
| **黎明雾** | dawn fog / morning mist | 柔和渐变，低对比 | 一切半透明，梦幻 |
| **暴风雪** | blizzard | 几乎零能见度 | 动态模糊，白色笼罩 |
| **热浪** | heat shimmer | 空气扭曲 | 远处物体扭曲变形 |

### 4.2 冬日氛围专有词库

| 概念 | 关键词 | 描述 |
|-----|-------|------|
| **朦胧晨雾** | dim morning haze | 缺乏亮度、对比、锐度的冬日早晨 |
| **薄雾灰** | mist grey | 珍珠灰、灰蓝色、柔和白的融合 |
| **霜辉** | frost glow | 淡薰衣草色、银白色、浅丁香紫在霜面闪烁 |
| **隐日之色** | hidden sun tint | 稀释的杏色、腮红米——几乎不可见的温暖 |
| **阴影色调** | shadow tint | 钢灰色、冷紫红——忧郁的底色 |
| **凝冻之光** | frozen light | 被困在湿气和霜冻中的光照，悬浮、静默 |
| **柔和距离** | soft distance | 雾气减少背景细节，深度变为渐变 |
| **冬日去饱和** | winter desaturation | 自然色彩被洗刷成灰蓝色 |

### 4.3 柔和极光氛围（Soft Polar Light）

| 元素 | 关键词 |
|------|-------|
| **引导词** | polar dawn, diffused sunlight, frost haze, refracted glow, pearl-white ambience, arctic mist, horizon blush, icy shimmer, frozen breath, crystalline air |
| **色系** | pale blue, silver white, blush rose, lavender mist, pearl grey |
| **情绪** | introspective, ethereal, quiet, contemplative, cinematic stillness |
| **相机设置** | Canon EOS R5, 85mm f/1.2, ISO 100, aperture f/2.2, HDR capture |

---

## 5. 四大核心支柱（摄影级真实风景）

> 来源：《告别AI塑料感！Midjourney生成摄影级真实风景的底层逻辑与万能公式》

每一张令人信服的真实风景图，都建立在以下四个基础之上。缺少任何一个，真实的错觉就会瞬间崩塌。

### 支柱一：深度（Depth）— 空间的构建方式

**原理**：风景之所以真实，是因为它有结构——不是视觉上的复杂堆砌，而是空间上的清晰明确。

**关键方法**：**三层法则**（见第6节）

**提示词要素**：
- 前景锚定：sharp textured rocks in the foreground
- 中景引导：curved shoreline guiding through the midground
- 背景尺度：distant ocean horizon fading into light haze

### 支柱二：大气/氛围（Atmosphere）— 距离感的表现方式

**原理**：远处的景物永远不可能是绝对清晰的。没有空气透视，Midjourney会生成"扁平的无限远"。

**空气透视特征**：物体离得越远 → 对比度越低 → 色温越偏冷调 → 边缘越显柔和

**可添加元素**：薄雾(mist)、浓雾(fog)、盐雾(salt haze)、尘霾(dust haze)、雨幕(rain veils)、热浪扭曲(heat shimmer)

### 支柱三：光线（Light）— 场景的展现方式

**核心法则**：**永远只选择一种主光源**。千万不要混合冲突的光线方向，那是打破真实感最快的"翻车"捷径。

**方向选择**：
- 侧光(Side Light) → 展现纹理和地形起伏
- 逆光(Backlight) → 创造光晕和绝佳氛围感
- 阴天/漫射光(Overcast) → 消除强烈对比，完美展现细节
- 蓝调时刻(Blue Hour) → 让一切变得柔和深邃
- 黄金时刻(Golden Hour) → 拉长阴影，增强立体浮雕感

### 支柱四：材质（Material）— 物质对环境条件的反应

**核心法则**：**材质必须与天气相匹配**。如果材质的质感和天气对不上，即使其他所有细节都完美无瑕，画面依然会散发出AI人工痕迹。

| 环境条件 | 材质表现 |
|---------|---------|
| 湿岩石 | 具有反射性、颜色变深、出现高光 |
| 干沙 | 哑光质感、漫反射光 |
| 雪 | 明亮、柔和、光线发生散射 |
| 雾 | 降低微观对比度 |
| 雨 | 增加光泽感和水面反射 |

---

## 6. 三层法则（前景/中景/背景）

> 核心方法：用三个层次构建空间世界

| 层次 | 角色 | 功能 | 典型元素 |
|------|------|------|---------|
| **前景（Foreground）** | 定海神针（锚点） | 观者"进入"画面的物理切入点 | 岩石、青草、沙纹、浮木、雪地纹理 |
| **中景（Midground）** | 视觉通道 | 视线游走和延伸的路径 | 河湾、小径、海岸线、林木线 |
| **背景（Background）** | 气场所在 | 赋予画面尺度感和宏大感 | 群山、地平线、风暴墙、远山脊线 |

**核心理念**：没有前景，图片就只是平面装饰。有了前景，它才变成一个可以让人身临其境的空间。

**提示词模板**：
```
Landscape photograph of [场景],
sharp textured [前景元素] in the foreground with wet reflections,
[中景元素] guiding through the midground,
distant [背景元素] fading into soft atmospheric haze,
[光线方向] creating gentle shadows,
natural color palette, Sony A7R V, [焦段]mm, f/11, ISO 100
```

### 景深增强技巧

- **强制划分平面**：用前景物体（树枝、石头、草丛）创造物理切入感
- **调整光线**：光线要有层级，主次分明
- **运用相机逻辑**：指定光圈(f/2.8背景虚化 / f/11全景清晰)
- **使用留白**：负空间增强纵深感
- **引导线**：用河湾、小径、海岸线等引导视线

---

## 7. 空气透视原理（Atmospheric Perspective）

### 核心原理

在现实生活中，物体距离越远：
1. **对比度越低**
2. **色温越偏冷调**
3. **边缘越显柔和**

### 关键词

| 概念 | 英文关键词 |
|------|-----------|
| **空气透视** | atmospheric perspective |
| **薄雾** | mist / thin mist |
| **浓雾** | dense fog |
| **盐雾** | salt haze |
| **尘霾** | dust haze |
| **雨幕** | rain veils |
| **热浪扭曲** | heat shimmer |
| **大气薄雾** | atmospheric haze |
| **蓝色雾气** | blue haze / blue atmospheric haze |
| **距离感** | sense of distance / depth perception |
| **层叠山脊** | layered ridgelines |
| **渐次模糊** | progressive blur / graduated softness |

### 提示词模板（空气透视）

```
Mountain landscape photograph with layered ridgelines,
rocky foreground in sharp focus,
midground forest slightly softened,
distant mountains fading into blue atmospheric haze,
natural daylight, Sony A1, 70mm, f/11, ISO 100
```

**为什么有效？**
- 前景极致锐利 → 锚定现实
- 中景柔和过渡 → 自然渐变
- 背景消隐于蓝色雾气 → 真实深度感知

---

## 8. 电影感柔光 — 核心法则

> 来源：《告别"AI塑料感"！Midjourney打造高级电影感柔光的终极指南》

### 核心问题
强硬光线会导致：强烈阴影、不自然对比度、浓重"AI生成痕迹"

### 黄金法则
使用**柔和漫反射光**（soft diffused lighting）模拟真实物理环境光线：
- 阴云密布的天空
- 窗边透过的自然光
- 雾气或大气的漫反射效果

### 实操关键词

| 推荐使用 | 避免使用 |
|---------|---------|
| soft diffused lighting | direct sunlight |
| overcast light | strong shadows |
| window light | harsh lighting |
| fog / mist / dust particles | hard shadows |

### 进阶大神技巧
- **柔光**（soft light）= 阴影几乎不可见
- **体积光**（volumetric light）→ 大幅提升电影级景深感
- **背光柔和光晕**（backlit soft glow）→ 为主体边缘勾勒梦幻效果
- **柔光 + 纹理**（soft light + texture）→ 质感与真实度拉满
- **一键升级**：overcast lighting + atmospheric haze → 瞬间消除生硬对比

### 镜头搭配建议

| 焦段 | 效果 | 适用场景 |
|------|------|---------|
| 35mm | 沉浸感强，同时捕捉环境和主体 | 风景、室内、环境人像 |
| 50mm | 透视自然，宛如肉眼所见 | 人像、静物、日常 |
| 85mm | 压缩背景，主体突出 | 肖像、特写 |
| 100mm macro | 极致细节 | 微距、产品、纹理 |

### 光圈策略

| 光圈 | 效果 |
|------|------|
| f/1.2 - f/2 | 极浅景深，背景融化，情绪集中 |
| f/2.8 | 柔和虚化，兼顾环境 |
| f/4 - f/5.6 | 多平面清晰，风景适用 |
| f/8 - f/11 | 全景清晰，最大景深 |

---

## 9. 梦幻魔法草地 — 光影特例

> 来源：《【MJ神仙教程】光影的极致温柔》

### 核心法则
**漫反射光 + 柔和渐变 + 微妙光晕 + 大气层级感**

不是在描述一个地方，而是在描述关于某个地方的记忆。

### 5个核心要素

| 要素 | 描述 | 关键词 |
|------|------|-------|
| 1. 柔和光线 | 拒绝刺眼，黄金时刻/漫反射日光 | soft glow, luminous haze, backlit |
| 2. 色彩和谐 | 轻柔低饱和，柔和粉彩 | pastel tones, muted greens |
| 3. 氛围层次 | 薄雾、花粉、漂浮颗粒 | atmospheric depth, floating particles |
| 4. 动态感 | 风、花瓣、流转光影 | gentle breeze, bending grass, motion |
| 5. 故事元素 | 小路、身影、被遗忘的物品 | winding path, distant figure |

### ❌ 错误写法 vs ✅ 正确写法

```
❌ "flower meadow with trees"
✅ "rolling meadow covered in soft wildflowers, drifting pollen glowing in backlight, gentle breeze bending tall grass, pastel sky dissolving into warm haze"
```

---

## 10. 霓虹光影美学

> 来源：《MJ进阶指南 | 霓虹光影美学》

### 霓虹灯的三个关键作用
1. **取代太阳**：霓虹成为主光源，不再有自然光逻辑
2. **为阴影上色**：阴影变成紫色、青色、洋红色
3. **创造质感表面**：需要反射材质才能展现生命力

### 色彩搭配推荐

| 配色 | 氛围 |
|------|------|
| 粉色/青色 (pink/cyan) | 梦幻未来 |
| 红色/蓝色 (red/blue) | 经典冲突 |
| 紫色/青色 (violet/teal) | 神秘深邃 |
| 洋红/电光绿 (magenta/electric green) | 赛博朋克 |

---

## 11. 月光氛围

> 来源：《月影回响：10组Midjourney柔和月光摄影提示词精选》

### 核心视觉原则
- **单一月光源**（切勿与强烈灯光混合）
- **冷色调主导**（银色、淡蓝色、柔和丁香紫）
- **柔和对比**（避免死黑）
- **材质至上**（薄雾、织物、石头、水面、呼吸白气）
- **留白是构图的一部分**

### 月光摄影关键词
| 类别 | 关键词 |
|------|-------|
| **光线** | pale moonlight, silver light, soft lunar glow, moonlit |
| **色彩** | cool monochrome, silver-blue, pale lavender, deep blue shadows |
| **氛围** | nocturnal, quiet, contemplative, cinematic stillness, emotional solitude |
| **相机** | long exposure, ISO 640-1250, f/1.4-f/2, subtle grain |

---

## 12. 破解"塑料感" — 光线控制法

> 来源：《拒绝"塑料感"！揭秘 Midjourney 默认的"完美滤镜"与破解指南》

### 三种过度平滑问题
1. **表面平滑**：材质纹理被抹平
2. **光线平滑**：光影过渡过于均匀
3. **情感平滑**：情绪张力被削弱

### 光线破解法
- 使用**硬光**（harsh directional light）→ 光线塑造边缘，边缘抗拒平滑
- 使用**强阴影**（strong shadows）
- 使用**轮廓光**（rim lighting）
- 使用**低角度阳光**（low-angle sunlight）
- 避免"完美信号"词：ultra clean, perfect lighting, studio quality
- 替换为：documentary style, unfiltered, cinematic realism

### 镜头选择对质感的影响
| 焦段 | 质感效果 |
|------|---------|
| 85mm | 空间压缩 → 看起来更平滑 |
| 35mm | 更自然的质感 |
| 24mm | 夸张深度和瑕疵 → 更真实 |

---

## 13. 胶片颗粒 — 光影的物理质感

> 来源：《告别"塑料感"！Midjourney 胶片颗粒全指南》

### 四种颗粒描述词

| 类型 | 关键词 | 效果 | 适用题材 |
|------|-------|------|---------|
| **柯达胶片颗粒** | subtle Kodak film grain | 柔和颗粒，平衡色调，自然肤色 | 人像、旅行、纪实 |
| **电影胶片颗粒** | cinematic film grain | 略强颗粒，戏剧光影，氛围感阴影 | 夜景、电影剧照、叙事 |
| **精细模拟颗粒** | fine analog grain texture | 几乎隐形，微观不规则性 | 微距、皮肤纹理、植物 |
| **纪实胶片颗粒** | documentary film grain | 原始观察，略显粗糙，自然光照 | 街头、报道、历史氛围 |

### 强化信号
- analog photography → 暗示物理胶片捕捉
- film stock texture → 激活胶片材料视觉记忆
- vintage film look → 怀旧色调表现
- natural sensor grain → 模拟真实数码相机噪点
