# Poster Design Agent

面向商业营销视觉的企业级 Agent Skill，适用于海报、Banner、App 活动页、小程序运营图、小红书封面、电商促销、数码产品推广和金融科技营销视觉。

## 能力范围

- 结构化需求采集
- 业务类型识别
- 营销与素材风险检查
- 视觉策略
- 页面布局
- AI 图片生成提示词
- Figma 生产建议
- 现有设计修改约束
- 设计审核与投放判断

## 目录

```text
poster-design-agent/
├── SKILL.md
├── README.md
├── references/
│   ├── brief-intake.md
│   ├── poster-design-guidelines.md
│   ├── font-licensing.md
│   ├── scenario-playbooks.md
│   └── marketing-compliance.md
├── examples/
│   ├── banner-example.md
│   ├── xiaohongshu-example.md
│   ├── app-campaign-example.md
│   └── finance-example.md
└── assets/
    ├── color.md
    ├── typography.md
    └── layout.md
```

## 使用方式

当用户提出“设计海报、做 Banner、优化活动页、审核营销图、生成图片 Prompt”等需求时，优先读取 `SKILL.md`。

设计前按 `references/brief-intake.md` 建立 Brief。

涉及具体场景时读取 `references/scenario-playbooks.md`。

涉及公开投放、促销、金融、支付、分期、租赁、平台合作时读取 `references/marketing-compliance.md`。

最终视觉方案与审核以 `references/poster-design-guidelines.md` 为基础。

含文字的正式稿必须读取 `references/font-licensing.md`，使用许可证可追溯的字体，并记录字体与许可证；AI 直接生成的文字仅作为概念占位。

## 设计原则

合规与真实性 > 商业目标 > 品牌一致性 > 用户可读性 > 视觉表现 > 制作效率。

## 版本建议

建议每次重要修改在 GitHub Commit Message 中标明：

- `feat:` 新能力
- `fix:` 规则修复
- `docs:` 文档优化
- `refactor:` 结构调整

示例：

`feat: add finance campaign compliance checklist`
