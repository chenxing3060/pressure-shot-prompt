---
name: pressure-shot-prompt
description: 根据「看图说话」方法论，用摄影四维度（角度+焦距+景别+景深）+主体刻画+环境分层+光照色调+视觉心理学五层逻辑，为任意压迫感/史诗感/悬疑感/宏大场景自动生成专业级AI生图/分镜Prompt。当用户提到压迫感镜头、广角仰拍、大场面、史诗感画面、AI生图prompt、分镜提示词、low angle wide shot、dutch angle、巨物恐惧、史诗战争、boss出场、巨型生物、灾难场景等电影感镜头prompt需求时使用此技能。适用于Midjourney、Stable Diffusion、DALL-E、Kling、可灵、即梦、Seedance、Sora等AI图像/视频生成工具。
---

# 压迫感镜头Prompt生成器

基于抖音「小G-0202」《看图说话》系列（第3期：如何用AI制作压迫感镜头画面）的方法论，把AI生图从"凭直觉碰运气"升级为"有逻辑可复用"的专业工作流。

## 核心方法论：五层拆解法

看到一张有压迫感的参考图（或脑中有一个压迫感画面），按以下顺序逐层拆解，最后按顺序组合成Prompt：

### 第1层 · 摄影四维度（镜头语言，决定"怎么看"）

| 维度 | 压迫感镜头常用值 | 视觉心理学原理 |
|------|-----------------|---------------|
| **角度 (Angle)** | 低角度仰拍 (low angle shot / looking up)、极端低角度 (extreme low angle)、荷兰角/倾斜构图 (dutch angle) | 仰拍让主体显得高大、有统治力、压迫观众；倾斜角制造不安、失控感 |
| **焦距 (Focal Length)** | **两大流派**：①超广角 (ultra wide-angle 14-24mm)、鱼眼 (fisheye 8-15mm) — 夸张近大远小，让巨物"向观众扑来"；②**超长焦 (telephoto 200mm+)** — 空间压缩，把远处威胁强行"拉近贴脸"，抹除安全距离，制造幽闭恐惧 | 超广角=巨物扑面而来的"泰山压顶"；超长焦=威胁无处可逃的"幽闭窒息"，两种流派心理学机制完全不同 |
| **景别 (Shot Size)** | ①大远景/大全景配合渺小人物（超广角流派）；②**特写+近景复合构图**（长焦流派：压迫源特写占画面主体，被压迫者近景仅在画面边缘做尺度参照） | 大景别=宏大vs渺小；复合特写=近距离面对威胁的窒息感，是更"狠"的压迫 |
| **景深 (Depth of Field)** | ①大景深(deep DOF)全画面清晰（战争/全景用）；②**浅景深+焦点锁定威胁本体**（长焦流派：前景人物轻微失焦保留轮廓，焦点锁定压迫源核心，背景完全融化在环境粒子中） | 大景深让威胁全貌可见；浅景深把视觉注意力强行钉在威胁最恐怖的部位（如巨口、眼睛），前景失焦人物暗示"你也是下一个" |
| **机位高度** | 摄像机高度低于胸口、贴近地面（low camera position） | 机位越低，观众越像躺在地上面对巨人/巨兽，强化被动、无力感 |

**⚠️ 两大压迫感流派（必须根据场景选对流派）**：

| 流派 | 焦段组合 | 心理学机制 | 适用场景 |
|------|---------|-----------|---------|
| **A. 巨物扑来（超广角派）** | 低角度仰拍+超广角14-24mm+大远景+大景深 | 近大远小夸张透视，巨物从上方向观众"压"下来 | Boss登场、巨兽出山、海啸压城、飞船遮天 |
| **B. 幽闭窒息（长焦压缩派）** | 微仰(15°左右)+超长焦200mm++特写近景复合构图+浅景深(焦点锁威胁本体) | 空间压缩抹除安全距离，威胁"贴在脸上"无处可逃；前景失焦人物=观众代入 | 直面怪兽巨口、被军队包围、黑洞在前、枪口抵脸 |

**关键组合规律**：
- **最强压迫感** = 低角度仰拍 + 超广角 + 大远景（主体巨大占满画面上方，人物在画面底部渺小）
- **幽闭压迫感（原教程沙虫范式）** = 低机位胸口以下 + 仰角约15° + 超长焦 + 复合构图(威胁特写占画面4/5高+人物近景压在最底边缘) + 浅景深(焦点锁威胁核心/前人物景失焦/背景融化)
- **悬疑不安感** = 荷兰角 + 中焦 + 中景 + 浅景深（倾斜+局部可见=未知威胁）
- **史诗宏大感** = 平视/微仰 + 广角 + 大远景 + 大景深（上帝视角看全貌）

