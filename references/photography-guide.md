# 摄影/镜头/构图方法论 —— AI绘画提示词知识蒸馏

> 本指南基于「AI绘画提示词」知识库中以下文章蒸馏而成：
> 1. 《别再瞎写提示词了！玩转AI绘画，你需要像摄影师一样去思考》
> 2. 《【MJ大师课】如何精准控制Midjourney镜头景别？》
> 3. 《构图进阶 | 中心绝非平庸：揭秘 Midjourney 绝对中心的高级玩法！》
> 4. 《拒绝画面平庸！Midjourney风景摄影永不翻车的构图神器：引导线解析》
> 5. 《告别AI塑料感！Midjourney生成摄影级真实风景的底层逻辑与万能公式》
> 6. 《告别塑料感！Midjourney 胶片颗粒全指南》
> 7. 《提升AI画面质感的1000个梦幻提示词》
> 8. 《告别"纸片感"！掌握这4个MidJourney景深秘籍》
> 9. 《告别"AI塑料感"！Midjourney打造高级电影感柔光的终极指南》
> 10. 《拒绝"塑料AI感"！揭秘让AI绘画秒变真实单反大片的"隐藏魔法"》

---

# 一、五大摄影思维模式

核心前提：一张出彩的 AI 图像并非建立在"主体"之上，而是建立在"定格"之上。你不是在描述一个场景，你是在描述一台相机如何去感受这个场景。

**摄影师的四项决策法则**（按下快门前的本能回答）：
- 主体是什么？
- 机位在哪里？
- 光线是如何表现的？
- 焦点在哪里？

## 【纪实思维】Documentary Photography

| 维度 | 内容 |
|------|------|
| **核心特点** | 真实至上，带有瑕疵，具有观察感。仿佛"我就在现场"的视觉体验。包含自然光、真实阴影、手持相机感、轻微动态模糊 |
| **适用场景** | 报道摄影、旅行记录、人文纪实、环境叙事、日常街拍 |
| **典型镜头** | **35mm**（最接近人类自然感知场景的视角——足够宽广容纳环境，足够接近突出主体，轻微畸变增添真实感与瑕疵美） |
| **提示词关键词** | `documentary photography`, `natural light`, `realistic shadows`, `handheld camera feel`, `slight motion blur`, `candid moment`, `unposed`, `muted tones`, `35mm lens`, `--raw` |
| **提示词模板** | `documentary photography, [主体], [场景], natural light, realistic shadows, handheld camera feel, 35mm lens, candid moment, muted tones --ar 2:1 --raw` |
| **核心理念** | 35mm = "我就在现场" |

## 【电影思维】Cinematic Photography

| 维度 | 内容 |
|------|------|
| **核心特点** | 情感至上，像电影中的一个镜头。戏剧性的体积光、深阴影、高对比度、克制且有目的性的画面框架、电影般的亲密感 |
| **适用场景** | 叙事性图像、电影剧照美学、氛围感场景、夜景、戏剧化照明场景 |
| **典型镜头** | **50mm**（标准镜头，电影摄影中非常强大——感觉自然，比35mm更聚焦，畸变更小，结合浅景深效果极佳） |
| **提示词关键词** | `cinematic still`, `dramatic volumetric light rays`, `deep shadows`, `high contrast lighting`, `slow contemplative mood`, `50mm lens`, `shallow depth of field`, `atmospheric haze`, `film grain`, `cinematic lighting` |
| **提示词模板** | `cinematic still, [主体], dramatic volumetric light rays, deep shadows, high contrast lighting, 50mm lens, shallow depth of field, atmospheric haze, film grain --ar 2:1 --raw` |
| **核心理念** | 50mm = "这是一个精心设计的场景，而不仅仅是一个瞬间" |

## 【商业品牌摄影思维】Brand Photography

| 维度 | 内容 |
|------|------|
| **核心特点** | 清晰至上，刻意设计的、精致的、商业化的。干净的画面、平衡的构图、柔和漫射光、高细节、锐利对焦、高级审美 |
| **适用场景** | 产品摄影、品牌视觉、高端广告、时尚摄影、精致静物 |
| **典型镜头** | **85mm**（拍摄高端精致视觉画面的首选——压缩空间透视让背景更近更柔和，更好修饰主体无畸变，自然隔离主体） |
| **提示词关键词** | `brand photography`, `clean composition`, `balanced framing`, `soft diffused lighting`, `high detail`, `sharp focus`, `premium aesthetic`, `controlled environment`, `85mm lens` |
| **提示词模板** | `brand photography, [主体], clean composition, balanced framing, soft diffused lighting, high detail, sharp focus, premium aesthetic, 85mm lens --ar 2:1 --raw` |
| **核心理念** | 85mm = "聚焦于完美" |

## 【街头摄影思维】Street Photography

