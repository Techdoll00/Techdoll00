<div align="center">

# 廖乃环 · Liaonaihuan

**AIGC 视觉创作 × Agent 产品工程**

</div>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Agent" src="https://img.shields.io/badge/-AI%20Agent-FF6B6B?style=flat-square&logo=openai&logoColor=white" />
  <img alt="AIGC" src="https://img.shields.io/badge/-AIGC-9B59B6?style=flat-square&logo=stablediffusion&logoColor=white" />
  <img alt="Eval" src="https://img.shields.io/badge/-Agent%20Eval-2ECC71?style=flat-square" />
  <img alt="Feishu" src="https://img.shields.io/badge/-Feishu-00D6B9?style=flat-square" />
  <img alt="Style3D" src="https://img.shields.io/badge/-Style3D%20Intern-1ABC9C?style=flat-square" />
</p>

---

## 我是谁

我不是算法派,也不是纯工程派。我是那个站在 **AIGC 视觉创作** 和 **Agent 产品工程** 之间、能把"模型 demo"推到"企业生产"的人。

- 在 [**Style3D**](https://www.linctex.com) 实习 5 个月,从 0 到 1 给服装 ODM 业务搭建了 Agent 评测体系、推款 Agent 工作流、20 家企业的数据治理标准
- 在 [**小影科技 AICatch**](https://www.aicatch.com) 做过 AIGC 设计师,30+ 个 AI 视频模板商用化,Stable Diffusion / Pika / Keling 实战派
- 在校期间主导过 48h Game Jam 像素 RPG 主程序、墙绘乡村振兴项目发起人、「视觉悦动」社团社长

我的差异化不是"做过 Agent",而是「**懂视觉创作 + 懂 Agent 产品 + 懂行业落地**」的跨界组合 —— 这个组合在多模态 AI 公司和垂直行业 AI 团队里都是稀缺的。

---

## 我在解决什么独特问题

**"AI Agent 在企业里从 demo 走到生产,中间缺什么?"**

我实习的时候发现:大多数 Agent 项目死在"能 demo,但不能上线"。原因不是模型不够强,而是缺一套**能拦截错误、能迭代回归、能在多会话/多业务线之间稳定运行**的工程基础设施。

所以我做的事情都围绕一个核心问题: **怎么让 Agent 在企业里真正可用,而不是停留在 demo?**

---

## 我的项目们是怎么互相支撑的

我故意没把项目做成孤立的"作品集",而是让它们形成一个闭环 —— 这是我的 Agent 工程方法论:

```
                    ┌────────────────────────────────────┐
                    │      agent-eval-tool (核心战场)        │
                    │  Style3D 实战验证过的 6 层评测框架         │
                    │  60 轮回归 0 事故 / 1-2 天 → 几分钟      │
                    └────────────────┬───────────────────┘
                                     │ 评测方法论
                    ┌────────────────▼───────────────────┐
                    │   Trend-agent / trend-ins           │
                    │   Fashion-Search                    │  ← Style3D 业务
                    │   (脱敏后的服装 Agent 实战代码)         │     实战沉淀
                    └────────────────┬───────────────────┘
                                     │ 业务 Know-how
            ┌────────────────────────┼────────────────────────┐
            │                        │                        │
┌───────────▼────────┐  ┌───────────▼────────┐  ┌───────────▼────────┐
│ ai-news-briefing    │  │ hermes-skills-      │  │ feishu-ai-knowledge│
│ -agent              │  │ collection          │  │ -base              │
│ 真实在跑的每日 Agent  │  │ Skill 卡片方法论     │  │ 知识管理飞轮模板     │
│ (已在飞书推送 4 天)   │  │                     │  │                    │
└────────────────────┘  └─────────────────────┘  └────────────────────┘
            │                        │                        │
            └────────────────────────┼────────────────────────┘
                                     │
                       ┌─────────────▼──────────────┐
                       │  linctex-obsidian-vault    │
                       │  (我所有思考的源头)            │
                       │  Style3D 实习复盘 / STAR 产出 │
                       │  Skill 分类体系 / 项目复盘     │
                       └────────────────────────────┘
```

**6 个项目不是 6 个独立作品,是"沉淀 → 落地 → 评测 → 复盘 → 再沉淀"的飞轮。** 面试官如果只看其中一个,会以为是 demo;但连起来看,是一套完整的 Agent 工程世界观。

---

## 现在在跑的东西(不是 demo)

| 项目 | 状态 | 实际证据 |
|------|------|---------|
| 飞书每日 AI 资讯 Agent | ✅ 在跑 | 7/27 - 7/30 连续 4 天推送,每天 9:00 自动出 |
| Huannessbot(手机 Agent 控制台) | ✅ 在跑 | 腾讯云 VPS + opencode + DeepSeek + systemd 24/7 |
| Style3D 实习沉淀的 Skill 体系 | ✅ 已沉淀 | 20 个 Skill 卡片 + 6 层能力地图(脱敏在 hermes-skills-collection) |
| Style3D 评测工具 | ✅ 在跑 | 60 轮上线前回归测试,0 事故 0 fallback 0 prompt 泄漏 |

**我倾向做"在跑的东西",而不是"写得漂亮但没人用的 demo"。**

---

## 我的下一步

- [ ] 把 Style3D 的 6 层评测框架开源成可被其他垂直行业复用的通用版本
- [ ] 把 Huannessbot 从个人 Agent 控制台演进成「服装行业 Agent 操盘台」的雏形
- [ ] 写「**垂直行业 Agent 落地周记**」—— 每周复盘一个"Agent 在企业里卡在哪"的真实问题

如果你在招"懂视觉 + 懂 Agent + 懂行业"的跨界产品工程师,或者正在做服装/零售/电商场景的 AI 落地,我想聊聊。

---

## 联系方式

- 📧 [17789651909@163.com](mailto:17789651909@163.com)
- 🌐 [Blog · huanhuan.ai](http://101.35.254.22/)
- 📱 +86 17789651909
- 💼 [LinkedIn](https://www.linkedin.com/) · [X/Twitter](https://x.com/) · [即刻](https://okjk.co/)

---

<details>
<summary>📄 完整简历</summary>

**廖乃环** · 浙江水利水电学院 · 数字媒体技术 · 2027 届

**实习经历**
- Style3D(凌迪科技) · AI Agent 产品实习生 · 杭州 · 2026.03 - 2026.07
  - 搭建 Style-Claw 推款 Agent 多阶段工作流,修复 4 项 P0 架构缺陷(会话串线/PPT 跨会话串用/记忆身份硬编码/检索确认模型)
  - 设计 6 维度 Agent 评测标准 + 40 条人工黄金集 + 0-5 分 Rubric + Blocker 门禁,搭建 Python 自动评测工具
  - 将一次完整测试从 1-2 天 → 几分钟,60 轮上线前回归测试 0 事故 0 fallback 0 prompt 泄漏
  - 调研 20 家服装企业 388 个字段 / 13,583 条枚举词,产出 32 字段标准字典 v2.1
  - 梳理 20+ 个 AI 技能卡片的能力边界,设计 6 层 Skill 体系能力地图
- 小影科技(AICatch) · AIGC 内容实习生 · 杭州 · 2025.06 - 2025.10
  - 30+ 个 AI 视频模板全流程交付(创意→Prompt→测试→上线),日均 2-3 个可商用模板

**认证** · 阿里云 ACA 大模型工程师认证

**在校经历** · 48h Game Jam 像素 RPG 主程序(获完美世界线下展示) · 墙绘实践团发起人 · 「视觉悦动」社团社长

</details>
