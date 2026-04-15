# McKinsey Editor Skill for OpenClaw

[English](#english) | [简体中文](#简体中文)

---

<a name="english"></a>
## 🇬🇧 English

**McKinsey Editor** is a structured writing flow skill designed for crafting in-depth, long-form articles. Based on the *Pyramid Principle*, *MECE Principle*, and *SCQA Framework*, this skill transforms the LLM into a senior McKinsey content editor. Through a progressive, multi-round interactive process, it helps users turn vague inspirations and scattered topics into highly logical, insightful, and high-quality long-form articles.

### 🌟 Core Philosophy
1. **Hypothesis-Driven**: Avoid aimless information listing. Propose a core hypothesis first, then seek compelling evidence to support it.
2. **MECE Principle (Mutually Exclusive, Collectively Exhaustive)**: When breaking down arguments, ensure analytical dimensions do not overlap and have no omissions, building a rigorous logical network.
3. **Pyramid Structure**: Conclusion first, top-down structure, grouped logically, and progressively detailed.

### ⚙️ Workflow
This skill strictly prohibits the LLM from "spitting out all content at once". Instead, it forces the process into the following interactive steps, each requiring user confirmation:
* **Step 0: Initiation & Greeting**: Trigger the workflow and confirm the user's [Topic Direction].
* **Step 1: SCQA Framing**: Build the **S**ituation - **C**omplication - **Q**uestion - **A**nswer framework to extract the core problem, and confirm with the user.
* **Step 2: Logic Tree & MECE**: Build an Issue Tree based on the core viewpoint. Break it down into 3-5 key drivers using MECE, and align with the user on arguments and cases.
* **Step 3: Analysis & Synthesis**: Deeply expand each key driver with explanations, case evidence, and actionable advice. Present a detailed outline for user confirmation.
* **Step 4: Final Output**: Synthesize all confirmed content into a structured, insightful long-form article (including a catchy title, SCQA intro, subheaded body, and summary/next steps).
* **Step 5: Universal Media Formatting**: After the final text is confirmed, automatically format the article using strictly inline CSS for maximum cross-platform compatibility (WeChat, Zhihu, Medium, etc.). Apply the Tech Blue theme, mobile-friendly micro-paragraphs, and generate a `.html` file saved directly to the workspace for the user to copy and paste into any rich-text editor.

### 🚀 How to Use
1. Install or copy the `SKILL.md` from this project into your OpenClaw `skills/` directory (e.g., `~/.openclaw/skills/mckinsey-editor/SKILL.md`).
2. Call the skill directly in the OpenClaw chat interface, or trigger it with prompts like:
   * *"Help me draft an in-depth article on the topic of..."*
   * *"I have a topic about X, help me write an article."*
3. Follow the AI assistant's guidance step by step to complete the SCQA framing, logic tree breakdown, and outline expansion. Enjoy your high-quality article!

---

<a name="简体中文"></a>
## 🇨🇳 简体中文

**McKinsey Editor (麦肯锡内容主编)** 是一款专为深度长文写作打造的结构化写作流技能 (Skill)。本技能基于《金字塔原理》、MECE 原则和 SCQA 框架，引导大模型转变为一位资深的麦肯锡内容主编，通过多轮渐进式的交互，帮助用户把模糊的灵感和零散的选题转化为逻辑严密、洞察深刻的高质量长文。

### 🌟 核心理念
1. **以假设为导向**: 摒弃漫无目的地罗列信息，主张先提出核心观点，再寻找有力证据支撑。
2. **MECE 原则 (相互独立，完全穷尽)**: 在拆解论点时，确保分析维度不重叠、无遗漏，构建严密的逻辑网。
3. **金字塔结构**: 结论先行，以上统下，归类分组，逻辑递进。

### ⚙️ 工作流解析
该技能严格禁止大语言模型“一次性吐出所有内容”，而是强制将其拆分为以下交互式步骤，每一步都需要用户的确认和参与：
* **Step 0: 启动与问候**: 触发工作流，确认用户的【选题方向】。
* **Step 1: 界定问题 (SCQA Framing)**: 构建 **S** (情景) - **C** (冲突) - **Q** (疑问) - **A** (核心假设) 框架，提炼文章要解决的核心问题，并与用户确认。
* **Step 2: 结构化拆解 (Logic Tree & MECE)**: 基于核心观点构建关键议题树 (Issue Tree)，使用 MECE 原则拆解出 3-5 个一级分论点，并与用户对齐论证方向和案例。
* **Step 3: 深化与验证 (Analysis & Synthesis)**: 对每个分论点进行深度扩展，补充深度解释、案例证据和对策建议，形成完整详实的大纲供用户二次确认。
* **Step 4: 金字塔输出 (Final Output)**: 将所有确认无误的内容整合成篇，输出结构清晰（包含吸引人的标题、SCQA 序言、小标题正文及总结建议）的深度长文，并等待最终确认。
* **Step 5: 全平台自媒体排版 (Universal Media Formatting)**: 在文本内容最终确认后，自动采用跨平台兼容的高级排版规范（科技蓝主题、严格内联样式、移动端极简段落）将文章转化为排版精美的 HTML 页面，并直接保存至工作区，方便用户一键复制粘贴至任何自媒体平台（微信公众号、知乎、头条等）的富文本编辑器中。

### 🚀 如何使用
1. 将本项目的 `SKILL.md` 安装或复制到您的 OpenClaw 的 `skills/` 目录中（例如 `~/.openclaw/skills/mckinsey-editor/SKILL.md`）。
2. 在 OpenClaw 聊天界面中直接呼叫该技能，或者输入类似指令触发：
   * *"帮我构思一篇深度文章，选题是..."*
   * *"我有一个关于...的选题，帮我写一篇文章"*
3. 按照 AI 助手的引导，一步步完成 SCQA 确认、逻辑树拆解和大纲扩展，最终收获高质量长文！

---
🤝 **Contributing / 贡献与反馈**: Welcome to submit Issues and Pull Requests to help optimize this workflow! / 欢迎提交 Issue 和 Pull Request，与我们一起优化这个写作工作流！