| 维度 | 内容 |
|------|------|
| **核心特点** | 随性至上，充满生命力，毫无计划感。动态角度、偏离中心构图、自然运动、环境氛围、抓拍感、活力与不可预测性 |
| **适用场景** | 街头抓拍、城市纪实、人文瞬间、日常生活记录 |
| **典型镜头** | **35mm**（核心在于运动感、自发性和环境氛围——紧跟动作核心，同时捕捉主体和周围环境，制造令人感觉真实的轻微瑕疵） |
| **提示词关键词** | `street style photography`, `dynamic angle`, `slightly off-center framing`, `natural movement`, `ambient lighting`, `urban documentary feel`, `candid capture`, `35mm lens` |
| **提示词模板** | `street style photography, [主体], dynamic angle, slightly off-center framing, natural movement, ambient lighting, urban documentary feel, 35mm lens, candid capture --ar 2:1 --raw` |
| **核心理念** | 35mm = "生活就在你眼前上演" |

## 【人像思维】Portrait Photography

| 维度 | 内容 |
|------|------|
| **核心特点** | 主体至上。一切的存在都是为了服务于主体。强烈的情感焦点，奶油般柔和的焦外虚化（Bokeh），亲密感与优雅感 |
| **适用场景** | 人像摄影、情感特写、时尚人像、室内/户外人像 |
| **典型镜头** | **85mm**（关注的是"人"而不是"地点"——压缩面部特征更显脸小好看，利用浅景深将主体隔离，剔除分散注意力的元素） |
| **提示词关键词** | `portrait photography`, `close-up`, `soft light on face`, `blurred background`, `shallow depth of field`, `85mm lens`, `emotional expression`, `natural skin texture`, `subject isolation` |
| **提示词模板** | `portrait photography, [主体], soft light on face, blurred background, shallow depth of field, 85mm lens, emotional expression, natural skin texture --ar 2:1 --raw` |
| **核心理念** | 85mm = "只有主体最重要" |

---

# 二、镜头焦段指南

> 核心法则：镜头参数(mm)决定情绪的距离。镜头本身并不创造虚化，它只是为虚化的存在创造了条件。

## 广角镜头（14mm - 28mm）

| 焦段 | 效果描述 | 适用场景 | 典型关键词 |
|------|---------|---------|-----------|
| **14mm** | 超广角，极端透视夸张，强烈空间纵深感，边缘畸变明显，画面极具冲击力 | 大远景建筑、宏大风景、星空摄影、狭窄室内空间 | `ultra-wide angle`, `14mm lens`, `exaggerated perspective`, `strong spatial depth` |
| **24mm** | 广角，夸大空间感，将环境向外推开，主体被锚定在世界中，夸张纵深感 | 建筑摄影、环境人像、大场景风景、引导线构图 | `24mm wide-angle lens`, `exaggerated perspective`, `strong leading lines`, `deep focus` |
| **28mm** | 广角，自然的沉浸感，比24mm略窄，仍保持环境感 | 旅行摄影、环境叙事、沉浸式风景 | `28mm lens`, `immersive composition`, `natural perspective` |

## 标准镜头（35mm - 50mm）

| 焦段 | 效果描述 | 适用场景 | 典型关键词 |
|------|---------|---------|-----------|
| **35mm** | 最接近人类自然感知视角，纪实感强，轻微畸变增添真实感，同时捕捉主体与环境 | 纪实摄影、街头摄影、环境肖像、旅行记录、电影感场景 | `35mm lens`, `documentary style`, `natural perspective`, `environmental portrait`, `candid feel` |
| **50mm** | 标准镜头，感觉自然但更聚焦，畸变极小，构图干净，与浅景深配合极佳，电影感强 | 电影摄影、人像摄影、静物、日常纪实、电影剧照 | `50mm lens`, `standard lens`, `natural realism`, `clean composition`, `cinematic still` |

## 中长焦镜头（70mm - 100mm）

| 焦段 | 效果描述 | 适用场景 | 典型关键词 |
|------|---------|---------|-----------|
| **70mm** | 中长焦，适度的空间压缩，背景开始柔和 | 风景远景、人物中景、环境人像 | `70mm lens`, `medium telephoto`, `subtle compression` |
| **85mm** | 人像黄金焦段，压缩空间透视，背景柔和靠近，完美修饰主体，自然隔离主体 | 人像摄影、商业摄影、品牌视觉、时尚摄影 | `85mm lens`, `portrait lens`, `subject isolation`, `creamy bokeh`, `premium aesthetic` |
| **100mm** | 长焦/微距，极端空间压缩，极度孤立主体，适合特写和微距细节 | 微距摄影、产品特写、人像特写、细节捕捉 | `100mm macro lens`, `telephoto lens`, `ultra isolation`, `extreme close-up`, `macro detail` |
| **135mm** | 超长焦，极强空间压缩感，主体极度孤立，背景完全虚化 | 远距离人像、野生动物、压缩风景 | `135mm lens`, `telephoto compression`, `extreme subject isolation` |

## 特殊镜头

| 镜头类型 | 效果描述 | 适用场景 | 典型关键词 |
|---------|---------|---------|-----------|
| **鱼眼镜头** | 极端畸变，180度视野，画面呈圆形或强烈桶形畸变 | 创意摄影、极限运动、特殊艺术效果 | `fisheye lens`, `extreme distortion`, `circular frame` |
| **微距镜头** | 极致细节捕捉，极近对焦距离，微观世界呈现 | 昆虫摄影、花卉特写、产品细节、纹理质感 | `macro lens`, `extreme close-up`, `ultra detail`, `fine texture` |
| **移轴镜头** | 模拟微缩模型效果，选择性对焦平面，独特透视控制 | 微缩效果（Tilt-Shift）、建筑校正、创意风景 | `tilt-shift lens`, `miniature effect`, `selective focus plane` |

