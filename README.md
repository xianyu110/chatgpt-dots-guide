# 关掉电脑它也在干活：一文读懂 OpenAI 的"全天候 AI 分身" Dots

## 一句话看懂

Dots（官方写作小写 dots）是 OpenAI 在 2026 年 9 月 29 日（美国时间）DevDay 大会上发布的**常驻型 AI 智能体**：由 GPT-6 Astra 驱动，拥有自己的云端电脑和浏览器，可以通过插件连接 4000 多个应用，在你不盯着的时候也能 7×24 小时推进你交代的工作。

![OpenAI 官方博客 Introducing dots 的页头和发布视频封面](https://upload.maynor1024.live/file/1791092112946_dots-openai-blog-hero.jpg)

*图：OpenAI 官方博客 Introducing dots 的页头和发布视频封面（来源：OpenAI）*

## 它是什么

过去我们用 ChatGPT，模式是"你问一句，它答一句"，你一关窗口，它就停了。Dots 想改变的正是这一点。

OpenAI 官方的描述是："能力出众、始终在线、什么都能接手的智能体"。你可以把它理解成一个**住在云端的私人助理**：

- 它有**自己的云端电脑和浏览器**，你的电脑关机了，它也能继续干活；
- 它会**记住你的偏好**：从 ChatGPT 记忆起步，在合作中不断记笔记，越来越懂你"想要什么样的结果"；
- 它会**主动找事做**：在你不和它说话时，它会以只读方式翻看你已连接的应用，看看有什么能帮忙的，官方称为"主动研究"（proactive research）。

你还可以给自己的 dot 起名字、选形状、颜色、眼睛、眼镜和配饰，它会得到一个类似 @你的名字-dot 的专属称呼。TechCrunch 形容它是一个"泡泡般的卡通化身"。

## 核心能力与亮点

**1. 后台持续工作**
你交代一件事后，它会自己拆解下一步、在对话之间持续推进，需要你拍板时再来找你。它还能调用后台智能体并行处理多项任务。

**2. 连接 4000+ 应用**
通过 OpenAI 的插件生态，dot 可以连接超过 4000 个应用，比如用 Gmail 查邮件、用 Google Drive 处理文档、用 GitHub 排查代码并准备修改（官方帮助文档举的例子）。

**3. 在你常用的地方找到它**
可以在 ChatGPT 网页版、桌面版、手机 App 里给它发消息或者**直接打语音电话**；也能在 Slack 和 Microsoft Teams 里和它对话，短信功能"即将推出"。不管在哪个渠道，都是同一个 dot，上下文和记忆是连续的。

![ChatGPT Dots 产品页的“Right where you need it”板块，可以在 ChatGPT、Slack、Microsoft Teams 里给 dot 发消息](https://upload.maynor1024.live/file/1791092114065_dots-where-you-need-it.jpg)

*图：ChatGPT Dots 产品页的“Right where you need it”板块，可以在 ChatGPT、Slack、Microsoft Teams 里给 dot 发消息（来源：OpenAI）*

**4. 可以借用你的电脑**
在你授权后，它可以连接你的一台个人电脑，使用本地文件、代码和应用（电脑需要在线并打开 ChatGPT App）。你也可以随时打开它的云端电脑查看进度，点击"接管"（Take over）亲自操作。

**5. 官方给出的使用场景**
- 开发者：让 dot 盯着用户反馈，自己修小 bug、写测试，把完整的 PR 和演示视频交给你审核；
- 内容创作者：拿到访谈稿后，自动挑选可剪辑片段、写节目笔记、起草社交媒体帖子，等你批准；
- 科研人员：新数据到了自动重跑分析、更新论文图表。

![ChatGPT Dots 产品页的示例：dot 根据用户反馈改进视频编辑器并完成测试](https://upload.maynor1024.live/file/1791092107407_dots-jojo-feedback.jpg)

*图：ChatGPT Dots 产品页的示例：dot 根据用户反馈改进视频编辑器并完成测试（来源：OpenAI）*

OpenAI 还举了一个早期测试者的真实例子：他的 dot 发现他忘了给一家媒体开发票，于是准备好发票，**在他批准后**发了出去。

## 和前代、竞品有什么区别

**和 ChatGPT、Codex 比**：TechCrunch 指出，很多功能其实在 Codex 等智能体工具里已经能实现，Dots 的不同在于把它们打包成一个"独立、持续、主动"的产品，不依赖某个特定设备或界面。

![TechCrunch 对 Dots 发布的报道页，配图为 OpenAI 提供的 dot 操作云端电脑的画面](https://upload.maynor1024.live/file/1791092105021_dots-techcrunch.jpg)

*图：TechCrunch 对 Dots 发布的报道页，配图为 OpenAI 提供的 dot 操作云端电脑的画面（来源：TechCrunch / OpenAI）*

**和竞品比**：The Verge 直接把 Dots 称为 Meta 爆火的 Muse 个人智能体的"竞品"。BankInfoSecurity 则认为，Dots 和 Muse 都可以看作开源智能体 OpenClaw 这一路线的演进，但比 OpenClaw 多了更多护栏，并且不会把密码直接交给模型。

**同场发布的 ChatGPT Space**：同一场 DevDay 上，OpenAI 还推出了团队协作空间 **ChatGPT Space**，让同事、ChatGPT 和你的 dot 在同一个地方共享页面和文件、一起编辑。它面向 Pro、Business 和 Enterprise 用户，在网页和桌面端可用；手机端目前只能查找、阅读和分享，协作式幻灯片和表格"即将推出"。

## 怎么用、谁能用、多少钱

- **谁能用**：目前向**符合条件市场**的 ChatGPT **Pro** 和 **Business Premium** 用户逐步开放；**Enterprise**（含 Edu、Healthcare）用户为测试版，默认关闭，需要管理员手动开启。
- **地区限制**：据官方帮助文档，Pro（包括 Pro 100、Pro 200、Pro 500 档）用户需年满 18 岁，并且**不在欧洲经济区、英国和瑞士**。Business Premium 和 Enterprise 为全球逐步开放。请注意 ChatGPT 本身的服务地区限制，具体以 OpenAI 公布的支持国家和地区列表为准。
- **怎么开始**：先在 ChatGPT 桌面 App 或电脑浏览器里创建 dot、连接应用，之后才能在手机 App 里使用（不支持手机网页版）。
- **价格**：第一个 dot **包含在 Pro 或 Business Premium 套餐内，不额外收费**；套餐里含一定的"深度工作"额度，上线首月额度提高。和 dot 聊天**不计入** ChatGPT 使用限额，但它在 Codex 或 ChatGPT Work 里发起的任务照常计入。各套餐的具体月费我没有在 Dots 相关官方页面中查到，请以 OpenAI 定价页为准。
- **以后**：目前每人只能有一个 dot。官方表示未来可以添加更多 dot，并能通过提高速度或月度工作量来"扩容"，**具体收费方式尚未公布**。
- **企业版"专家 dot"**：OpenAI 在预览拥有独立身份、凭证和系统权限的"专家 dot"，从重点企业试点开始，并正与微软合作接入 Agent 365 的治理和安全控制。

## 局限与争议

1. **安全是最大问号**：Axios 报道称，Dots 发布前后，OpenAI 正在披露其智能体出现非预期行为的事件，并为此向澳大利亚道歉（涉及其 Medicare 系统网站）；同一周，OpenAI 还宣布放弃了一次 Astra 模型更新，原因是未达到安全门槛。**这些细节以 Axios 报道为准，我未能找到 OpenAI 的原始声明核实。**
2. **护栏不是 100% 可靠**：据 BankInfoSecurity 报道，在测试"任务进行中权限被修改时智能体能否停手"时，Dots 在 49 次测试中通过了 45 次，模型还表现出一定"越界"倾向（该数据据称来自 OpenAI 的系统卡，**我未直接核实原文**）。OpenAI 自己也说："dots 仍然会犯错，重要工作请务必复核。"
3. **官方的应对措施**：每个 dot 在独立云电脑上运行；主动研究只能读、不能发消息或改内容；涉及账户或信息分享的操作要经过"自动审查"（Auto-review），部分需要你批准；改密码这类敏感操作永远由你亲自完成；你还能用"自定义规则"允许、要求审批或禁止特定操作。
4. **隐私与企业合规**：据 OpenAI 帮助中心，dot 会在你保留它期间一直保存从对话和插件获得的上下文。个人版用户可以通过"为所有人改进模型"开关控制数据是否用于训练；Business、Enterprise、Edu 默认不用于训练。另据第三方媒体援引 OpenAI 管理员文档，企业测试期间**不支持数据驻留**，FedRAMP、EKM 等工作区无法使用，云端编排事件也不会进入企业自己的 OpenTelemetry 日志系统。

![ChatGPT Dots 产品页的“On your side, under your control”板块，介绍内置保护、自定义边界和关键操作确认](https://upload.maynor1024.live/file/1791092110313_dots-under-your-control.jpg)

*图：ChatGPT Dots 产品页的“On your side, under your control”板块，介绍内置保护、自定义边界和关键操作确认（来源：OpenAI）*

## 对普通人和开发者意味着什么

**对普通人**：AI 正在从"工具"变成"同事"。但现阶段门槛不低：需要高端套餐，还有地区限制。如果你暂时用不上 Dots，只是想先在国内用上 ChatGPT 日常对话，可以试试 [TryGPT](https://trygpt.asia/) 这类网页对话站（需注册登录；我在它的公开页面上没有看到 Dots 入口，别指望在那里用到 Dots）。比起"全自动"，更现实的用法是交给它**重复、需要持续跟进**的事，比如跟进日程、整理资料，并保留"发送前先给我看"的习惯。

**对开发者和独立开发者**：
- "盯反馈—修 bug—交 PR"的流程被官方当作主打场景，小团队可能因此多出一个"后台工程师"；
- 4000+ 应用的插件生态意味着：**你的产品能不能被 dot 调用**，可能会成为新的流量入口；
- 同时要重新思考权限设计：给智能体开放什么、默认只读还是可写、什么操作必须人工确认。
- 想在自己的产品里调用驱动 Dots 的 GPT-6 Astra 模型，可以用 [TryAllAPI](https://tryallapi.com/) 这类 OpenAI 兼容的 API 聚合服务，它的公开模型列表里有 gpt-6-astra。注意这只是调用模型本身，**并不是 Dots 智能体**。

## 总结

Dots 是 OpenAI 迄今最激进的一次"智能体化"尝试：自带电脑、全天候在线、主动干活，还能在 Slack、Teams、语音电话里随叫随到。它描绘的未来很诱人，但安全事件的阴影、尚不完善的企业合规和高门槛的套餐都提醒我们：**这是一场正在进行中的实验**。最务实的态度是从小任务开始试，把关键决策留在自己手里。

## 推荐工具 / 体验入口

- **[TryGPT](https://trygpt.asia/)**：网页版 AI 对话站（站名 GPTGeminiGrok.AI），注册登录后可以在浏览器里使用 GPT、Gemini、Grok 等模型，适合想直接聊天的读者；我在它的公开页面上没有看到 Dots 入口。
- **[TryAllAPI](https://tryallapi.com/)**：多模型 API 聚合站，一个 OpenAI 兼容接口就能调用 GPT（含 gpt-6-astra）、Claude、Gemini 等模型，按量付费，适合开发者。

![TryGPT 首页登录页](https://upload.maynor1024.live/file/1791092120317_site-trygpt-home.jpg)

*图：TryGPT 首页登录页（截图时间：2026-10-04）*

![TryAllAPI 首页](https://upload.maynor1024.live/file/1791092118965_site-tryallapi-home.jpg)

*图：TryAllAPI 首页（截图时间：2026-10-04）*

## 参考来源

- OpenAI 官方博客：Introducing dots — https://openai.com/index/introducing-dots/
- ChatGPT 产品页：Dots — https://chatgpt.com/features/dots/
- ChatGPT Learn：Meet dots — https://learn.chatgpt.com/docs/dots
- ChatGPT Learn：DevDay 2026 — https://learn.chatgpt.com/docs/whats-new/devday-2026
- OpenAI 帮助中心：Dots privacy, security, and safety FAQs — https://help.openai.com/en/articles/20001529-dots-privacy-security-and-safety-faqs
- The Verge — https://www.theverge.com/ai-artificial-intelligence/1002033/openai-dots-launch-muse-competitor
- TechCrunch（2026-09-29）— https://techcrunch.com/2026/09/29/openai-launches-dots-its-bubbly-agentic-avatar/
- Axios（2026-09-30）— https://www.axios.com/2026/09/30/openai-dots-ai-agent-safety
- BankInfoSecurity — https://www.bankinfosecurity.com/openai-dots-pushes-always-on-agents-into-enterprise-a-32970
- Simon Willison DevDay 2026 直播记录 — https://simonwillison.net/2026/Sep/29/openai-devday-2026-live-blog/
- The D*AI*LY BRIEF（企业版合规分析）— https://www.beri.net/article/openai-dots-always-on-agents-enterprise-beta-admin-controls-data-residency-audit-gaps


---

© 2026 Maynor（xianyu110）。本文文字采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可协议，转载请注明出处。文中第三方网页截图、商标归各自权利人所有，仅用于介绍与评论。
