# 材质与形容词词库

> 知识来源：AI绘画提示词知识库（10篇核心文章蒸馏）
> 内容涵盖：材质分类、形容词分类、材质-天气匹配规则、场景组合推荐

---

## 1. 材质分类

### 1.1 金属材质

| 材质 | 英文关键词 | 反射特性 | 典型应用 |
|------|-----------|---------|---------|
| **镀铬** | chrome / chromium finish | 锐利的镜面反射 | 汽车、未来主义、科幻 |
| **拉丝金属** | brushed metal / brushed steel | 拉伸的反射，有方向性 | 工业设计、现代家居 |
| **抛光金属** | polished metal / polished steel | 高反射，清晰倒影 | 珠宝、雕塑、豪华 |
| **粗糙金属** | rough metal | 漫反射为主 | 工业、复古 |
| **氧化金属** | oxidized metal | 哑光与反射并存 | 做旧、工业风 |
| **生锈金属** | rusted metal | 色彩丰富，表面粗糙 | 废土、复古、纪实 |
| **哑光金属** | matte metal | 柔和反射 | 现代简约、高端 |
| **金色** | gold / golden | 温暖高反射 | 奢华、古典、宗教 |
| **银色** | silver | 中性高反射 | 未来、科技 |
| **铜** | copper / bronze | 暖色反射 | 复古、工业、蒸汽朋克 |
| **液态金属** | liquid metal / molten metal | 流动的镜面 | 抽象、奇幻 |

**核心法则**（来源：《告别塑料感！Midjourney金属反光高阶完全指南》）：
> 不要去描述金属本身，去描述它所反射的事物。
> 金属 = 镜子，必须定义：环境、光源、对比区域

**金属质感四要素**：
1. **反射内容**：chrome helmet reflecting a sunset skyline with warm orange light gradients
2. **表面表现**：抛光→锐利反射 / 拉丝→拉伸反射 / 粗糙→漫反射
3. **光影结构**：高光 + 渐变过渡 + 边缘反射
4. **对比区域**：明亮高光 + 深邃阴影 + 中间调渐变

### 1.2 自然材质

| 材质 | 英文关键词 | 视觉特点 |
|------|-----------|---------|
| **岩石/石头** | rock / stone | 粗糙、硬朗、纹理多样 |
| **湿润岩石** | wet rock | 反射性、颜色变深、出现高光 |
| **光滑鹅卵石** | smooth pebbles / river stones | 水磨质感 |

| **沙** | sand | 颗粒感，哑光 |
| **干沙** | dry sand | 哑光质感，漫反射光 |
| **湿沙** | wet sand | 颜色变深，反射增强 |
| **泥土** | soil / dirt / earth | 不规则的天然质感 |
| **木材** | wood / timber / wooden | 纹理方向明确，温润 |
| **枯木/浮木** | driftwood | 风化的粗糙表面 |
| **草地** | grass / grassland | 纤维质感，动态感 |
| **苔藓** | moss | 柔软、绒面质感 |
| **树皮** | bark | 纵向纹路，粗糙 |
| **雪** | snow | 明亮、柔和、光线散射 |
| **冰** | ice | 半透明，有折射 |
| **霜** | frost | 结晶状，精致 |
| **水** | water | 反射、透明、流动 |
| **水面** | water surface | 反射和折射 |
| **水滴** | dew / water droplets | 微小透镜效果 |
| **叶子** | leaf / leaves | 半透明（逆光时） |
| **花瓣** | petal | 柔软、半透明 |
| **羽毛** | feather | 轻盈、纹理细腻 |
| **皮毛** | fur | 柔软、方向性纹理 |

### 1.3 织物材质

| 材质 | 英文关键词 | 视觉特点 |
|------|-----------|---------|
| **丝绸** | silk | 光泽感、顺滑、垂坠 |
| **天鹅绒** | velvet | 绒面、吸光、奢华 |
| **棉麻** | linen / cotton | 哑光、自然褶皱 |
| **羊毛** | wool | 蓬松、温暖质感 |
| **针织** | knit / knitted | 编织纹理，结构感 |
| **皮革** | leather | 自然纹理，随时间变化 |
| **做旧皮革** | worn leather / cracked leather | 划痕、包浆 |
| **牛仔布** | denim | 斜纹编织，耐磨质感 |
| **薄纱** | tulle / gauze | 半透明，轻盈 |
| **蕾丝** | lace | 精致镂空图案 |
| **帆布** | canvas | 粗糙、结实 |
| **粗麻布** | burlap / hessian | 极粗糙的编织 |
| **纺织物** | textile / fabric | 通用 |
| **磨损织物** | frayed fabric | 边缘破损的质感 |