---

# 三、景别控制

> 核心法则：在AI绘画中，**景别 = 构图 + 距离**，**镜头 = 画面强化**。镜头不能决定景别，景别决定了距离、构图和创作意图，镜头仅负责调整透视关系、景深和空间压缩感。

## 1. 大远景（Extreme Long Shot / ELS）

| 维度 | 内容 |
|------|------|
| **画面特征** | 主体在画面中非常微小，环境占据绝对主导地位 |
| **核心作用** | 建立比例感与宏大规模；表现个体的孤独与隔离感；营造极其宏大的氛围 |
| **适配镜头** | 14mm - 24mm 广角 |
| **适配光圈** | f/8 - f/11（大景深，所有细节清晰可见） |
| **提示词关键词** | `extreme long shot`, `vast landscape`, `tiny figure`, `grand scale`, `wide-angle` |
| **提示词模板** | `Extreme long shot of [主体] in [场景], f/11, 14mm lens, deep focus --ar 3:2 --v 8` |

## 2. 远景（Long Shot / LS）

| 维度 | 内容 |
|------|------|
| **画面特征** | 主体完全可见，但依然有一定距离，环境仍然非常重要 |
| **核心作用** | 交代场景与位置；平衡主体与环境的互动关系 |
| **适配镜头** | 24mm - 35mm |
| **适配光圈** | f/4 - f/8 |
| **提示词关键词** | `long shot`, `full body visible`, `environmental context`, `balanced composition` |
| **提示词模板** | `Long shot of [主体] in [场景], f/8, 35mm lens --ar 3:2 --v 8` |

## 3. 中景（Medium Shot / MS）

| 维度 | 内容 |
|------|------|
| **画面特征** | 主体成为画面的视觉中心，环境逐渐淡化为背景衬托 |
| **核心作用** | 将视觉焦点转移到主体上；保留部分环境以维持叙事感 |
| **适配镜头** | 50mm - 85mm |
| **适配光圈** | f/5.6 - f/11（中等景深，画面部分焦点清晰，适度虚化背景） |
| **提示词关键词** | `medium shot`, `waist up`, `subject focus`, `moderate background blur`, `natural realism` |
| **提示词模板** | `Medium shot of [主体] in [场景], f/8, 50mm lens --ar 3:2 --v 8` |

## 4. 特写（Close-Up Shot / CU）

| 维度 | 内容 |
|------|------|
| **画面特征** | 画面紧紧聚焦于主体的某个局部（如脸部） |
| **核心作用** | 展现细腻的情绪；营造强烈的亲密感 |
| **适配镜头** | 85mm - 100mm |
| **适配光圈** | f/11 - f/16（浅景深） |
| **提示词关键词** | `close-up shot`, `face focus`, `strong subject isolation`, `shallow depth of field`, `emotional intensity` |
| **提示词模板** | `Close-up shot, [主体], face softly lit, strong subject isolation, f/16, 100mm lens --ar 2:3 --v 8` |

## 5. 大特写（Extreme Close-Up / ECU）

| 维度 | 内容 |
|------|------|
| **画面特征** | 画面中仅可见极为细节的部分（如眼睛、肌肤纹理、手部等） |
| **核心作用** | 极强的视觉冲击力；呈现抽象的艺术美感；深层情绪传递 |
| **适配镜头** | 微距镜头 / 100mm |
| **适配光圈** | f/2.8 - f/8（超浅景深，仅极小部分对焦） |
| **提示词关键词** | `extreme close-up`, `macro detail`, `ultra shallow depth of field`, `texture focus`, `abstract beauty` |
| **提示词模板** | `Extreme close-up shot, detail of [主体局部], ultra shallow depth of field, f/11, 100mm macro lens --ar 3:2 --v 8` |

## 景别核心总结

| 对比维度 | 景别 | 镜头 |
|---------|------|------|
| 决定因素 | 距离、构图、创作意图 | 透视关系、景深、空间压缩感 |
| 角色 | 定义画面内容 | 画面强化辅助 |
| 不可逆 | 镜头不能改变景别 | 景别决定镜头选择 |

---

# 四、构图法则

## 1. 中心构图（居中构图）——绝对中心法

