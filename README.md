# Observed Atlas System

Observed Atlas System（OAS）是一套面向 Codex 的视觉设计 Skill，用于创作具有主体依据、编辑层级、材料感和结构性几何的艺术海报、主视觉及相关视觉界面。

它不把“几何线条”“技术标注”或“拼贴纹理”当作固定风格，而是从主题内部推导视觉关系：

> **subject → observation operation → structural response → evidence trail**

## 设计目标

- 让主体本身发生可见的表征变化，而不是在完整主体周围添加装饰性分析。
- 保留可识别的语义锚点，同时通过时间、材料、尺度、位移或状态变化建立抽象载体。
- 使用成体系的块面、遮罩、裁切、轴线、弧线和长距离连接组织画面。
- 保持主体的解剖、承重、连接、比例与功能关系可信。
- 用户未指定其他风格时，默认采用欧式古典绘图与纸本平面艺术语言；这是形式语言，不强制欧洲题材。
- 默认把主体、碎片、纸张、色块和线稿压在同一浅层画布中，不以电影场景或真实纵深作为空间骨架。
- 允许多个主体碎片，但每个主要碎片都必须提供不可替代的结构、材料、保存、功能、时间或绘制阶段信息。
- 不把复杂主体误判为杂乱；保留有意义的主体细节，通过降低几何、纹理、碎片和信号色等辅助层的对比、密度与覆盖范围建立清晰主次。
- 风格修订只改变媒介、线条和显著性，不默认删除原有的状态信息、混合材料、面积几何与长距离曲线；“压低”不等于“清空”。
- 将准确文字与可编辑排版留给可控的 SVG、HTML、CSS 或其他确定性图层。

## 主要特性

- 自动判断适合 OAS 的开放式视觉主题，不要求用户使用内部方法术语。
- 内置五张正向视觉锚点，并按关系而不是题材类别选择参考。
- 要求将锚点作为真实图片输入，而不是只在提示词中复述风格。
- 开放式海报至少探索并查看两种不同的栅格或混合媒介候选。
- 避免纯 SVG 代替主视觉生成、随机 HUD、虚构测量数据和无根据的鲜艳信号色。
- 抑制未被要求的电影概念图惯性，例如居中写实主体、戏剧性天空、月亮、湿地反光、体积光和暖窗光。
- 区分“欧式古典形式语言”和“欧洲题材语境”，不机械复制参考中的建筑、马、柱式、布局或纹样。
- 以缩略图平面感、真实手工绘图逻辑和碎片状态不可替代性作为默认验收门。
- 用缩略图或模糊检查确认一个主读法、受控的次级运动和真正连续的安静区域；少量低对比路线可以穿过留白，但反复出现的弧线、网格、噪点和碎片不能形成第二套活跃纹理。
- 通过渲染结果判断视觉质量，不以文件存在、XML 有效或哈希一致代替视觉审查。

## 目录结构

```text
outputs/
├── observed-atlas-design/
│   ├── SKILL.md
│   ├── agents/
│   │   └── openai.yaml
│   ├── assets/
│   │   ├── anchor-distributed-world-montage.webp
│   │   ├── anchor-editorial-interpenetration.png
│   │   ├── anchor-fragment-continuity.png
│   │   ├── anchor-growth-cycle-geometry.png
│   │   └── anchor-multi-representation-motion.png
│   └── references/
│       ├── design-language-spec.md
│       ├── positive-anchors.md
│       └── test-plan.md
└── observed-atlas-design.zip
```

## 安装

### 使用 ZIP

下载 `outputs/observed-atlas-design.zip`，解压到 Codex 的个人 Skill 目录：

```text
%USERPROFILE%\.codex\skills\observed-atlas-design
```

### 使用 Git

克隆公开仓库后，将 `outputs/observed-atlas-design` 目录复制到同一位置：

```powershell
git clone https://github.com/skksjdu/observed-atlas-design.git
```

安装后应保证 `SKILL.md` 位于：

```text
%USERPROFILE%\.codex\skills\observed-atlas-design\SKILL.md
```

建议在新任务中测试自动调用，避免用当前会话的既有上下文代替真实路由验证。

## 使用示例

可以直接使用普通视觉请求，不需要写出 OAS 的内部结构：

```text
制作一个建筑题材艺术海报，主题是和时间有关，欧式建筑，表现形式不限。
```

```text
做一张艺术视觉海报，主题是奔马，文字元素自行决定是否加入。
```

如需强制使用，也可以明确指定 `observed-atlas-design`。

## 当前状态

当前版本处于稳定维护阶段。源码、安装副本和 ZIP 保持 10 文件交付结构，并使用官方 Skill 校验与逐文件 SHA-256 检查维护一致性；建筑任务完成过实际锚点输入、双候选生成和最终渲染审查。

近期真实回归确认了欧式古典、平面浅空间和碎片状态规则能够改善方向，但也暴露了两个相反风险：辅助层同时高强度发声会造成杂乱，而把主体改成欧式线稿时又可能把几何、混合材料和状态信息一起删掉。当前规则要求在同一路径上耦合面积几何与线性几何，并在风格修订中通过重排显著性保留功能层；仍需后续独立生成确认实际行为。

## 许可

当前仓库未附加开源许可证。除非另有说明，公开可见不等于授予复制、修改或再分发许可。