### 第2层 · 主体刻画（画面"谁/什么"，决定被压迫的对象与压迫源）

**双主体公式（压迫感镜头必备）**：
1. **压迫源（Threat）**：要巨大、要占画面主导、要具有视觉重量
   - 生物类：巨型怪兽/沙虫/巨龙/外星生物/巨型机甲/克苏鲁式触手
   - 建筑/自然类：摩天楼/巨型雕像/火山/海啸/风暴/通天塔
   - 人物类：千军万马/铠甲军团/巨型Boss/神级存在
   - 抽象类：巨大的眼睛/张开的深渊/遮天蔽日的飞船/黑洞
2. **被压迫者（Victim/Viewer surrogate）**：要渺小、要脆弱、要提供尺度参照
   - 一个孤独的士兵/小人物站在画面底部
   - 渺小的人群/队伍
   - 观众POV视角（第一人称仰视）
   - 可以没有具体人物，但必须有尺度参照物（车/树/建筑碎片）

**描述公式**：`[压迫源：形容词+尺寸+材质+动作/状态] + [与被压迫者的关系：俯视/逼近/矗立/吞噬] + [被压迫者：渺小+动作+情绪反应]`

**⚠️ 复合构图量化布局（长焦流派必用）**：
- 压迫源（Threat）特写：占据画面上方约 **4/5（80%）高度**，宽度占据画面中间或略偏一侧 **1/3** 空间
- 被压迫者（Victim）近景：仅位于画面**最底部边缘**，占画面高度<10%，**仅作为尺度参照物存在**，不需要刻画表情细节
- 关键描述词：「仅作为尺度参照物存在」「边缘压底」「高度占比XX/宽度占比XX」——这些量化词比单纯写"giant""tiny"更有效

**原教程沙虫案例示范**：
> 沙虫巨口向外张开呈喇叭状，特写，高度占据画面上方约五分之四空间，宽度占画面中间略偏左三分之一空间。沙虫巨口边缘被浓厚沙暴包裹，边缘和沙尘分界清晰。沙虫口部前景有沙尘遮挡。五名战士近景，位于画面最底部边缘，仅作为尺度参照物存在。

### 第3层 · 环境刻画（分三层描述，营造空间纵深）

按「前景-中景-后景」三层公式写：

| 层次 | 作用 | 压迫感镜头常用元素 |
|------|------|-------------------|
| **前景 (Foreground)** | 制造画面"窗框感"，让观众有"窥视/身临其境"感 | 飞扬的尘土/碎石/火星、前景士兵背影/武器、地面裂缝、被吹起的碎片、雨/雪/风沙打在镜头上 |
| **中景 (Midground)** | 核心冲突发生地 | 战场对峙/巨物本体/人群奔逃/主要动作 |
| **后景 (Background)** | 营造氛围纵深，强化宏大感 | 漫天乌云/远处山脉/燃烧的城市/风暴中心/冲天烟柱/层叠军队/神秘光源 |

**环境描述顺序**：天气/天象 → 地形 → 周围破坏/混乱元素 → 氛围粒子（烟尘/雨/雪/火星/灰烬/飞沙）

**⚠️ 长焦流派的特殊环境处理——背景融化（Background Melting）**：
在超长焦+浅景深组合下，后景**不**需要写具体场景（如"远处山脉""燃烧的城市"），而是让背景完全融化在环境粒子中——写「背景完全融化于[沙暴/浓雾/烟尘/暴风雪/黑暗]中」「背景与粒子边界融为一体」「no clear background, dissolved into particles」。这种"没有背景"的处理反而强化了幽闭感，让威胁填满整个世界、无处可逃。

**原教程沙虫案例示范**：前景五名曼战士（轻微失焦，仅保留轮廓与局部高光）→ 中景沙虫巨口（焦点区域，喇叭状张开）→ 后景完全融化于沙暴中。

### 第4层 · 光照与色调（决定画面质感和情绪）

**压迫感镜头光影配方**：

