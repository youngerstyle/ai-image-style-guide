# AI 图像风格扫盲手册 - 设计文档

## 项目概述

**目标**：创建一本面向 AI 绘图新手的百科全书式风格指南，帮助用户从零开始理解图像风格概念。

**目标读者**：AI 绘图新手，完全不了解风格概念，需要从零开始学习

**语言**：中英对照，每个概念都有中英双语解释，方便用户在英文 prompt 中使用

**规模**：百科全书式，200+ 风格，深入讲解每个风格的历史背景、代表艺术家、变体等

**结构**：双轨并行式
- 教程轨：系统学习，循序渐进
- 词典轨：快速查阅，"我要什么"导向

---

## 目录结构

```
docs/style-guide/
├── README.md                    # 手册导航页
│
├── tutorial/                    # 教程轨 - 系统学习
│   ├── 00-前言.md
│   ├── 01-认识风格/
│   │   ├── 01-什么是图像风格.md
│   │   ├── 02-风格从哪里来.md
│   │   └── 03-AI绘图中的风格.md
│   ├── 02-风格的构成要素/
│   │   ├── 01-构图与版式.md
│   │   ├── 02-色彩与调性.md
│   │   ├── 03-光影与氛围.md
│   │   ├── 04-线条与形状.md
│   │   ├── 05-材质与质感.md
│   │   └── 06-媒介与技法.md
│   ├── 03-常见风格分类/
│   │   ├── 01-按时代划分.md
│   │   ├── 02-按地域划分.md
│   │   ├── 03-按媒介划分.md
│   │   └── 04-按用途划分.md
│   └── 04-如何选择风格/
│       ├── 01-明确你的目的.md
│       ├── 02-从参考图找灵感.md
│       └── 03-组合与创新.md
│
├── dictionary/                  # 词典轨 - 快速查阅
│   ├── README.md               # 词典使用指南
│   ├── by-category/            # 按分类浏览
│   │   ├── 01-艺术流派.md
│   │   ├── 02-设计风格.md
│   │   ├── 03-插画风格.md
│   │   ├── 04-摄影风格.md
│   │   ├── 05-3D与数字艺术.md
│   │   ├── 06-文化与地域风格.md
│   │   ├── 07-时代与复古风格.md
│   │   └── 08-特殊效果与技法.md
│   ├── by-purpose/             # 按目的浏览 "我想要..."
│   │   ├── 01-可爱萌系.md
│   │   ├── 02-酷炫科技.md
│   │   ├── 03-复古怀旧.md
│   │   ├── 04-优雅精致.md
│   │   ├── 05-暗黑神秘.md
│   │   ├── 06-清新自然.md
│   │   ├── 07-抽象艺术.md
│   │   └── 08-写实逼真.md
│   └── alphabetical/           # 字母索引
│       └── index.md            # A-Z 完整索引
│
└── appendix/                    # 附录
    ├── prompt-templates.md     # Prompt 模板集
    ├── resources.md            # 学习资源
    └── glossary.md             # 术语表
```

---

## 教程轨内容规划

### 00-前言.md
- 这本手册是什么
- 为谁写的
- 怎么使用这本手册
- 教程轨 vs 词典轨的区别

### 01-认识风格/

#### 01-什么是图像风格.md
- 风格的定义（中英对照）
- 为什么风格重要
- 风格 vs 主题 vs 内容的区别
- 同一主题不同风格的对比示例

#### 02-风格从哪里来.md
- 艺术史简述：从古典到当代
- 技术发展对风格的影响
- 文化背景与风格的关系
- 风格的演变与融合

#### 03-AI绘图中的风格.md
- AI 如何理解和生成风格
- Prompt 中风格词的作用
- 风格词的权重和组合
- 常见 AI 绘图工具的风格特点

### 02-风格的构成要素/

#### 01-构图与版式.md
- 构图基础概念
- 常见构图类型：对称、三分法、黄金分割、对角线...
- 版式与留白
- 构图相关 prompt 词汇

#### 02-色彩与调性.md
- 色彩基础：色相、饱和度、明度
- 色调与情绪
- 常见配色方案
- 色彩相关 prompt 词汇

#### 03-光影与氛围.md
- 光源类型
- 明暗对比
- 氛围营造
- 光影相关 prompt 词汇

#### 04-线条与形状.md
- 线条特征：粗细、曲直、风格化程度
- 几何形状 vs 有机形状
- 轮廓与边缘处理
- 线条相关 prompt 词汇