| 维度 | 内容 |
|------|------|
| **核心原理** | 中心不是平庸的——它是绝对的。当你将主体居中时：消除了方向上的张力，剔除了视觉拉扯感，创造了绝对平衡。主体不再是图像的"一部分"，它直接变成图像的**轴心**，产生强烈的**存在感**（Presence） |
| **黄金法则** | 只有当整张图像都与之契合时，居中构图才能发挥作用。你必须围绕"居中"这个决定去设计画面中的一切——对称、视觉流、层级、光影 |
| **适用场景** | ①**静谧感**：具有情感分量的肖像、孤独独立的主体、诗意或内省场景；②**对称信息传达**：建筑设计、倒影反射、仪式感构图；③**主体统治地位**：产品摄影、标志性物品、象征性视觉效果；④**神圣感/标志性能量**：宗教圣像、正式肖像、仪式感构图 |
| **光影配合** | 必须用光影创造视觉层级，否则画面扁平崩塌：**边缘光**（rim light）分离边缘勾勒轮廓；**顶光**（top light）创造垂直统治力；**侧光**（side light）增加微妙不对称感 |
| **镜头搭配** | ①**广角24-28mm**：夸大空间感，将环境向外推开，适合环境交代的居中场景；②**标准35-50mm**：自然的平衡感，贴近人类真实视觉，适合宁静有真实感的居中构图；③**长焦85mm+**：压缩空间，极度孤立主体，将居中图像转化为标志性图腾 |
| **提示词关键词** | `centered composition`, `symmetrical`, `perfectly centered`, `centered framing`, `focal symmetry`, `centered subject`, `centered [主体]` |
| **隐藏陷阱** | 对称纯属偶然、光影过于扁平、缺失景深 → 图像变得只具装饰性而毫无意图 |

**警示**：停止认为"居中=安全区"，建立"居中=一种宣誓与承诺"的思维。当把某物放在正中央时，你宣告的是：这就是整幅作品的灵魂，这才是真正重要的焦点，没有任何东西可以与之争锋。

## 2. 引导线构图（Leading Lines）

| 维度 | 内容 |
|------|------|
| **核心原理** | 引导线是被具象化的意图。它们不喧宾夺主，只负责引导视线。创造了**流动感**、**纵深感**和**叙事方向**。没有引导线画面是静止的，有了它们画面就有了呼吸感 |
| **核心法则** | 引导线必须指向**某个有意义的地方**（光源、主体、地平线、消失点）。如果引导线没有指向，画面会显得空洞，观者会感到迷茫 |
| **视觉语法技巧** | ❌ 不要写 `river in a landscape`；✅ 要写 `winding river leading toward distant mountains`；❌ 不要写 `path in a forest`；✅ 要写 `narrow trail disappearing into dense fog` |
| **镜头逻辑** | 引导线需要透视关系才能存在：**24mm**夸张纵深感与强烈线条；**28mm**自然沉浸感；**35mm**可控的电影般视觉引导。**低视角**（low angle）夸张放大线条；**平视视角**自然流动感；**强调前景**锚定引导线 |
| **提示词关键词** | `leading lines`, `winding [element] leading toward`, `disappearing into`, `guiding the eye`, `vanishing point`, `perspective lines`, `foreground path`, `curved shoreline`, `narrow trail` |
| **典型引导线元素** | 蜿蜒河流（winding river）、小路/小径（trail/path）、海岸线（shoreline）、栅栏线（fence lines）、车辙（tire tracks）、岩石裂缝（cracks）、道路（road）、队列（rows of trees） |
| **提示词结构** | `[场景描述], [引导线元素] leading toward [目的地], [光线], [镜头], [光圈], deep focus --ar 16:9 --style raw` |
| **核心启示** | 构图不是装饰；方向比细节更重要；视线需要被引导，而不是被信息淹没 |

## 3. 三分法则（Rule of Thirds）

| 维度 | 内容 |
|------|------|
| **方法** | 将画面横竖三等分，形成九宫格，将主体/关键元素放置在四条分割线的交点或沿线分布 |
| **适用场景** | 几乎所有场景的基础构图方式，尤其适合风景、人像、街拍 |
| **提示词关键词** | `rule of thirds`, `off-center composition`, `subject offset to the left/right` |

## 4. 框架式构图（Framing）

| 维度 | 内容 |
|------|------|
| **方法** | 利用前景元素（如窗框、拱门、树枝、门洞）形成自然画框，将主体框在其中 |
| **适用场景** | 建筑摄影、人像、风景、营造深度感和窥视感 |
| **提示词关键词** | `framed by [元素]`, `through window/doorway/arch`, `natural framing`, `foreground frame` |

## 5. 负空间/留白构图（Negative Space）

| 维度 | 内容 |
|------|------|
| **方法** | 有意识地让画面大部分区域保持空旷（天空、墙面、水面等），主体占极小比例，创造呼吸感和意境 |
| **适用场景** | 极简风格、孤独感表达、情绪渲染、强调渺小与宏大对比 |
| **提示词关键词** | `negative space`, `minimal composition`, `70% empty frame`, `vast background`, `subject small in frame`, `empty sky` |

## 6. 对称构图（Symmetry）

| 维度 | 内容 |
|------|------|
| **方法** | 利用左右/上下镜像对称，创造平衡、庄严、仪式感的画面 |
| **适用场景** | 建筑摄影、倒影场景、宗教空间、仪式感图像、科技感走廊 |
| **提示词关键词** | `symmetrical`, `mirrored symmetry`, `perfect reflection`, `symmetrical composition`, `balanced symmetry` |

## 7. 对角线构图（Diagonal Composition）

| 维度 | 内容 |
|------|------|
| **方法** | 利用主体或元素的走向形成对角线，创造动感、动态和延伸感 |
| **适用场景** | 动态场景、建筑摄影、引导线构图的变体 |
| **提示词关键词** | `diagonal composition`, `diagonal lines`, `dynamic angle` |

## 8. 前景强调构图（Foreground Emphasis）