| 元素 | 推荐值 | 心理学效果 |
|------|--------|-----------|
| **主光源方向** | 逆光/侧逆光 (backlight / rim light)、顶光 (top light)、底光 (underlight) | 逆光勾勒主体轮廓形成剪影，神秘/未知；底光制造恐怖/诡异 |
| **光质** | 硬光 (hard light)、高对比度 (high contrast) | 硬朗阴影制造紧张、冲突感 |
| **色温** | 冷色调为主（深蓝/铁青/青灰色）+ 局部暖光（爆炸/火光/熔岩）点缀 | 冷=恐惧、危险、未知；暖点=毁灭、破坏、威胁来源 |
| **氛围光** | 体积光/丁达尔光 (volumetric light / god rays)、闪电光、爆炸闪光 | 体积光穿透烟尘制造史诗纵深；闪电/爆炸提供突变高光强化威胁 |
| **阴影** | 大面积阴影/深黑 (chiaroscuro / low key lighting) | 未知潜伏在阴影中=恐惧 |

**色调黄金组合**：
- 史诗战争：暗蓝灰主调 + 橙黄火光点缀（冷暖对比经典电影色）
- 灾难/末日：铅灰+血红+暗紫
- 科幻压迫：冷青+品红霓虹+黑
- 克苏鲁/深海：墨绿+深蓝+病态黄绿
- 巨物神圣恐惧：白金强光+深黑阴影（宗教感）
- **废土窒息（原教程沙虫范式）**：极低饱和度（desaturated）+废土色调（wasteland color palette：土黄/沙褐/铅灰为主，剥夺所有情感温度）— 心理学原理：极低饱和度与生命力、活力、安全感挂钩，毫无生机的色调潜意识告诉观众"这里只有残酷生存与死亡，没有浪漫"，避免画面拍成"太空歌剧"式的酷炫美感

### 第5层 · 视觉心理学底层校验（写完Prompt后自问7个问题）

1. **尺度对比够不够？** 有没有渺小参照物来体现"大"？没有的话补小人物/小物体在画面最底部边缘，量化"仅作为尺度参照物存在"
2. **透视/压缩选对流派了吗？** 要"扑脸"用超广角近大远小；要"幽闭"用超长焦空间压缩抹除安全距离
3. **视觉重心在哪？** 压迫源是否在画面上方/中央形成"泰山压顶"（超广角派），或特写填满画面4/5让观众无处可逃（长焦派）？
4. **背景处理对吗？** 超广角派后景要具体（天空/远山/城市）营造宏大纵深；长焦派后景要"融化"在粒子中制造幽闭
5. **未知感是否保留？** 是否有阴影/雾气/遮挡物让部分威胁藏起来？（全看清反而没那么可怕）焦点是否锁定在威胁最恐怖的核心（如巨口内部、黑洞深处）？
6. **饱和度是否匹配情绪？** 要"史诗酷"用蓝橙对比+正常饱和度；要"窒息残酷"必须用极低饱和度废土色调，剥夺浪漫感
7. **情绪词有没有加？** 结尾加`oppressive / menacing / claustrophobic / inescapable / awe-inspiring / daunting / epic / overwhelming / cinematic tension / brutal survival horror / suffocating dread`等情绪关键词

---

## Prompt组装公式（终极模板）

```
[镜头四维], [主体：压迫源 vs 被压迫者],
[前景层：碎片/粒子/遮挡物],
[中景层：核心对峙/动作],
[后景层：天象/环境纵深/氛围],
[光照：方向+光质+色温+氛围光],
[色调/风格关键词],
[画质/技术参数],
[情绪/氛围词]
```

**英文版（Midjourney/SD/DALL-E/Sora推荐）**：
```
[Camera angle], [focal length] lens, [shot size], [DOF],
[Subject: gigantic ___ looming over ___], [relationship/action],
foreground: [particles/debris], midground: [core action], background: [sky/terrain/distant chaos],
[lighting style: backlight/rim light/hard light], [color tone], volumetric light, high contrast,
[style: cinematic / photorealistic / concept art / anime],
8K, ultra detailed, cinematic composition, color grading,
oppressive atmosphere, sense of scale, overwhelming tension, epic --ar 16:9 --v 6
```

---

## 按情绪类型的Prompt预设模板