#### 05-材质与质感.md
- 表面质感：光滑、粗糙、纹理
- 透明度与反射
- 材质的情感表达
- 材质相关 prompt 词汇

#### 06-媒介与技法.md
- 传统媒介：油画、水彩、素描、版画...
- 数字媒介：矢量、像素、3D...
- 混合媒介
- 媒介相关 prompt 词汇

### 03-常见风格分类/

#### 01-按时代划分.md
- 古典时期风格
- 现代主义风格
- 当代风格
- 未来主义风格

#### 02-按地域划分.md
- 东方风格：中国、日本、韩国...
- 西方风格：欧洲、美国...
- 其他地域特色

#### 03-按媒介划分.md
- 绘画类风格
- 摄影类风格
- 3D/CG 类风格
- 混合媒介风格

#### 04-按用途划分.md
- 插画风格
- 海报/平面设计风格
- UI/界面设计风格
- 概念艺术风格
- 游戏/动画风格

### 04-如何选择风格/

#### 01-明确你的目的.md
- 想表达什么情感/信息
- 目标受众是谁
- 使用场景是什么

#### 02-从参考图找灵感.md
- 如何分析一张图的风格
- 拆解风格要素
- 找到关键风格词

#### 03-组合与创新.md
- 风格混搭技巧
- 避免风格冲突
- 发展个人风格

---

## 词典轨内容规划

### 按分类浏览 (by-category/)

每个分类文件包含该类别下的所有风格，每个风格条目包含：
- 风格名称（中英对照）
- 简介（100-200字）
- 视觉特征
- 历史背景
- 代表艺术家/作品
- 变体与相关风格
- Prompt 关键词
- 示例 prompt

#### 01-艺术流派.md
涵盖风格（约30个）：
- 印象派 Impressionism
- 后印象派 Post-Impressionism
- 表现主义 Expressionism
- 立体主义 Cubism
- 超现实主义 Surrealism
- 抽象表现主义 Abstract Expressionism
- 波普艺术 Pop Art
- 极简主义 Minimalism
- 达达主义 Dadaism
- 野兽派 Fauvism
- 新艺术运动 Art Nouveau
- 装饰艺术 Art Deco
- 巴洛克 Baroque
- 洛可可 Rococo
- 文艺复兴 Renaissance
- 浪漫主义 Romanticism
- 现实主义 Realism
- 自然主义 Naturalism
- 象征主义 Symbolism
- 构成主义 Constructivism
- 未来主义 Futurism
- 至上主义 Suprematism
- 新表现主义 Neo-Exprenism
- 概念艺术 Conceptual Art
- 街头艺术 Street Art
- 涂鸦艺术 Graffiti Art
- ...

#### 02-设计风格.md
涵盖风格（约25个）：
- 扁平化设计 Flat Design
- 拟物化设计 Skeuomorphism
- 材质设计 Material Design
- 新拟态 Neumorphism
- 玻璃拟态 Glassmorphism
- 瑞士风格 Swiss Style
- 包豪斯 Bauhaus
- 孟菲斯 Memphis
- 极简主义设计 Minimalist Design
- 野兽派设计 Brutalist Design
- 复古设计 Retro Design
- 蒸汽波 Vaporwave
- 赛博朋克 Cyberpunk
- 蒸汽朋克 Steampunk
- 柴油朋克 Dieselpunk
- 生物朋克 Biopunk
- Y2K 风格
- 酸性设计 Acid Graphics
- 迷幻风格 Psychedelic
- 波西米亚 Bohemian
- 斯堪的纳维亚设计 Scandinavian Design
- 日式设计 Japanese Design
- 中式设计 Chinese Design
- ...

#### 03-插画风格.md
涵盖风格（约35个）���
- 日系动漫 Anime
- 美式卡通 American Cartoon
- 欧洲漫画 European Comics
- 韩系插画 Korean Illustration
- 扁平插画 Flat Illustration
- 线条插画 Line Art
- 矢量插画 Vector Illustration
- 水彩插画 Watercolor Illustration
- 手绘风格 Hand-drawn
- 涂鸦风格 Doodle
- 儿童插画 Children's Illustration
- 时尚插画 Fashion Illustration
- 科学插画 Scientific Illustration
- 建筑插画 Architectural Illustration
- 社论插画 Editorial Illustration
- 概念插画 Concept Art
- 角色设计 Character Design
- Q版/赤壁 Chibi
- 像素艺术 Pixel Art
- 低多边形 Low Poly
- 等距插画 Isometric
- 信息图表 Infographic
- 贴纸风格 Sticker Style
- 徽章风格 Badge Style
- 复古插画 Vintage Illustration
- 波普插画 Pop Art Illustration
- 超现l Illustration
- 暗黑插画 Dark Illustration
- 奇幻插画 Fantasy Illustration
- 科幻插画 Sci-fi Illustration
- 恐怖插画 Horror Illustration
- 浪漫插画 Romantic Illustration
- 治愈系插画 Healing Illustration
- ...

