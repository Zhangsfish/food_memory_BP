# 证据登记｜v0.1

核验日期：2026-09-25。优先官方产品说明、官方文档和公司公告。产品方声称的能力不是独立效果评测；以下来源不证明 Food Memory 存在付费需求或护城河。

## E01｜当前原型，不是市场验证

通过授权 GitHub 工具读取：

- [原库 main 版本 e6a2f52](https://github.com/Zhangsfish/food_memory/tree/e6a2f52ee5592006b324d246bd8193c9300462a4)
- [catalog.json](https://github.com/Zhangsfish/food_memory/blob/e6a2f52ee5592006b324d246bd8193c9300462a4/indexes/catalog.json)：2 条经历、1 位作者 github:Zhangsfish、1 个地区 CN/北京。
- [AGENTS.md](https://github.com/Zhangsfish/food_memory/blob/e6a2f52ee5592006b324d246bd8193c9300462a4/AGENTS.md)：原库保存经历，AI 负责推断，地图负责现况；没有人工维护的作者画像。
- [CONTRIBUTING.md](https://github.com/Zhangsfish/food_memory/blob/e6a2f52ee5592006b324d246bd8193c9300462a4/CONTRIBUTING.md)：广泛开放贡献前仍需选定数据/内容许可。

支持：已有个人原型和多人贡献的文件接口。
不支持：已完成第三方贡献测试、用户留存、付费、推荐效果、实名能力或全球覆盖。本轮没有对现有 CI 和安全措施做全面审计，不能把历史“检查通过”当作所有安全边界已闭合。

## E02｜公开 GitHub 的读取与复制边界

来源：[GitHub Docs — Forks](https://docs.github.com/en/pull-requests/reference/forks)

支持：公共仓库可被 fork。因此公开原始数据层不能作为“每天写才可读”的强制访问控制层。
不支持：所有下游复制行为都依法得到任意商业复用授权；这属于许可问题，见 E03。

## E03｜可见性不等于开放许可

来源：[GitHub Docs — Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)

支持：GitHub 说明公共仓库在其服务条款下可被查看和 fork；未设许可不等于授予一般的开源使用权；改为私有不消灭他人已存在的 fork/本地副本。

业务含义：不能先按“完全开放共建”吸引贡献，再默认把全部内容改成独家收费资产。应分别明确代码许可、经历文本/图片许可、是否授权商业服务与再分发、隐私处理和未来收益规则。正式条款需按业务和适用法审查，本文件不是法律意见。

## E04｜Beli 已有以人为中心的饮食记录与匹配

来源：
- [Beli 官网](https://beliapp.com/)
- [Beli 官方 App Store 产品说明](https://apps.apple.com/py/app/beli/id1478375386)

支持：官方产品说明包含记录餐厅、朋友吃饭动态、个性化建议、Taste Profile 和朋友之间的 Match Score。
不支持：这些功能已解决所有用户痛点；也不证明其算法适合中国校园场景。

业务含义：“口味画像 + 参考朋友”不是空白赛道。需证明跨 AI 的可携带性、原话来源、具体决策效果或本地采集效率的增量。

## E05｜Beli 已有创作者付费指南制度

来源：
- [Paid Guides Terms — Creator](https://beliapp.com/paid-guides-terms-creator)，页面注明生效日 2025-12-23。
- [Creator/Guides Subscription Support](https://beliapp.com/guide-subscriptions)

支持：官方条款允许创作者提供付费指南订阅，并规定 Creator Share 等结算事项。
不支持：收入规模、创作者平均盈利、所有创作者都成功，或这就是 Food Memory 适用的分成方案。

业务含义：“给食评创作者订阅付费”也不是无人做。具体费率不是本轮结论。

## E06｜Yelp 已在将真实评论交给 AI 理解

来源：[Yelp 官方 2026-04-21 产品公告](https://www.yelp-ir.com/news/press-releases/news-release-details/2026/Yelp-Launches-the-New-Yelp-Assistant-Transforming-Local-Discovery-from-Search-to-Answers-and-Actions/default.aspx)

支持：Yelp 宣布新助手覆盖其各类别，利用评论、照片和商家信息回答具体请求，并展示用户内容支持建议；同时连接订餐/预约等动作。
不支持：其结果一定可信或一定优于本项目；公告属于公司对产品能力的描述。

业务含义：不能声称“旧平台只有五星、不会读原话”。真实比较应以同一地区同类问题的效果为准。

## E07｜Google Maps 已有对话与个性化发现

来源：[Google 官方 2026-03-12 — How we’re reimagining Maps with Gemini](https://blog.google/products-and-platforms/products/maps/ask-maps-immersive-navigation/)

支持：宣布 Ask Maps，以对话查询地点，并利用已搜索/保存地点等信号个性化；该公告中的首发范围是美国和印度。
不支持：已在全部国家开放、适合中国校园的当前可用性、实际准确率。不能据此要求校园受试者使用当地不可用的基线。

业务含义：对手能把地点、评论、个性化与行动接起来，竞争不是“懂 AI 的小团队 vs 完全不会 AI 的老平台”。

## E08｜本地内容向 AI 生态授权已有供给方案例

来源：[Yelp 官方 2026-02-12 财报公告](https://www.yelp-press.com/press-releases/press-release-details/2026/Yelp-Delivers-Record-Net-Revenue-in-2025-Accelerating-Investment-in-AI-Transformation/default.aspx)

支持：Yelp 公告签署与 OpenAI 的协议，并在其他收入增长来源中提到 data licensing。
不支持：该协议价格、单条评论价值、本项目能拿到同样客户或报价；不据此给原型估值。

业务含义：AI 数据服务是存在的交易方向，但已有成熟供给者。潜在买方要买的不是“我们用了 GitHub”，而是增量效用、授权、更新、质量与服务。

## E09｜ChatGPT 可以读取授权仓库，但不要泛化单次体验

来源：[OpenAI Help — Connecting GitHub to ChatGPT](https://help.openai.com/en/articles/11145903-connecting-github-to-chatgpt)

支持：在受支持的套餐与产品界面中，读取被授权的仓库内容；可用性与产品界面有关。
不支持：任何同学任意账号都能零配置读写本仓库。读取、授权和写入能力需分别实测。

业务含义：当前作者的演示不是普通学生开户/接入成本的证据。必须实测国内候选入口，不能让用户为记饭学习 Git。

## E10｜WorkBuddy 是候选入口，不是已完成的接入

来源：[腾讯 WorkBuddy 官方简介](https://www.workbuddy.cn/docs/workbuddy/Overview)

支持：自然语言任务、任务执行与授权的本地文件操作等产品能力。
不支持：已连接 Food Memory、能替任意普通贡献者成功提交、稳定性和用户成本已达标。

业务含义：可以安排接入实验，不能写成已支持的产品集成。

## E11｜MCP 是接口，不是人或数据真实性

来源：[Model Context Protocol 官方简介](https://modelcontextprotocol.io/docs/getting-started/intro)

支持：MCP 用于连接 AI 应用与外部数据、工具和工作流。

业务含义：“人当 MCP”是有启发的比喻，但更准确是人产生物理世界的第一手记录，数据库保存，API/MCP 暴露查询能力。建立 MCP 不自动创造数据、用户、可信度或收入。

## E12｜反女巫系统仍依赖证据、模型与外部验证

来源：
- [Human Passport 官方概览](https://docs.human.tech/passport)
- [Available models and recommended scores](https://docs.passport.human.tech/building-with-passport/models/available-models)
- [Individual Verifications API](https://docs.passport.human.tech/building-with-passport/individual-verifications/api-reference)

支持：采用历史凭据、行为模型或身份验证；部分模型输出风险分，并在交易数据不足时返回特殊状态；并非只连接钱包就等于证明唯一真人。
不支持：一人一号绝对保证、从未误判、真实人不会代发广告、实际用餐发生过，或已有独立评估证明适合本项目。

业务含义：早期先用自愿熟人邀请、限速、抽查与利益披露，不把 Web3 当真实性答案。未来只有当威胁模型与规模明确才评估新增验证层。

## E13｜链上记录不会自动验证线下发生过什么

来源：[Ethereum 官方开发者文档 — Oracles](https://ethereum.org/developers/docs/oracles/)

支持：链外事实需要外部输入/预言机；链本身不直接知道谁实际吃过一顿饭。

业务含义：可验证签名/哈希证明的是特定声明与版本，不是菜好吃、作者诚实或毫无商业关系。

## 仍缺的证据

本轮没有用户访谈、校园课程合作证明、真实竞品对照、贡献留存、支付行为或反作弊性能测试。

下一轮检索/实验优先级：候选同学的真实选餐流程；可接入入口；校园局部覆盖；画像的增量效果；提供商的真实数据需求。全国市场规模和完整融资估值排在这些之后。