### 1.4 艺术材质（绘画质感）

| 材质 | 英文关键词 | 视觉特点 | 核心词汇 |
|------|-----------|---------|---------|
| **油画** | oil painting | 颜料厚度+笔触压力+光线吸收与漫射 | thick impasto, oil-saturated pigment, visible brush ridges, slow blended transitions |
| **丙烯画** | acrylic painting | 速干，哑光到半光泽 | matte and semi-gloss, bold color blocking |
| **水彩** | watercolor | 透明、流动、晕染 | translucent washes, color bleeding |
| **素描** | sketch / pencil drawing | 线条感，黑白 | graphite texture, cross-hatching |
| **水墨/国画** | ink wash / sumi-e | 墨色浓淡变化 | ink wash, brush stroke, white space |
| **粉彩/色粉** | pastel | 柔软、粉末质感 | soft powdery texture, smudged |
| **蜡笔** | crayon / oil pastel | 厚重、蜡质感 | waxy buildup, grainy |
| **版画** | printmaking / woodcut | 线条锐利、重复图案 | carved lines, ink impression |
| **浮世绘** | ukiyo-e | 平涂色彩、黑线轮廓 | flat color, black outlines |
| **拼贴** | collage | 多层纸张或材料叠加 | layered paper, torn edges |
| **壁画** | mural / fresco | 墙面质感 | wall texture, faded pigments |
| **彩铅** | colored pencil | 精致、层叠色彩 | fine cross-hatching, layering |

**油画核心语法**（来源：《【MJ进阶】告别"滤镜感"！让像素像颜料一样呼吸》）：
- ✅ 使用：thick impasto, oil-saturated pigment, visible brush ridges, slow blended transitions, matte and semi-gloss paint interaction, pigment pooling in darker zones, canvas tooth visible beneath paint
- ❌ 避免：hyper-sharp, ultra-detailed, glossy finish, digital smoothness, photorealistic lighting

### 1.5 人造/合成材质

| 材质 | 英文关键词 | 视觉特点 |
|------|-----------|---------|
| **玻璃** | glass | 透明、折射、反射 |
| **水晶** | crystal | 高折射率，通透 |
| **陶瓷** | ceramic / porcelain | 光滑、硬朗、易碎 |
| **混凝土** | concrete | 灰色、多孔、冷硬 |
| **砖墙** | brick wall | 规则排列，粗糙 |
| **沥青** | asphalt | 黑色、颗粒感 |
| **塑料** | plastic | 光滑、无反光细节 |
| **橡胶** | rubber | 哑光、弹性质感 |
| **碳纤维** | carbon fiber | 编织纹理，高科技感 |
| **霓虹灯管** | neon tube | 发光、彩色、玻璃管 |
| **镜子** | mirror | 完美反射 |
| **磨砂玻璃** | frosted glass | 半透明，散射光线 |
| **镀铬** | chrome / chromium | 极高反射，镜面效果 |
| **珐琅** | enamel | 光滑、光泽、色彩鲜艳 |
| **树脂** | resin | 半透明、可塑性 |

**玻璃材质核心法则**（来源：《【AI绘画干货】高级感拉满！如何在Midjourney中用"玻璃"材质》）：
> 不要去描述物体本身，去描述它有多容易破碎。

**玻璃五维度**：

| 维度 | 描述 | 关键词 |
|------|------|-------|
| 1. 材质 | 选择透明易碎材质 | fragile glass, thin crystal, delicate translucent material, brittle edges |
| 2. 厚度 | 极致轻薄 | ultra-thin, fine edges, hollow glass, lightweight structure |
| 3. 光线表现 | 穿透、折射、散射 | soft refraction, subtle caustics, light diffusion, internal glow |
| 4. 瑕疵感 | 微小裂纹、气泡、划痕 | micro cracks, scratches, bubbles, uneven surfaces |
| 5. 情绪张力 | 临界破碎的不稳定感 | pressure, imbalance, suspension, falling moment |

---

## 2. 形容词分类

> 来源：《大师级提示词指南》+《那些年入几十万的AI画师，都在用这套"邪修"词库》