| 维度 | 内容 |
|------|------|
| **方法** | 利用清晰锐利的前景元素作为画面锚点，让观者"进入"画面 |
| **适用场景** | 风景摄影、深度感构图、三层法则的延伸 |
| **提示词关键词** | `foreground emphasis`, `sharp foreground`, `textured foreground`, `foreground anchor` |

---

# 五、景深控制

## 景深基本原理

景深（Depth of Field）是指图像中对焦清晰的最近和最远点之间的距离。它是摄影中最强大的叙事工具之一，能直接影响观看者的注意力聚焦点。

> **核心理解**：在AI绘画语境中，光圈参数（f/值）是控制景深的主要信号。焦距越长、光圈越大（f值越小），景深越浅。

## 浅景深（Shallow Depth of Field）

| 维度 | 内容 |
|------|------|
| **效果描述** | 主体清晰锐利，背景及前景极度柔化虚化（Bokeh），创造出强烈的**主体分离感**和**空间剥离感** |
| **适合场景** | 人像摄影、特写镜头、产品摄影、电影感叙事、突出情绪表达 |
| **光圈策略** | 大光圈：f/1.2 - f/2.8 |
| **镜头搭配** | 85mm（人像黄金组合）、50mm f/1.8（经典电影感）、100mm（微距） |
| **提示词关键词** | `shallow depth of field`, `creamy bokeh`, `background blur`, `subject isolation`, `soft background`, `cinematic focus roll-off`, `blurred background`, `f/1.8`, `f/2.8` |
| **提示词示例** | `Portrait of [主体], shallow depth of field, creamy bokeh background, 85mm lens, f/1.8, subject isolation` |

## 深景深（Deep Depth of Field）

| 维度 | 内容 |
|------|------|
| **效果描述** | 从前景到背景所有细节全部清晰可见，画面信息量极大，空间连贯感强 |
| **适合场景** | 风景摄影、建筑摄影、大远景、全景、纪实摄影、环境交代 |
| **光圈策略** | 小光圈：f/8 - f/16 |
| **镜头搭配** | 14-35mm 广角/标准镜头 |
| **提示词关键词** | `deep depth of field`, `deep focus`, `everything in focus`, `front-to-back sharpness`, `hyperfocal focus`, `f/11`, `f/16`, `all sharp` |
| **提示词示例** | `Landscape, deep depth of field, f/11, 24mm lens, everything in focus from foreground to background` |

## 移轴效果 / Tilt-Shift / 微缩景观

| 维度 | 内容 |
|------|------|
| **效果描述** | 模拟移轴镜头的选择性对焦平面，画面中仅有一条窄带清晰，其余部分模糊，产生微缩模型般的视觉效果 |
| **适合场景** | 微缩玩具城风格、高空俯瞰城市、创意风景、独特视角 |
| **提示词关键词** | `tilt-shift`, `miniature effect`, `selective focus plane`, `narrow focus band`, `aerial view with tilt-shift` |
| **搭配要素** | 需搭配高视角（`aerial view`, `elevated perspective`）和极繁细节（`hypermaximalism`）效果最佳 |

## 画面缺乏深度的4大原因与修复

| 问题 | 原因 | 修复方法 |
|------|------|---------|
| **元素在同一平面** | 所有物体感觉粘贴在同一个图层上，没有前景/中景/背景的明确划分 | 强制划分三个平面——明确命名前景（foreground）、中景（middle distance）、背景（background），使用关系短语如 `mossy stones in the foreground`, `mountains fading in the far background` |
| **光线无层级** | 光线均匀照射在所有物体上，没有任何东西突显出来 | 指定光线**方向**（逆光/侧光/顶光）、**强度**（强高光/微弱光晕/深阴影）、**氛围**（薄雾/灰尘/雾气捕捉光线） |
| **相机逻辑平淡** | 没有给出任何相机信息，Midjourney选择中性镜头和中距离焦点 | 明确指定**焦距**（镜头的空间压缩感）、**光圈**（景深控制）、**对焦与模糊**（景深过渡） |
| **画面杂乱无留白** | 画面从边缘到边缘都填满了细节，眼睛无处停歇 | 有意识地使用留白——`70% empty frame`, `minimal background`, `negative space around subject` |

## 深度构建的三大杠杆

| 杠杆 | 控制项 | 效果 |
|------|--------|------|
| **焦距** | 镜头mm数（14mm→135mm） | 广角夸张透视→长焦压缩空间 |
| **光圈** | f/值（f/1.2→f/16） | 大光圈浅景深→小光圈深景深 |
| **对焦与模糊** | 清晰区域与模糊区域的过渡 | 决定焦内区域和虚化滚降（focus roll-off） |

---

# 六、胶片与画质参数

## 胶片颗粒哲学

> 图像变得越完美，它看起来就越显得虚假。在物理世界中，摄影很少呈现完美状态。胶片颗粒是AI图像获得视觉真实感的关键——不完美的细节置顶真实感。

**颗粒的心理学**：一个多世纪以来，人类大脑已经习惯于将胶片颗粒解读为"真实"的信号——物理捕捉、纪实证据、摄影写实主义、模拟时代的真实性。

## 四种胶片颗粒类型

