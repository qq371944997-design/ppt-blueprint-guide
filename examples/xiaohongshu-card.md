# Example: Xiaohongshu Card｜小红书图文卡片

This example shows how to use **PPT Blueprint Guide** for Xiaohongshu-style educational cards.

本示例展示如何用 **PPT Blueprint Guide** 规划一组小红书图文卡片。

---

## User Input｜用户输入

```text
我想做一组小红书图文，主题是：ChatGPT 做 PPT 老翻车？问题可能不是工具，是你没给它页面蓝图。
希望风格干净、有设计感、适合收藏。
```

---

## Recommended Direction｜推荐方向

- Scenario｜场景：小红书图文卡片 / AI 工具分享
- Design Mode｜设计模式：Magazine Card
- Industry Visual System｜行业视觉：小红书风格参考 / 黑白红杂志感
- Ratio｜比例：3:4
- Output｜输出：Editable PPTX or image cards

---

## PAGE_BLUEPRINT_USER_VIEW｜页面规划表

| Slide | Goal 页面目标 | Conclusion Title 结论标题 | Layout 推荐版式 | Image Asset 配图 | Chart / Logic 图表或逻辑图 |
|---|---|---|---|---|---|
| Slide 1 | 强钩子封面 | ChatGPT 做 PPT 老翻车？先别怪工具 | 大字杂志封面 | 不配图，使用几何块 | 无 |
| Slide 2 | 制造共鸣 | 很多人不是不会用 AI，而是直接跳过了页面蓝图 | 痛点卡片 | 不配图 | 3 个痛点标签 |
| Slide 3 | 解释核心概念 | Page Blueprint 是让 AI 先想清每一页怎么讲 | 概念解释页 | 线框页面示意图 | Shapes |
| Slide 4 | 展示流程 | 好的 PPT 生成，不是提示词越长越好，而是流程越清楚越好 | 流程页 | 不配图 | 5 步流程图 |
| Slide 5 | 强调可编辑 | 真正有用的 PPT，不只是好看，还要能改数据、改结构 | 对比页 | 不配图 | Before / After 对比 |
| Slide 6 | 给出方法 | 先确认页面蓝图，再确认视觉系统，最后再制作 | 方法卡片 | 不配图 | 三栏卡片 |
| Slide 7 | 总结收藏 | 记住这 4 个词，AI 做 PPT 会稳很多 | 收藏总结页 | 不配图 | 四个关键词模块 |

---

## DESIGN_SYSTEM_SPEC｜视觉系统规范

- Aspect Ratio: 3:4
- Design Mode: Magazine Card
- Industry: 小红书风格参考
- Palette: 黑白红杂志感
  - Primary: #111111
  - Secondary: #FFFFFF
  - Background: #F7F7F7
  - Text: #111111
  - Accent: #FF2442
- Font Stack:
  - Chinese: PingFang SC / Microsoft YaHei
  - English: Helvetica / Arial
- Typography Scale:
  - Cover Title: 46–60 pt
  - Page Title: 30–40 pt
  - Body Text: 18–22 pt
  - Caption / Label: 12–14 pt
- Layout Grid: vertical card grid, strong margins, large typography, minimal decoration
- Chart Style: use cards, labels and simple shapes instead of complex charts
- Image Treatment: mostly no photo; use geometric blocks, lines and typographic rhythm

---

## BUILD_RULES｜制作约束

- File Type: Editable .pptx or image cards if explicitly requested
- Quality Level: Formal design-enhanced version
- Image Asset: Not required; use typographic and geometric visuals
- Native Chart: Not needed
- Logic Diagram: Use editable Shapes / Connectors for flow and comparison pages
- Editable Objects: Titles, body text, labels and modules must remain editable
- No Full-page Image: Keep editable version unless user explicitly asks for PNG/JPG output

---

## FINAL_BUILD_INPUT｜最终制作输入包

- File Type: Editable .pptx
- Slide Count: 7
- Aspect Ratio: 3:4
- System: macOS / Cross-platform
- Design Mode: Magazine Card
- Industry Visual System: 小红书黑白红杂志感
- Design Level: Formal design-enhanced version
- Image Strategy: No photo by default; use typography, lines and geometric blocks
- Editable Rule: Titles, labels, modules and flow shapes remain editable
- No Full-page Image: Do not create flat image slides unless explicitly requested

## SLIDE_BUILD_LIST｜逐页制作清单

- Slide 1: 封面｜大字标题 + 红色强调块｜无配图
- Slide 2: 痛点共鸣｜三张痛点标签卡｜Shapes
- Slide 3: 概念解释｜线框页面示意图｜Editable Shapes
- Slide 4: 流程页｜5 步流程｜Shapes + Connectors
- Slide 5: 可编辑对比｜Before / After｜双栏结构
- Slide 6: 方法页｜三栏卡片｜Page Blueprint / Design System / Build Rules
- Slide 7: 总结页｜四个关键词模块｜收藏导向