**使用原则**：
- 每个提示词使用 **3-6个** 强有力的形容词
- 混合**不同类别**而非堆砌近义词
- 从具体形容词入手，避免抽象
- 按：颜色 → 纹理 → 材料 → 灯光风格 → 设计美学 → 物理属性 的思路组合

### 2.1 颜色类

| 分类 | 形容词 |
|------|-------|
| **经典色** | vibrant, muted, pastel, monochrome, desaturated, monochromatic, colorful, vivid, saturated |
| **暖色调** | warm, golden, amber, rosy, fiery, sunset, honey, terracotta, bronze, ochre, sepia |
| **冷色调** | cool, icy, frosty, glacial, steel-blue, azure, cerulean, cobalt, indigo, teal, cyan |
| **中性色** | neutral, beige, taupe, greige, stone, slate, charcoal, ivory, cream, off-white |
| **柔和色** | soft, pale, washed, faded, dusty, powdery, misty, hazy, subdued, delicate |
| **大地色** | earthy, terracotta, sage, olive, umber, sienna, umber, khaki, sand, clay |
| **金属色** | metallic, golden, silver, bronze, copper, chrome, gunmetal, brass, iridescent |
| **特殊色** | monochromatic, analogous, complementary, analogous, discordant, jewel-toned |

### 2.2 纹理类

| 分类 | 形容词 |
|------|-------|
| **粗糙类** | rough, coarse, gritty, rugged, uneven, bumpy, jagged, abrasive, grainy, pebbled |
| **光滑类** | smooth, sleek, glossy, polished, silky, satiny, slippery, glassy, buttery, creamy |
| **柔软类** | soft, plush, velvety, fuzzy, fluffy, fleecy, downy, feathery, silken, velour |
| **硬朗类** | hard, rigid, stiff, solid, firm, dense, compact, unyielding, sturdy, tough |
| **自然类** | organic, weathered, rustic, cracked, wrinkled, patinated, mossy, bark-like, rippled |
| **精致类** | intricate, detailed, delicate, fine, subtle, refined, ornate, elaborate, filigree |
| **磨损类** | worn, aged, distressed, faded, chipped, scratched, frayed, tattered, faded, rusted |
| **透明类** | translucent, transparent, clear, sheer, see-through, diaphanous, gauzy, crystalline |
| **光泽类** | shiny, lustrous, gleaming, sparkling, glittering, glistening, shimmering, radiant, iridescent |
| **哑光类** | matte, dull, flat, non-reflective, low-sheen, absorbent, chalky, powdery |

### 2.3 材料类

| 分类 | 形容词 |
|------|-------|
| **金属质感** | metallic, crystalline, steely, brassy, golden, silvery, coppery, pewter-like, liquid-metal |
| **石质质感** | stony, rocky, pebbly, gravelly, sandy, dusty, earthy, clay-like, loamy |
| **木质感** | woody, grainy, knotty, varnished, timbered, bark-textured |
| **织物感** | silken, velvety, satiny, fleecy, woolly, cottony, linen-like, lace-like, brocaded |
| **液态感** | liquid, fluid, molten, flowing, aqueous, dewy, damp, moist, hydrated |
| **半透明感** | translucent, crystalline, glassy, frosty, milky, hazy, opalescent, pearlescent |

### 2.4 灯光风格类

| 分类 | 形容词 |
|------|-------|
| **强度** | bright, dim, soft, harsh, intense, subdued, radiant, luminous, glaring |
| **方向** | directional, diffused, ambient, side-lit, back-lit, front-lit, top-lit, rim-lit |
| **质量** | warm, cool, neutral, crisp, hazy, golden, silvery, ruddy, amber, pearlescent |
| **风格** | cinematic, dramatic, moody, ethereal, theatrical, natural, environmental, artistic, film noir |
| **效果** | glowing, shimmering, flickering, pulsing, streaming, dappled, speckled, rippling |
| **氛围** | atmospheric, ambient, moody, evocative, dreamy, hazy, misty, luminous, incandescent |

### 2.5 设计美学类