### ① 细腻柯达胶片颗粒（Subtle Kodak Film Grain）

| 维度 | 内容 |
|------|------|
| **特性** | 最安全、最可靠。柔和颗粒质感，平衡的色调过渡，自然的肤色，克制的对比度。唤起经典纪实摄影的视觉感 |
| **视觉效果** | 感觉真实而不失格调，像杂志报道或旅行摄影 |
| **适用题材** | 人像、旅行摄影、日常纪实场景、环境叙事 |
| **提示词** | `subtle Kodak film grain` |

### ② 电影胶片颗粒（Cinematic Film Grain）

| 维度 | 内容 |
|------|------|
| **特性** | 比静态摄影中的颗粒略强。为场景增添氛围和情感基调，戏剧化的光影，暗部区域更强质感 |
| **视觉效果** | 将图像转化为电影中凝固的瞬间，富有氛围感的阴影，微妙调色 |
| **适用题材** | 夜景、戏剧性照明、电影剧照美学、叙事性图像 |
| **提示词** | `cinematic film grain` |

### ③ 精致模拟颗粒纹理（Fine Analog Grain Texture）

| 维度 | 内容 |
|------|------|
| **特性** | 几乎隐形，不主导图像。引入微观的不规则性，微妙地打破数字平滑感 |
| **视觉效果** | 极其细腻真实，高质量模拟胶片在受控光线下捕捉的印象 |
| **适用题材** | 宏观摄影、皮肤纹理、植物细节、材料表面 |
| **提示词** | `fine analog grain texture` |

### ④ 纪实胶片颗粒（Documentary Film Grain）

| 维度 | 内容 |
|------|------|
| **特性** | 唤起新闻摄影的美学——原始、观察性、真实。自然光照，略显粗糙的质感，抓拍式构图 |
| **视觉效果** | 图像感觉是被观察到的，而不是被布置出来的 |
| **适用题材** | 街头摄影、报道场景、历史氛围感、旅行记录 |
| **提示词** | `documentary film grain` |

## 扩展颗粒语言

| 关键词 | 作用 |
|--------|------|
| `analog photography` | 暗示物理胶片捕捉 |
| `film stock texture` | 激活胶片材料特定的视觉记忆 |
| `vintage film look` | 引入怀旧的色调表现 |
| `natural sensor grain` | 模拟真实的数码相机噪点 |

**策略建议**：将颗粒词汇与以下信号结合以强化物理成像效果：
- `analog photography` + `vintage film look` + `subtle grain texture`
- `natural sensor grain` + `cinematic lighting`

## 相机型号参数参考（用于提升真实感）

在提示词中嵌入真实相机型号 + 镜头 + 光圈 + ISO 的组合，能显著提升图像的真实感级别（Meta Tokens效应）。

### 全画幅专业机身

| 相机型号 | 关键词 | 适用场景 |
|---------|--------|---------|
| Sony A1 / A7R V | `Sony A1`, `Sony A7R V` | 全能顶级画质，适合风景/人像 |
| Canon R5 / R3 | `Canon R5`, `Canon R3` | 色彩科学优秀，适合人像/商业 |
| Nikon Z8 / D850 | `Nikon Z8`, `Nikon D850` | 细节表现卓越，适合风景 |
| Hasselblad X2D | `Hasselblad X2D` | 中画幅极致画质，适合商业/艺术 |

### 经典胶片相机

| 相机型号 | 关键词 | 适用场景 |
|---------|--------|---------|
| Leica M系列 | `Leica M`, `rangefinder camera` | 街头摄影、人文纪实 |
| 哈苏500系列 | `Hasselblad 500CM`, `medium format film` | 复古胶片质感 |

### 提示词中的相机参数模板

```
[场景描述], [相机型号], [镜头], f/[光圈], ISO [数值] --ar 2:1 --raw --v 8.1
```

示例：`Landscape photograph of a coastal cliff, Sony A7R V, 24mm, f/11, ISO 100 --ar 2:1 --raw`

## Meta Tokens（渲染元数据）体系

Meta Tokens是不描述场景元素、而影响模型**如何渲染**场景的语言碎片。它们是引导模型诠释真实感、光影和视觉保真度的核心信号。

### 三大Meta Token类别

| 类别 | 说明 | 关键词 |
|------|------|--------|
| **核心真实感Tokens** | 决定图像的基础渲染质量 | `photorealistic`, `architectural photography`, `natural lighting`, `HDR photography`, `ultra detailed textures`, `high dynamic range`, `global illumination`, `sharp focus`, `physically accurate materials` |
| **相机Tokens** | 决定图像的相机行为与视角 | `24mm wide-angle lens`, `eye-level perspective`, `deep depth of field`, `professional [genre] photography` |
| **光影Tokens** | 决定图像的光影物理特性 | `natural directional sunlight`, `soft interior bounce light`, `warm ambient light`, `subtle shadow gradients` |

### A/B对比经验

> 同样的场景描述，添加Meta Tokens与不添加的结果有天壤之别。结构化的提示词（如JSON蓝图）赋予精确性，Meta Tokens则稳定了渲染风格的解读，告诉AI"像处理照片一样处理这个场景"。

---

# 七、光影控制专题