### 模板A · 巨物压迫（Boss出场/巨兽逼近/巨型建筑）
```
Extreme low angle shot, ultra wide-angle 14mm lens, extreme wide shot, deep depth of field,
a colossal [巨兽/机甲/雕像/飞船名称] towering above, its [body/structure] dominating 80% of the frame,
a single tiny [soldier/figure/person] standing at the bottom center looking up, completely dwarfed,
foreground: dust and debris flying toward camera, cracked ground, scattered rubble,
midground: the massive [creature/structure] [looming/descending/awakening], casting enormous shadow,
background: stormy dark sky with swirling [purple/dark red] clouds, distant lightning, apocalyptic atmosphere,
dramatic backlight with harsh rim light separating the subject from the sky, cold blue-grey color palette with [orange/magenta] accents from [explosions/energy pulses], volumetric light beams piercing through dust,
cinematic, photorealistic, hyper detailed, 8K, IMAX quality, film grain, color graded,
oppressive sense of scale, overwhelming presence, terrifying awe, monumental tension --ar 16:9
```

### 模板B · 战场史诗（千军万马/战争场面）
```
Slight low angle, wide-angle 24mm lens, extreme wide establishing shot, deep depth of field,
two massive armies facing each other across a vast battlefield, thousands of soldiers stretching to horizon,
foreground: a lone [warrior/general] on [horseback/elevated ground], banner fluttering in wind,
midground: armies clashing, dust clouds rising, flags and weapons filling the field,
background: [dark mountains/burning city/stormy sky], smoke pillars rising to clouds, distant siege weapons,
golden hour backlight mixed with fire glow, warm orange vs cold steel blue contrast, volumetric dust and smoke, god rays through clouds,
cinematic war photography style, gritty, hyper realistic, Peter Jackson epic battle aesthetic,
8K, cinematic composition, anamorphic lens flare, color graded,
epic scale, impending battle tension, overwhelming numbers, historic grandeur --ar 21:9
```

### 模板C · 悬疑不安（未知威胁/恐怖场景）
```
Dutch angle tilt, medium 50mm lens, medium shot, shallow depth of field,
[模糊的威胁主体：一双眼睛/一个轮廓/一道影子] partially visible in [corner/darkness/reflection],
protagonist in foreground, back to camera, unaware / slowly turning toward threat,
foreground: out-of-focus [door frame/curtain/shoulder], adding voyeuristic framing,
midground: the [figure/creature/shadow] barely visible, obscured by [shadow/fog/reflection],
background: dark corridor/abandoned room/forest, single faint light source,
single harsh side light creating deep shadows, low-key lighting, mostly dark frame, cold desaturated green-grey palette, single warm accent from [flickering bulb/distant lamp],
psychological horror, cinematography by Roger Deakins, atmospheric,
nocturnal, unsettling, uncanny, creeping dread, tense silence --ar 16:9
```

### 模板D · 自然灾害/末日（海啸/火山/风暴/小行星）
```
Low angle looking up, ultra wide 16mm lens, extreme wide shot, deep depth of field,
a massive [tsunami wall/erupting volcano/tornado/firestorm/asteroid] filling the sky,
tiny [people/cars/buildings] at bottom fleeing in panic, sense of unavoidable doom,
foreground: debris/ash/water spray hurtling toward camera,
midground: the [wave/lava flow/debris cloud] advancing, destroying everything in path,
background: dark apocalyptic sky, [lightning/ash cloud/mushroom shape], red/black/deep purple tones,
apocalyptic lighting, dark and foreboding, flashes of lightning illuminating the scene,
practical disaster film aesthetic, Roland Emmerich style,
8K, photorealistic, IMAX scale, cinematic,
overwhelming force of nature, hopelessness, existential dread --ar 16:9
```

### 模板E · 科幻赛博压迫（巨型飞船/未来城市/AI统治）
```
Extreme low angle, fisheye 12mm lens, wide shot, deep depth of field,
a colossal [alien mothership/cyberpunk megastructure/AI monolith] hovering/looming overhead,
neon-lit city streets far below, tiny human figures looking skyward,
foreground: rain drops on lens, holographic ads reflecting in puddles, flying vehicle debris,
midground: the massive structure blocking out sky, emitting [energy beams/blue light/tractor beam],
background: endless [cyberpunk cityscape/red planet surface/dark space], thousands of lights,
neon noir lighting, cyan and magenta color palette against deep black, heavy rain atmosphere, volumetric fog, holographic glow,
Blade Runner 2049 aesthetic, cyberpunk, sci-fi concept art, Denis Villeneuve cinematic style,
8K, anamorphic widescreen, lens flare, atmospheric haze,
oppressive technological dominance, futuristic dread, inhuman scale --ar 21:9
```