| 分类 | 形容词 |
|------|-------|
| **现代** | modern, contemporary, minimalist, sleek, streamlined, clean, geometric, industrial |
| **复古** | vintage, retro, antique, classic, nostalgic, old-world, Victorian, Edwardian, mid-century |
| **自然** | organic, rustic, pastoral, earthy, natural, wild, untamed, botanical, woodland |
| **极简** | minimal, clean, simple, uncluttered, sparse, restrained, pure, essential |
| **奢华** | luxurious, opulent, lavish, ornate, extravagant, sumptuous, regal, majestic |
| **粗犷** | raw, rugged, tough, brutal, unpolished, industrial, weathered, distressed |
| **浪漫** | romantic, dreamy, whimsical, delicate, tender, soft, gentle, sweet |
| **暗黑** | dark, gothic, moody, mysterious, somber, melancholic, brooding, ominous |
| **科幻** | futuristic, sci-fi, cyberpunk, dystopian, techno, biomechanical, cosmic |
| **奇幻** | fantasy, magical, mystical, enchanted, surreal, ethereal, mythical, fairy-tale |
| **纪实** | documentary, authentic, honest, raw, unfiltered, candid, editorial, photojournalistic |
| **电影感** | cinematic, epic, dramatic, atmospheric, narrative, storytelling, film-still |

### 2.6 物理属性类

| 分类 | 形容词 |
|------|-------|
| **重量** | heavy, light, weighty, massive, feathery, airy, buoyant |
| **密度** | dense, thick, compact, solid, porous, permeable, hollow |
| **温度** | hot, warm, cool, cold, icy, fiery, lukewarm, frosty |
| **湿度** | wet, dry, damp, moist, humid, arid, parched, saturated, dewy |
| **透明度** | transparent, translucent, opaque, clear, cloudy, misty, hazy |
| **反光率** | reflective, matte, glossy, shiny, dull, mirror-like, non-reflective |
| **弹性** | elastic, rigid, flexible, stiff, malleable, pliable, brittle |
| **温度感** | frigid, glacial, tepid, searing, scorching, balmy, crisp, biting |
| **时间感** | aged, weathered, new, fresh, pristine, antique, vintage, contemporary |

---

## 3. 材质与天气匹配规则

> 核心原则：材质必须对天气条件做出正确的物理响应

### 3.1 湿/雨天

| 材质 | 表现 | 关键词 |
|------|------|-------|
| 岩石 | 反射性、颜色变深、出现高光 | wet rocks with reflections |
| 路面 | 光泽感增强，倒影 | wet pavement, reflections, sheen |
| 植物 | 水珠附着，更鲜亮 | dew-covered, moisture-laden |
| 建筑 | 表面湿润反光 | damp facade, rain-streaked |
| 玻璃 | 水珠聚集，模糊视线 | water droplets, rain on glass |
| **典型提示词** | after rainfall, wet stones reflecting soft light, damp soil textures, shallow puddles creating subtle reflections |

### 3.2 干燥/晴天

| 材质 | 表现 | 关键词 |
|------|------|-------|
| 沙地 | 哑光质感，漫反射 | dry sand, matte texture |
| 岩石 | 粗粝、坚硬、颜色浅 | sun-baked rocks, dry stone |
| 土地 | 干燥开裂 | cracked earth, parched ground |
| 植物 | 略显枯黄，缺乏水分 | sun-dried, withered |

### 3.3 雪天/寒冷

| 材质 | 表现 | 关键词 |
|------|------|-------|
| 雪面 | 明亮、柔和、光线散射 | fresh snow, powdery snow, light scattering |
| 冰面 | 半透明、折射 | crystalline ice, frozen surface |
| 霜面 | 精致结晶 | frost-covered, rime ice |
| 水面 | 结冰，失去流动感 | frozen lake, icy surface |
| 建筑 | 积雪覆盖，边缘圆润 | snow-capped, frost-laden |
| **典型氛围** | winter desaturation, frozen light, frost haze, crystalline air |

### 3.4 雾天

| 材质 | 表现 | 关键词 |
|------|------|-------|
| 所有材质 | 微观对比度降低 | softened, muted, veiled |
| 远景 | 对比度降低，色温偏冷 | faded, atmospheric haze |
| 光线 | 散射柔和，无锐利阴影 | diffused, scattered, soft |
| 水面 | 与雾融合，界限模糊 | misty surface, obscured horizon |

### 3.5 风暴/强风

| 材质 | 表现 | 关键词 |
|------|------|-------|
| 植被 | 动态弯曲，被压弯 | wind-blown, bent, flattened |
| 水面 | 波纹剧烈 | choppy, turbulent, whitecaps |
| 天空 | 厚重云层，戏剧性光线 | storm clouds, dramatic overcast |
| 建筑 | 承受风力冲击 | wind-swept, battered |

---

## 4. 常用材质描述词组合

### 4.1 按场景推荐

