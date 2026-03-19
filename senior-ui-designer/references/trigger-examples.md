# 真实触发示例

用这份文档判断什么请求应该触发 `senior-ui-designer`，以及它更适合扮演什么角色。

## 应该触发

### 页面设计与改版

- 帮我把这个后台首页重新设计得更有层级感。
- 这个 SaaS 产品的定价页太普通了，给我一个更成熟的 UI 方向。
- 我有一版低保真草图，帮我整理成更像正式产品的界面方案。
- 这个移动端页面看起来很乱，帮我优化布局和视觉节奏。

### 品牌官网与营销页

- 帮我设计一个 AI 产品官网首页，要高级一些但还能转化。
- 这个落地页首屏不够有说服力，帮我重做结构和 CTA。
- 我们品牌官网太像模板站了，帮我定一个新的视觉风格。
- 给我一套适合 B2B 官网的 Hero、卖点区和案例区设计建议。

### 组件与规范

- 帮我定义这套按钮、表单和卡片的视觉规范。
- 把这版设计整理成可交付给前端的 token 和组件规范。
- 我们现在颜色和圆角很乱，帮我整理成统一的设计语言。
- 给我一套后台系统的状态色、间距和标题层级建议。

### UI Review

- 你从资深 UI 设计师角度 review 一下这个页面。
- 帮我指出这个界面最影响质感和可用性的 5 个问题。
- 我把截图给你，你帮我按严重程度做 UI 评审。
- 这个页面为什么看着不高级，帮我诊断并给出改法。

## 可能与其他技能组合触发

### 与 Web / 前端实现类技能组合

- 我有个 React 页面，帮我在不改功能的前提下重做 UI 并直接落代码。
- 根据这个 Figma 和现有代码，把页面做得更像成熟产品。
- 帮我先定视觉方向，再给出前端可实现的结构和样式建议。

这类请求里，`senior-ui-designer` 负责视觉方向、层级、规范和评审判断；实现类技能负责代码落地。

### 与产品 / PRD 类技能组合

- 我们还在定义产品，顺便帮我想一下这个核心页面应该怎么呈现。
- 写 PRD 的同时，把后台信息架构和关键页面布局也梳理一下。

这类请求里，产品类技能负责范围、目标和流程，`senior-ui-designer` 负责界面表达和信息层级。

## 一般不单独触发

- 帮我修一个按钮点击没反应的 bug。
- 帮我接一个后端接口并把数据展示出来。
- 帮我写数据库表结构。
- 帮我做一份纯品牌文案，不涉及页面结构和界面表达。

这些请求更偏工程实现、后端、数据或纯文案，不应只依赖本技能。

## 边界判断

- 如果用户核心诉求是“更清楚、更高级、更统一、更有转化、更像成熟产品”，优先触发。
- 如果用户给的是截图、Figma、现有页面或代码，但诉求聚焦在界面质量，也应触发。
- 如果用户主要要的是功能开发，且没有明确要求 UI 方向，可不优先触发。
- 如果用户要的是品牌表达加页面落地，通常应触发。

## 测试用示例请求

- Use $senior-ui-designer to redesign this B2B dashboard so it feels clearer and more premium.
- Use $senior-ui-designer to propose a landing page structure, visual direction, and CTA strategy for this AI tool.
- Use $senior-ui-designer to review this settings page and identify the most important UI issues.
- Use $senior-ui-designer to turn this rough page idea into a color, typography, and component direction.