### 模板F · 神圣/宗教压迫（巨型神像/圣殿/神降临）
```
Extreme low angle, wide-angle 20mm lens, extreme wide shot, deep depth of field,
a colossal [god statue/angelic being/divine figure] descending/standing tall, blinding radiance behind,
tiny worshippers/pilgrims kneeling at the bottom,
foreground: incense smoke/swirling mist/marble steps leading up,
midground: the divine figure emanating light, multiple arms/wings/halo,
background: golden clouds/beam of light from heaven/grand cathedral architecture stretching up,
overwhelming backlight creating bright halo/silhouette, golden white light with deep blue shadows, divine volumetric rays,
Baroque religious painting meets epic fantasy, Zdzisław Beksiński meets classical religious art,
8K, cinematic, hyper detailed, awe-striking,
religious awe mixed with terror, sublime beauty, overwhelming divinity, fear of god --ar 16:9
```

### 模板G · 幽闭窒息·长焦压缩派（原教程沙虫范式——直面巨兽/无处可逃）
```
Low camera position below chest level, slight upward tilt about 15°,
extreme telephoto cinematic lens (200mm+), strong spatial compression effect,
composite framing: close-up of [压迫源特写：巨兽巨口/枪口/黑洞/巨眼/深渊入口] flaring open like [喇叭/深渊/漩涡], occupying upper four-fifths of frame height, one-third width positioned slightly off-center left/right, edges wrapped in dense [sandstorm/smoke/fog/particles] with clear boundary between subject and particles, partial obstruction by particles in front,
five [soldiers/figures/people] in near shot positioned at the very bottom edge of frame, existing solely as scale reference, slightly out of focus retaining only silhouettes and local highlights,
shallow depth of field: focus locked on the dark interior of the [threat orifice/core/eye], foreground figures slightly defocused, background completely dissolved into [sandstorm/haze/abyss/darkness], no clear background,
no rim light separation, desaturated wasteland color palette, dirt brown/sand beige/lead grey tones, extreme low saturation stripping all emotional warmth, creating brutal documentary/archive footage realism, harsh flat lighting with local specular highlights on armor/debris,
cinematic, gritty, desaturated, wasteland aesthetic, photorealistic,
claustrophobic dread, inescapable doom, overwhelming force directly in your face, no room to run, suffocating tension, brutal survival horror --ar 16:9
```

**中文版（原教程沙虫范式适配即梦/可灵/Kling）**：
```
低机位仰视，摄像机高度接近胸口以下位置，镜头整体向上倾斜约15°，超长焦电影镜头，极强空间压缩感。
复合构图：[压迫源：巨口/洞口/巨眼/枪口]向外张开呈[喇叭状/漩涡状/深渊状]特写，高度占据画面上方约五分之四空间，宽度占画面中间略偏[左/右]三分之一的空间，压迫源边缘被浓厚[沙暴/浓雾/烟尘/黑暗]包裹，边缘与粒子分界清晰，口部/核心前景有粒子遮挡。[3-5名被压迫者]近景，位于画面最底部边缘，仅作为尺度参照物存在，整体轻微失焦，仅保留轮廓与局部高光。
浅景深：焦点明确锁定于[压迫源核心黑暗/瞳孔/洞口内部]区域，前景人物轻微失焦，背景完全融化于[沙暴/浓雾/烟尘/黑暗]中，无清晰背景。
极低饱和度，废土色调，土黄/沙褐/铅灰为主色，剥夺画面情感温度，极度写实历史档案般粗粝感，硬光，局部高光点缀，无轮廓光分离，
电影感，粗粝纪实，压迫感，无可逃遁的幽闭恐惧，窒息感，直面毁灭 --ar 16:9
```

**⚠️ 原教程沙虫完整Prompt（中文原文，可直接使用）**：
> 低机位仰视，摄像机高度接近人类胸口以下位置，镜头整体向上倾斜约15°。超长焦电影镜头，极强空间压缩感。复合构图。沙虫巨口向外张开，呈喇叭状，特写，高度占据画面上方约五分之四空间，宽度占画面中间略偏左三分之一的空间。沙虫巨口边缘被浓厚沙暴包裹，边缘和沙尘分界清晰。沙虫口部前景不少沙尘遮挡。五名战士近景，位于画面最底部边缘，仅作为尺度参照物存在。浅景深。前景战士整体轻微失焦，仅保留轮廓与局部高光。焦点明确锁定于沙虫巨口内部黑暗区域。背景完全融化于沙暴中。极低饱和度，废土色调，极度写实、历史档案般的粗粝感，残酷生存与死亡的氛围。

