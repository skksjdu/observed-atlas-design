# Observed Atlas System

Observed Atlas System（OAS）是一套面向 Codex 的视觉设计 Skill，用于创作具有主体依据、编辑层级、材料感和结构性几何的艺术海报、主视觉及相关视觉界面。

它不把“几何线条”“技术标注”或“拼贴纹理”当作固定风格，而是从主题内部推导视觉关系：

> **subject → observation operation → structural response → evidence trail**

## 设计目标

- 让主体本身发生可见的表征变化，而不是在完整主体周围添加装饰性分析。
- 保留可识别的语义锚点，同时通过时间、材料、尺度、位移或状态变化建立抽象载体。
- 使用成体系的块面、遮罩、裁切、轴线、弧线和长距离连接组织画面。
- 保持主体的解剖、承重、连接、比例与功能关系可信。
- 将准确文字与可编辑排版留给可控的 SVG、HTML、CSS 或其他确定性图层。

## 主要特性

- 自动判断适合 OAS 的开放式视觉主题，不要求用户使用内部方法术语。
- 内置四张正向视觉锚点，并按关系而不是题材类别选择参考。
- 要求将锚点作为真实图片输入，而不是只在提示词中复述风格。
- 开放式海报至少探索并查看两种不同的栅格或混合媒介候选。
- 避免纯 SVG 代替主视觉生成、随机 HUD、虚构测量数据和无根据的鲜艳信号色。
- 抑制未被要求的电影概念图惯性，例如居中写实主体、戏剧性天空、月亮、湿地反光、体积光和暖窗光。
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

当前版本处于稳定维护阶段。源码、安装副本和 ZIP 的 9 个文件已通过逐文件一致性检查，源码与安装副本均通过官方 Skill 校验；建筑任务完成过实际锚点输入、双候选生成和最终渲染审查。

生命主题回归暴露并修正了“为了候选差异而切换时代、媒介和纪实类型”的问题。候选现在默认共享同一视觉语言边界，只在题材、关系、艺术化机制和构图上变化。该修正规则已静态验证，仍需下一次全新生成任务确认实际视觉行为。

## 许可

当前仓库未附加开源许可证。除非另有说明，公开可见不等于授予复制、修改或再分发许可。