#### 04-摄影风格.md
涵盖风格（约25个）：
- 人像摄影 Portrait Photography
- 风景摄影 Landscape Photography
- 街头摄影 Street Photography
- 纪实摄影 Documentary Photography
- 时尚摄影 Fashion Photography
- 商业摄影 Commercial Photography
- 产品摄影 Product Photography
- 美食摄影 Food Photography
- 建筑摄影 Architectural Photography
- 微距摄影 Macro Photography
- 航拍摄影 Aerial Photography
- 黑白摄影 Black and White Photography
- 胶片摄影 Film Photography
- 宝丽来 Polaroid
- 双重曝光 Double Exposure
- 长曝光 Long Exposure
- 高速摄影 High-speed Photography
- HDR 摄影
- 红外摄影 Infrared Photography
- 移轴摄影 Tilt-shift Photography
- 鱼眼摄影 Fisheye Photography
- 剪影摄影 Silhouette Photography
- 逆光摄影 Backlit Photography
- 低调摄影 Low-key Photography
- 高调摄影 High-key Photography
- ...

#### 05-3D与数字艺术.md
涵盖风格（约30个）：
- 写实3D Photorealistic 3D
- 卡通3D Cartoon 3D
- 低多边形3D Low Poly 3D
- 等距3D Isometric 3D
- 体素艺术 Voxel Art
- 粘土风格 Claymation/Clay Style
- 玻璃质感 Glass Material
- 金属质感 Metallic
- 霓虹风格 Neon Style
- 全息风格 Holographicitch Art
- 数据可视化 Data Visualization
- 生成艺术 Generative Art
- 分形艺术 Fractal Art
- 粒子艺术 Particle Art
- 流体艺术 Fluid Art
- 数字拼贴 Digital Collage
- 照片处理 Photo Manipulation
- 数字绘画 Digital Painting
- 概念渲染 Concept Rendering
- 产品渲染 Product Rendering
- 建筑可视化 Architectural Visualization
- 游戏美术 Game Art
- 电影概念艺术 Film Concept Art
- VR/AR 艺术
- NFT 艺术风格
- AI 艺术风格
- 赛博风格 Cyber Style
- 未来主义3D Futuristic 3D
- 复古3D Retro 3D
- ...

#### 06-文化与地域风格.md
涵盖风格（约25个）：
- 中国风 Chinese Style
- 日本风 Japanese Style
- 韩国风 Korean Style
- 东南亚风格 Southeast Asian Style
- 印度风格 Indian Style
- 中东风格 Middle Eastern Style
- 非洲风格 African Style
- 拉丁美洲风格 Latin American Style
- 北欧风格 Nordic Style
- 地中海风格 Mediterranean Style
- 美式风格 American Style
- 英伦风格 British Style
- 法式风格 French Style
- 意大利风格 Italian Style
- 德式风格 German Style
- 俄罗斯风格 Russian Style
- 波西米亚风格 Bohemian Style
- 摩洛哥风格 Moroccan Style
- 墨西哥风格 Mexican Style
- 巴西风格 Brazilian Style
- 澳洲原住民风格 Aboriginal Style
- 凯尔特风格 Celtic Style
- 希腊风格 Greek Style
- 埃及风格 Egyptian Style
- 玛雅风格 Mayan Style
- ...

#### 07-时代与复古风格.md
涵盖风格（约20个）：
- 古典风格 Classical
- 中世纪风格 Medieval
- 文艺复兴风格 Renaissance Style
- 维多利亚风格 Victorian
- 爱德华风格 Edwardian
- 20年代风格 1920s/Roaringies
- 30年代风格 1930s/Art Deco Era
- 40年代风格 1940s/Wartime
- 50年代风格 1950s/Mid-century
- 60年代风格 1960s/Mod
- 70年代风格 1970s/Disco
- 80年代风格 1980s/Synthwave
- 90年代风格 1990s/Grunge
- Y2K 风格 Y2K/Millennium
- 复古未来主义 Retro-futurism
- 原子时代 Atomic Age
- 太空时代 Space Age
- 蒸汽时代 Steam Age
- 工业时代 Industrial Age
- 数字时代 Digital Age
- ...