---

## 视频生成适配（Kling/可灵/即梦/Seedance/Sora）

如果是AI视频生成，在Prompt前加镜头运动：

| 想达到的效果 | 添加的运镜词 |
|-------------|-------------|
| 压迫感升级（主体逼近） | `slow push in / dolly forward / zoom in slowly` |
| 揭示巨大全貌 | `crane up / slow reveal / tilting up from ground to sky` |
| 不安感加强 | `handheld camera shake / subtle handheld tremor` |
| 史诗拉远 | `slow pull back / dolly out revealing scale` |
| 荷兰角悬疑 | `slow dutch tilt rotation / camera tilting sideways` |

视频Prompt追加示例：`slow push in camera, handheld subtle shake, dust particles floating, 24fps cinematic, dramatic tension building`

---

## 负面Prompt（通用）

```
blurry, low quality, deformed, cartoon, anime style (unless specified), bright cheerful lighting, flat lighting, happy mood, wide angle distortion artifacts, extra limbs, bad anatomy, text, watermark, logo, oversaturated
```

针对特定题材补充：
- 巨物类：`small creature, normal scale building, tiny object`
- 战争类：`peaceful scene, empty battlefield, modern weapons in period piece`
- 恐怖类：`comedic, cartoonish monster, bright colorful`
- 科幻类：`medieval elements, nature landscape, peaceful utopia`

---

## 使用流程（执行时按此步骤）

1. **识别用户意图**：用户想要什么类型的压迫感？（巨物扑来/战场史诗/悬疑不安/末日灾难/赛博科幻/神圣压迫/幽闭窒息）
2. **选对流派（最关键决策）**：
   - 想要"怪物/海啸/飞船泰山压顶迎面扑来"→ **超广角派**（模板A/B/D/E/F）
   - 想要"直面威胁、无处可逃、被贴脸杀"→ **长焦压缩派**（模板G）
3. **询问或推断关键参数**（如果用户没说全）：
   - 压迫源是什么？（巨兽/军队/灾难/建筑/飞船/神明）
   - 场景环境？（战场/城市/太空/古代/未来/深海/天空）
   - 色调偏好？（冷蓝/末日红/赛博霓虹/神圣金光/黑暗恐怖）
   - 画幅比例？（16:9电影横屏/9:16竖屏短视频/21:9超宽银幕）
   - 用途？（静态图/视频分镜/漫画分镜/海报）
4. **选择最匹配的模板**（A-G），填充方括号中的具体元素
5. **按七层法校验**（见第5层）：检查尺度对比、流派选择、焦点锁定、背景处理、饱和度、情绪词是否都到位
6. **输出Prompt**：给出中英文双版本（中文给即梦/可灵/Kling，英文给Midjourney/SD/Sora），并附上简短的"为什么这样写"的设计说明（解释每个关键视觉决策对应的心理效果）
7. **如有参考图**：引导用户先描述参考图，按五层法拆解后再生成Prompt，或直接用图生图配合此Prompt

## 输出格式

给用户的输出应包含：
1. 🎯 **画面描述**（一句话概括最终画面）
2. 📷 **镜头语言解析**（四维参数+为什么这样选）
3. ✨ **中文版Prompt**（适用于即梦/可灵/Kling/文心一格等国产工具）
4. 🌍 **English Prompt**（适用于Midjourney/Stable Diffusion/DALL-E/Sora/Runway/Pika）
5. 🎬 **视频运镜建议**（如适用）
6. 🧠 **设计说明**（3-5条关键视觉决策及其心理学依据，帮助用户理解并灵活调整）

---

## 变体扩展

用户说这些词时也适用本技能：
- "史诗感画面""大场面""IMAX感""电影感"
- "巨物恐惧""Boss出场""压迫感""泰山压顶"
- "广角仰拍""低角度""荷兰角""低机位"
- "分镜提示词""AI生图prompt""AI绘图提示词""电影镜头prompt"
- "末日场景""战争场面""巨兽登场""神降临""巨型建筑"
- "给我写个XX场景的Midjourney/即梦prompt""用AI画一个XX镜头"