#### 梦幻草地/自然场景
```
rolling meadow, soft wildflowers, drifting pollen glowing in backlight, gentle breeze bending tall grass, pastel sky dissolving into warm haze, dew-kissed petals, luminous morning mist
```

#### 海洋/海岸场景
```
wet stones, reflective tidal pools, damp sand with ripples, sea-worn driftwood, salt-crusted rocks, misty horizon, foam-flecked waves
```

#### 森林/林间场景
```
moss-covered bark, dappled sunlight through canopy, soft fallen leaves, damp earth, fern fronds with dew, translucent green leaves in backlight, layered atmospheric depth
```

#### 冬日/雪景
```
fresh powder snow, frost-covered branches, crystalline ice, frozen breath, pearl-white ambience, hoarfrost on grass, steel-grey mist, pale blue shadows
```

#### 赛博朋克/夜景
```
wet asphalt reflecting neon, chrome surfaces with color streaks, rain-slicked glass, glowing signs, metallic sheen, iridescent puddles, glossy reflections on polished surfaces
```

#### 室内/家居
```
worn leather with patina, linen with natural wrinkles, wooden table with scratches, dust particles in warm light, imperfect surfaces, uneven textures, visible grain
```

#### 金属/机械
```
polished chrome reflecting environment, brushed steel with directional grain, oxidized copper patina, rusted iron texture, liquid metal flow, mirror-like reflections
```

#### 玻璃/水晶
```
thin translucent surfaces, micro cracks, trapped air bubbles, internal glow, soft refraction, paper-thin edges, fragile structure
```

### 4.2 邪修词库 — 光影与氛围篇

> 来源：《那些年入几十万的AI画师，都在用这套"邪修"词库》

| 词库 | 用途 | 效果 |
|------|------|------|
| **Cinematic lighting** | 电影级光照 | 营造大片感 |
| **Volumetric lighting** | 体积光/丁达尔效应 | 增加空间通透感 |
| **Rim light** | 轮廓光 | 勾勒主体边缘，增强立体感 |
| **Bioluminescence** | 生物荧光 | 奇幻或夜景题材 |
| **God rays** | 耶稣光/神圣光线 | 营造神圣或宏大氛围 |
| **Soft illumination** | 柔和照明 | 人像或静物，光线细腻 |
| **Neon ambiance** | 霓虹氛围 | 赛博朋克或夜景必备 |
| **Chiaroscuro** | 明暗对照法 | 强烈明暗对比，艺术感强 |
| **Global illumination** | 全局光照 | 模拟真实光线反射 |
| **Moody lighting** | 情绪化打光 | 营造忧郁或神秘叙事氛围 |

### 4.3 邪修词库 — 材质与修饰篇

| 词库 | 用途 | 效果 |
|------|------|------|
| **Translucent skin** | 半透明皮肤/次表面散射 | 人像更真实 |
| **Iridescent texture** | 彩虹色/珠光纹理 | 色彩变化丰富 |
| **Metallic sheen** | 金属光泽 | 适合机械或盔甲 |
| **Porcelain texture** | 陶瓷质感 | 光滑、易碎、高雅 |
| **Fluid simulation** | 流体模拟 | 水流、烟雾动态效果 |
| **Double exposure** | 双重曝光 | 画面融合（人像+风景） |
| **Dispersion effect** | 破碎/消散效果 | 粒子飞散 |
| **Chromium finish** | 镀铬表面 | 极强镜面反射 |
| **Filigree pattern** | 金银丝细工/掐丝图案 | 繁复装饰纹样 |

### 4.4 提升画面质感的1000个梦幻提示词 — 核心组合公式

> 来源：《提升AI画面质感的1000个梦幻提示词》

**组合逻辑**：按「光影氛围 → 材质肌理 → 色彩调性 → 风格/镜头」的顺序搭配

**色彩氛围类**：
| 类别 | 关键词 |
|------|-------|
| 主色调 | 莫兰迪、马卡龙、大地色、靛蓝色、琥珀色 |
| 色彩氛围 | 高饱和、柔和过渡、强烈对比、复古怀旧、清新治愈、梦幻色彩 |
| 色彩细节 | 复古棕、天空蓝、樱花粉、祖母绿、焦糖色、奶油白、茱萸粉 |

**细节质感类**：
| 材质 | 关键词 |
|------|-------|
| 玻璃 | 玻璃磨砂 |
| 丝绸 | 丝绸光泽 |
| 棉麻 | 棉麻粗糙 |
| 木质 | 木质温润 |
| 金属 | 金属冷硬 |

