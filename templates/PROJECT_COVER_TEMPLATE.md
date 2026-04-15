# 项目封面模板说明

这套模板用于 GitHub 项目 README 顶部封面图，风格统一为：

- 英文主标题保留第一视觉
- 中文副标题固定放第二行
- 技术栈统一保留英文
- 流程节点统一采用“英文标题 + 中文说明”
- 整体适合“中文内容 + 国际感”的作品集展示

## 推荐结构

封面建议固定包含以下 6 个区域：

1. 顶部标签
   示例：`MULTI-AGENT SYSTEM`、`RESEARCH TOOL`、`VISUAL DASHBOARD`
2. 英文主标题
   示例：`Concept Stock Agent`
3. 中文副标题
   示例：`概念选股多智能体`
4. 一到两行中文价值说明
   示例：`把概念主题拆成产业链节点，扩展候选股票，再生成组合与回测结果`
5. 流程节点
   示例：`Planner / 确定研究目标`
6. 底部技术栈
   示例：`Python • Tushare • DeepSeek • Weighted Backtest`

## 推荐写法

### 顶部标签

- `MULTI-AGENT SYSTEM`
- `RESEARCH TOOL`
- `QUANT WORKFLOW`
- `VISUAL DASHBOARD`
- `LOCAL PRODUCT`

### 英文主标题

统一写成项目正式英文名，尽量控制在 2 到 4 个单词内。

### 中文副标题

统一写成一句简短定位，建议 6 到 12 个中文字符，避免太长。

### 中文价值说明

建议拆成两行，每行控制在 14 到 20 个中文字符左右。

### 流程节点

统一格式：

- 第一行：英文节点名
- 第二行：中文动作说明

推荐节点名示例：

- `Planner`
- `Chain Analyzer`
- `Node Expander`
- `Sector Worker`
- `Macro Worker`
- `Stock Worker`
- `Risk Worker`
- `Review + Build`

## 使用方式

### 蓝色模板

适合：

- 多智能体系统
- 量化研究工具
- 数据工作流

文件：

- [project-cover-template-blue.svg](/Users/xinwei/Documents/xinpipi-ai/templates/project-cover-template-blue.svg)

### 绿色模板

适合：

- 宏观事件
- 风险与对冲
- 事件驱动系统

文件：

- [project-cover-template-green.svg](/Users/xinwei/Documents/xinpipi-ai/templates/project-cover-template-green.svg)

## 替换字段清单

复制模板后，优先替换以下内容：

- `{{TOP_LABEL}}`
- `{{EN_TITLE}}`
- `{{CN_SUBTITLE}}`
- `{{CN_DESC_LINE_1}}`
- `{{CN_DESC_LINE_2}}`
- `{{STEP_1_TITLE}}` / `{{STEP_1_DESC}}`
- `{{STEP_2_TITLE}}` / `{{STEP_2_DESC}}`
- `{{STEP_3_TITLE}}` / `{{STEP_3_DESC}}`
- `{{STEP_4_TITLE}}`
- `{{STEP_4_DESC}}`
- `{{STACK_LINE}}`
- `{{BOTTOM_NOTE}}`

## 最佳实践

- README 正文写中文，封面图保留英文主标题
- 一个项目只保留一种主色，不要混多套风格
- 技术栈统一英文，便于兼顾国内外阅读
- 节点说明优先写“动作”，不要写空泛名词
- 如果项目没有流程节点，可以把第三个节点框改成 `Key Feature`

## 当前已采用这套规范的项目

- [Concept Stock Agent](https://github.com/xinpipi-ai/concept-stock-agent)
- [Macro Hotspot Agent](https://github.com/xinpipi-ai/macro-hotspot-agent)