#### 08-特殊效果与技法.md
涵盖风格（约20个）：
- 双重曝光 Double Exposure
- 故障效果 Glitch Effect
- 色差效果 Chromatic Aberration
- 颗粒效果 Grain Effect
- 模糊效果 Blur Effect
- 景深效果 Depth of Field
- 运动模糊 Motion Blur
- 光晕效果 Lens Flare
- 散景效果 Bokeh
- 剪影效果 Silhouette
- 负片效果 Neg调效果 Halftone
- 波普效果 Pop Art Effect
- 素描效果 Sketch Effect
- 油画效果 Oil Paint Effect
- 水彩效果 Watercolor Effect
- 马赛克效果 Mosaic Effect
- 像素化效果 Pixelation
- 浮雕效果 Emboss Effect
- 霓虹效果 Neon Effect
- ...

### 按目的浏览 (by-purpose/)

每个文件聚焦一种创作目的/情感需求，列出适合的风格：

#### 01-可爱萌系.md
- Chibi/Q版
- Kawaii/卡哇伊
- 儿童插画
- 卡通风格
- 粘土风格
- 圆润3D
- 治愈系插画
- 贴纸风格
- ...

#### 02-酷炫科技.md
- 赛博朋克
- 霓虹风格
- 全息风格
- 故障艺术
- 科幻插画
- 未来主义
- 数据可视化
- ...

#### 03-复古怀旧.md
- 各年代风格
- 胶片摄影
- 复古插画
- 蒸汽波
- 像素艺术
- 复古海报
- ...

#### 04-优雅精致.md
- 新艺术运动
- 装饰艺术
- 时尚插画
- 极简主义
- 法式风格
- 水彩风格
- ...

#### 05-暗黑神秘.md
- 哥特风格
- 暗黑插画
- 恐怖风格
- 低调摄影
- 表现主义
- 超现实主义
- ...

#### 06-清新自然.md
- 水彩风格
- 自然主义
- 北欧风格
- 植物插画
- 风景摄影
- 治愈系
- ...

#### 07-抽象艺术.md
- 抽象表现主义
- 几何抽象
- 极简主义
- 构成主义
- 生成艺术
- 分形艺术
- ...

#### 08-写实逼真.md
- 超写实主义
- 照片级渲染
- 写实油画
- 人像摄影
- 产品摄影
- 建筑可视化
- ...

### 字母索引 (alphabetical/)

#### index.md
- A-Z 完整索引
- 每个风格名称链接到对应的分类文件位置
- 包含中英文名称

---

## 附录内容规划

### prompt-templates.md
- 通用 prompt 结构模板
- 各风格专用 prompt 模板
- 风格组合 prompt 示例
- 常用修饰词列表

### resources.md
- 推荐学习资源
- 参考网站
- 工具推荐
- 社区推荐

### glossary.md
- 专业术语表
- 中英对照
- 简短解释

---

## 风格条目模板

每个风格条目采用统一格式：

```markdown
## 风格名称 English Name

**别名**：其他名称 / Other Names

**简介**：
100-200字的风格介绍，包含定义和核心特征。

**视觉特征**：
- 特征1
- 特征2
- 特征3

**历史背景**：
风格的起源、发展、代表时期。

**代表艺术家/作品**：
- 艺术家1 - 代表作品
- 艺术家2 - 代表作品

**变体与相关风格**：
- 相关风格1
- 相关风格2

**Prompt 关键词**：
`keyword1`, `keyword2`, `keyword3`

**示例 Prompt**：
```
完整的示例 prompt
```

**适用场景**：
- 场景1
- 场景2
```

---

## 实施计划

1. 创建目录结构
2. 撰写教程轨内容（按章节顺序）
3. 撰写词典轨内容（按分类）
4. 撰写附录内容
5. 创建导航页和索引
6. 整体校对和优化

---

## 参考资源

- 项目内 awesome-nano-banana 案例库
- 项目内 MidJourney-Styles-and-Keywords-Reference
- 现有 README.md 中的风格分类草稿