## 柔和电影感光影（电影级柔光）

| 维度 | 内容 |
|------|------|
| **核心法则** | 多数AI图像的"塑料感"源于光线生硬。柔和漫反射光（soft diffused lighting）模拟真实世界物理环境，降低对比度，在光与影之间创造平滑过渡 |
| **推荐关键词** | `soft diffused lighting`, `overcast light`, `window light`, `fog`, `mist`, `dust particles` |
| **避开的词汇** | `direct sunlight`, `strong shadows`（直射阳光和强烈阴影会导致"AI生成感"） |
| **最佳搭配** | 50mm镜头（自然写实感）+ 浅景深（柔和感）+ 柔和色调（情绪宁静） |

## 光线方向与效果

| 光线类型 | 效果描述 | 提示词关键词 | 适用场景 |
|---------|---------|-------------|---------|
| **侧光** | 展现纹理和地形起伏，创造立体感 | `side light`, `side lighting`, `dramatic side lighting` | 风景、人像、纹理强调 |
| **逆光** | 创造光晕和氛围感，勾勒主体轮廓 | `backlight`, `backlighting`, `rim light`, `backlit soft glow` | 人像、氛围场景、主体分离 |
| **顺光** | 均匀照亮，细节清晰但缺乏立体感 | `front light`, `flat lighting` | 产品摄影、技术记录 |
| **顶光** | 创造垂直方向的统治力，戏剧性阴影 | `top light`, `top-down lighting` | 舞台感、仪式感 |
| **边缘光** | 分离边缘，勾勒轮廓，制造立体感 | `rim light`, `edge light`, `rim lighting` | 居中构图、人像、主体分离 |
| **漫射光** | 降低对比度，阴影柔和，过渡平滑 | `soft diffused lighting`, `diffuse light`, `overcast light` | 人像、室内、电影感 |
| **体积光** | 光线可见光束，丁达尔效应，氛围极强 | `volumetric light`, `volumetric light rays`, `god rays`, `light beams` | 电影感、神圣感、森林/教堂场景 |

## 光线方向策略

> **永远只选择一种主光源**。混合冲突的光线方向是打破真实感最快的"翻车"捷径。

| 光线场景 | 关键词 | 适用场景 |
|---------|--------|---------|
| 黄金时刻（Golden Hour） | `golden hour`, `warm golden light`, `long shadows` | 风景、人像、浪漫氛围 |
| 蓝调时刻（Blue Hour） | `blue hour`, `cool blue light`, `soft twilight` | 城市夜景、宁静风景 |
| 阴天/漫射光 | `overcast`, `cloudy sky`, `diffused light` | 消除强烈对比，完美展现细节 |
| 窗口光 | `window light`, `north-facing window light` | 室内人像、静物、电影感室内 |
| 篝火/烛光 | `firelight`, `candlelight`, `warm glow` | 复古氛围、亲密场景 |
| 霓虹光 | `neon light`, `neon glow`, `colorful neon` | 赛博朋克、城市夜景 |

## 进阶光影技巧

| 技巧 | 方法 | 提示词关键词 |
|------|------|-------------|
| **柔光+纹理** | 柔光与纹理结合使用，质感与真实度直接拉满 | `soft diffused lighting` + `textured surface` |
| **体积光** | 加入可见光束大幅提升电影级景深感 | `volumetric light rays`, `god rays cutting through fog` |
| **背光柔和光晕** | 为主体边缘勾勒梦幻般的效果 | `backlit soft glow`, `rim light highlighting edges` |
| **阴天+大气薄雾** | 一键消除生硬对比度，画面质感高级翻倍 | `overcast lighting + atmospheric haze` |
| **反光板效果** | 利用环境反射光自然填充阴影 | `bounce light`, `ambient bounce light` |
| **光晕/光斑** | 增加镜头光学不完美感 | `lens flare`, `light flare`, `sun flare` |

---

# 八、提示词万能公式与组合策略

## 摄影思维万能公式

```
[摄影风格] + [主体] + [光线表现] + [镜头] + [焦点/景深] + [参数]
```

**实战示例**：
```
cinematic still, woman exploring a cathedral, volumetric light rays, 50mm lens, shallow depth of field, atmospheric haze --ar 2:1 --raw
```

## 摄影级真实风景万能公式

```
Landscape photograph of [场景描述],
[前景：锐利纹理元素],
[中景：视觉引导通道],
[背景：远景消失于大气],
[光线方向与效果],
[天气与材质匹配],
[相机型号], [镜头], f/[光圈], ISO [数值]
--ar 2:1 --raw --stylize 150 --hd --v 8.1
```

**大师级模板**：
```
Landscape photograph of a wide valley, textured grass and small rocks in the foreground, winding river leading through the midground, distant mountains fading into soft atmospheric haze, early morning side light creating gentle shadows, slight mist in low areas, natural color palette, high detail but soft distance, Sony A7R V, 28mm, f/11, ISO 100 --ar 2:1 --raw
```

## 景深分层提示词公式

```
[场景], [前景元素] in the foreground in sharp focus, [中景元素] in the middle distance, [背景元素] in the far background, three-plane composition, layered depth cues, [镜头], f/[光圈], [光线] --ar 16:9
```

