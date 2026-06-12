# Example: Business Review｜经营复盘

This example shows how to use **PPT Blueprint Guide** for a quarterly business review deck.

本示例展示如何用 **PPT Blueprint Guide** 规划一份季度经营复盘类 PPTX。

---

## User Input｜用户输入

```text
你作为公司采购部负责人，现在需要做 2026 年 4-6 月水果品类复盘。
请根据向导协助我完成内容规划，数据先用 mock 数据代替。
```

---

## Recommended Direction｜推荐方向

- Scenario｜场景：工作汇报 / 经营复盘
- Design Mode｜设计模式：Formal Business Enhanced
- Industry Visual System｜行业视觉：生鲜食品
- Ratio｜比例：16:9
- Output｜输出：Editable PPTX

---

## PAGE_BLUEPRINT_USER_VIEW｜页面规划表

| Slide | Goal 页面目标 | Conclusion Title 结论标题 | Layout 推荐版式 | Image Asset 配图 | Chart / Logic 图表或逻辑图 |
|---|---|---|---|---|---|
| Slide 1 | 建立主题识别 | Q2 水果品类复盘：规模增长背后，结构效率更关键 | 大标题 + 主题图 | 水果主题氛围图 | 无 |
| Slide 2 | 先给管理层结论 | 增长主要由 TOP 商品拉动，长尾商品贡献仍有限 | KPI 看板 + 三张结论卡 | 不配图 | KPI Cards |
| Slide 3 | 展示销售趋势 | 4-6 月销售稳步增长，但节日节点贡献更集中 | 左侧折线图 + 右侧解释卡 | 不配图 | Native Line Chart |
| Slide 4 | 拆解类目结构 | 高客单水果贡献毛利，基础水果承担规模 | 环形图 + 横向对比卡 | 可选水果小图 | Native Donut Chart |
| Slide 5 | 分析 TOP 商品 | TOP 10 商品贡献主要销售额，爆品运营仍是增长关键 | 排名页 / 双栏数据对比 | 不配图 | Native Bar Chart / Pareto |
| Slide 6 | 分析供应商表现 | 供应商贡献高度集中，需要管理中腰部履约风险 | 四象限 / 表格卡片 | 不配图 | Editable Table / Quadrant |
| Slide 7 | 识别问题 | 增长质量的核心风险在于结构单一和履约波动 | 问题 / 原因 / 对策 | 不配图 | Shapes + Connectors |
| Slide 8 | 给出行动方案 | 下季度应从爆品、结构、供应商三条线同步优化 | 三栏策略卡 | 轻量水果场景图 | SmartArt / Shapes |

---

## DESIGN_SYSTEM_SPEC｜视觉系统规范

- Aspect Ratio: 16:9
- Design Mode: Formal Business Enhanced
- Industry: 生鲜食品
- Palette: 自然绿
  - Primary: #166534
  - Secondary: #86EFAC
  - Background: #F7FEE7
  - Text: #111827
  - Accent: #F97316
- Font Stack:
  - Chinese: Microsoft YaHei / PingFang SC
  - English: Aptos / Arial
- Typography Scale:
  - Cover Title: 44–56 pt
  - Page Title: 28–34 pt
  - Body Text: 16–20 pt
  - Caption / Label: 10–13 pt
- Layout Grid: 12-column grid, strong margins, clean business spacing
- Chart Style: native editable charts, no rainbow colors, readable labels
- Image Treatment: fresh, natural, restrained; images support category recognition only

---

## BUILD_RULES｜制作约束

- File Type: Editable .pptx
- Quality Level: Formal design-enhanced version
- Image Asset: Cover image required; key pages may use suitable visuals
- Native Chart: Data pages use editable native charts when possible
- Logic Diagram: Logic pages use SmartArt / Shapes / Connectors
- Editable Objects: Titles, body text, numbers, charts and diagrams must remain editable
- No Full-page Image: Do not turn slides into flat images unless explicitly requested

---

## FINAL_BUILD_INPUT｜最终制作输入包

- File Type: Editable .pptx
- Slide Count: 8
- Aspect Ratio: 16:9
- System: Cross-platform
- Design Mode: Formal Business Enhanced
- Industry Visual System: 生鲜食品 / 自然绿
- Design Level: Formal design-enhanced version
- Image Strategy: Cover image required; key pages use restrained fruit visuals
- Editable Rule: Titles, numbers, charts, diagrams and tables remain editable
- No Full-page Image: Do not create flat image slides

## SLIDE_BUILD_LIST｜逐页制作清单

- Slide 1: 封面｜大标题 + 水果主题氛围图｜必须配图
- Slide 2: 核心摘要｜KPI 看板 + 三张结论卡｜可编辑数字
- Slide 3: 销售趋势｜Native Line Chart + 解释卡
- Slide 4: 类目结构｜Native Donut Chart + 对比卡
- Slide 5: TOP 商品｜Native Bar Chart / Pareto
- Slide 6: 供应商表现｜Editable Table / Quadrant
- Slide 7: 问题诊断｜Shapes + Connectors
- Slide 8: 行动方案｜SmartArt / Shapes + 轻量场景图