**特殊效果类**：
| 类型 | 关键词 |
|------|-------|
| 特效元素 | 烟雾、火焰、彩虹、极光、闪电、魔法粒子、光晕 |
| 技术效果 | 透明叠加、双重曝光、故障艺术、动态模糊、静态清晰、3D立体 |
| 创意叠加 | 虚实结合、画中画、倒影、镜像、光影交错、时空穿越感 |

### 4.5 "句子优先法" — 材质与纹理图层

> 来源：《告别提示词堆砌！Midjourney"句子优先法"》

提示词结构：**[核心句], [镜头逻辑], [光影语法], [材质精度]**

材质与纹理是第三个受控图层，需要精准描述：
```
[主体+动作+背景], [镜头焦段+光圈], [光线类型+方向], [材质表现+表面细节+瑕疵]
```

### 4.6 10个摄影级光影短语速查

| 编号 | 光影短语 | 效果 | 英文关键词 |
|------|---------|------|-----------|
| 1 | 柔和的窗前自然光 | 温馨肖像布景 | soft natural window light |
| 2 | 黄金时刻光影 | 温暖情感户外 | golden hour lighting |
| 3 | 戏剧性侧光 | 高对比电影感 | dramatic side lighting |
| 4 | 柔光背光效果 | 梦幻空灵 | backlit with a soft glow |
| 5 | 电影感光效 | 电影剧照张力 | cinematic lighting |
| 6 | 压抑暗调光效 | 深沉情感色调 | moody low-key lighting |
| 7 | 高调光效 | 明亮干净 | high-key lighting |
| 8 | 轮廓光 | 边缘定义 | rim lighting |
| 9 | 柔和散射光 | 讨喜温柔 | diffused soft lighting |
| 10 | 硬核直射光 | 大胆前卫 | harsh direct light |

---

## 5. 提示词万能公式 — 组合模板

### 大师级风景提示词模板（融合四大支柱）

```
Landscape photograph of [场景],
textured [前景元素] in the foreground,
[中景元素] leading through the midground,
distant [背景元素] fading into [大气效果],
[光线方向] creating [阴影/光效],
[天气条件] enhancing [材质表现],
natural color palette, high detail but soft distance,
[相机型号], [焦段]mm, f/[光圈], ISO [感光度]
```

### 电影感柔光模板

```
[主体描述],
soft diffused [光源类型] lighting,
[氛围元素],
[色彩描述] color palette,
[景深控制] depth of field,
cinematic atmosphere,
shot on [相机], [焦段]mm lens, f/[光圈],
[胶片风格] color grading
```

### 摄影级人像模板（5个真实摄影要素）

> 来源：《你的人像为什么总是"像AI"？因为少了这5个真实摄影要素》

1. **真实光影** → natural window light / soft diffused lighting
2. **皮肤纹理** → natural skin texture, subtle imperfections, pores, fine lines
3. **环境叙事** → lived-in space, personal details, authentic setting
4. **镜头逻辑** → 指定焦段、光圈、景深
5. **色彩科学** → realistic skin tone, natural color grading, film stock

---

## 6. 破解"塑料感" — 材质增强对照表

| 塑料感来源 | 问题 | 破解方案 | 替换词汇 |
|-----------|------|---------|---------|
| 表面过度平滑 | 纹理丢失 | 加入材质描述词 | rough concrete, oxidized metal, frayed fabric, dust particles |
| 光线过于均匀 | 无层次 | 使用定向硬光 | harsh directional light, strong shadows, rim lighting |
| 完美无瑕感 | 虚假 | 声明不完美为意图 | uneven texture, visible grain, imperfect surfaces, raw aesthetic |
| 色彩太艳 | 失真 | 降低饱和度 | desaturated, muted tones, natural palette |
| 皮肤塑料感 | 无毛孔 | 增加皮肤纹理 | pores, freckles, skin texture, subtle imperfections |
| 金属塑料感 | 无反射 | 描述反射内容 | reflecting [环境], mirror-like, chrome finish |
| 玻璃塑料感 | 无折射 | 描述光线行为 | soft refraction, subtle caustics, internal glow |

---

*本文档由AI绘画提示词知识蒸馏生成，整合自知识库中10+篇核心文章。所有关键词和提示词模板均经过结构化和系统化整理，可直接用于Midjourney、DALL·E、Stable Diffusion等主流AI绘画工具。*