## 千人千面组合逻辑

**推荐组合顺序**：`光影氛围 → 材质肌理 → 色彩调性 → 风格/镜头`

**新手用法**：先套用模板，微调1-2个关键词。
**进阶用法**：跨类别补充细节词，如在"温柔治愈写真"中添加"空气中的尘埃颗粒"增强画面层次感。

---

# 九、核心参数速查表

## 镜头与景别的匹配关系

| 景别 | 推荐镜头 | 推荐光圈 | 画面特征 |
|------|---------|---------|---------|
| 大远景 | 14-24mm | f/8-f/11 | 主体微小，环境主导 |
| 远景 | 24-35mm | f/4-f/8 | 主体可见，环境重要 |
| 中景 | 50-85mm | f/5.6-f/11 | 主体中心，环境陪衬 |
| 特写 | 85-100mm | f/11-f/16 | 局部聚焦，情绪强烈 |
| 大特写 | 微距/100mm | f/2.8-f/8 | 极致细节，抽象美 |

## 景别/构图/镜头关系核心结论

> **景别**决定了：距离（distance）→ 构图（framing）→ 创作意图（intention）
> **镜头**仅调整：透视关系（perspective）→ 景深（depth of field）→ 空间压缩感（compression）
> **光圈**（f/）→ 决定背景的虚化程度
> **物理距离**→ 决定视觉效果的强度

## 摄影思维与镜头速查

| 摄影思维 | 核心口号 | 推荐镜头 | 关键词标志 |
|---------|---------|---------|-----------|
| 纪实思维 | "我就在现场" | 35mm | documentary, candid, unposed, handheld |
| 电影思维 | "这是一个精心设计的场景" | 50mm | cinematic, volumetric, dramatic, film grain |
| 商业品牌思维 | "聚焦于完美" | 85mm | brand, clean, premium, controlled |
| 街头思维 | "生活就在你眼前上演" | 35mm | street, dynamic, candid, urban |
| 人像思维 | "只有主体最重要" | 85mm | portrait, close-up, shallow depth of field, emotional |

---

# 十、高频提示词关键词总库

## 视角/角度类

| 分类 | 关键词 |
|------|--------|
| **基本景别** | `extreme long shot`, `long shot`, `medium shot`, `close-up shot`, `extreme close-up` |
| **拍摄角度** | `low angle`, `high angle`, `eye-level`, `bird's eye view`, `worm's eye view`, `aerial view`, `overhead shot`, `dutch angle` |
| **特殊视角** | `first person view`, `over-the-shoulder shot`, `POV`, `reflection shot`, `through window` |

## 构图类

| 分类 | 关键词 |
|------|--------|
| **基础构图** | `rule of thirds`, `centered composition`, `symmetrical`, `diagonal composition`, `leading lines` |
| **进阶构图** | `negative space`, `minimal composition`, `framing shot`, `layered composition`, `three-plane layout` |
| **画幅比例** | `--ar 16:9`（电影宽屏）, `--ar 3:2`（标准摄影）, `--ar 4:5`（竖版人像）, `--ar 1:1`（方图）, `--ar 2:1`（超宽幅） |

## 光影类

| 分类 | 关键词 |
|------|--------|
| **光线方向** | `side light`, `backlight`, `front light`, `top light`, `rim light`, `edge light` |
| **光线质量** | `soft diffused lighting`, `hard light`, `direct sunlight`, `overcast light`, `window light` |
| **光线效果** | `volumetric light`, `god rays`, `lens flare`, `crepuscular rays`, `light beams`, `bounce light` |
| **光线时机** | `golden hour`, `blue hour`, `sunrise`, `sunset`, `twilight`, `midnight` |
| **进阶氛围** | `atmospheric haze`, `mist`, `fog`, `dust motes`, `heat shimmer`, `rain veils` |

## 景深与焦点类

| 分类 | 关键词 |
|------|--------|
| **景深控制** | `shallow depth of field`, `deep depth of field`, `deep focus`, `hyperfocal focus` |
| **虚化效果** | `creamy bokeh`, `background blur`, `soft background`, `cinematic focus roll-off` |
| **焦点特写** | `sharp focus`, `ultra-sharp`, `crisp detail`, `soft focus`, `dreamy blur` |
| **特殊焦点** | `selective focus`, `tilt-shift`, `miniature effect`, `macro focus` |

## 胶片与质感类

| 分类 | 关键词 |
|------|--------|
| **颗粒类型** | `subtle Kodak film grain`, `cinematic film grain`, `fine analog grain texture`, `documentary film grain` |
| **模拟风格** | `analog photography`, `film stock texture`, `vintage film look`, `natural sensor grain` |
| **画质关键词** | `photorealistic`, `HDR photography`, `ultra detailed`, `high dynamic range`, `8k`, `global illumination` |
| **画质参数** | `sharp focus`, `physically accurate materials`, `natural textures`, `high fidelity` |

---

> **撰文说明**：本文档由AI绘画提示词知识蒸馏专家基于知识库中10篇核心文章系统整理而成，旨在为AI绘画创作者提供一份完整的摄影/镜头/构图方法论参考，帮助创作者停止像作家一样思考，开始像相机一样观察。
