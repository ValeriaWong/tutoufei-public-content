# 95 条 AGENTS.md 教程的共性与可吸取之处

日期：2026-11-25｜底本：`agentsmd-tutorials-sweep-20261125.md`（95 条，13 平台）。本文件只写从 95 条里数出来的共性，不复述清单。

## 一、共性：12 条

1. **越短越好是最大共识。** 30–50 行（Medium kenek）、50–80 行路由器模式（SergiuSavva，引 GitHub 2500 仓库分析）、30 行规则（Qiita akira_papa_AI）、150 行上限（GitHub 2500 分析）、60 行以内（YouTube 小企业例子）、<100 行（西语 betterclaw）。太长怎么办的共识也是拆：拆成用到才读的规则文件（B 站 Skill 03）、渐进披露、宁要指针不要复制（Medium Kushal Banda）、瘦身做索引（Substack Lobo）。
2. **只写 agent 推断不出来的东西。** "only what the agent cannot infer"（kenek）、只编码不可发现的知识（GitHub dossier）、Codex 指南第 5 条只放非显而易见的约定（X Tekon Burns）、每条规则都要过 inclusion test（skale）。
3. **规则要可验证、可检查。** "specific enough to check"（B 站 Codex 22）、可验证的完成标准（德语 Blake Crosley）、testable rules（Substack WebAfterAI）、checkable instructions（dev.to johnnylemonny）、quick verification test（西语 reunified）。
4. **模板＋实例是标配格式。** 几乎每篇都给 starter template（最小版＋完整版），很多给好坏对照（jerdaw gist、bswen、Zenn babushkai 150 行模板＋Good/Bad、Addy Osmani 交互式模板生成器）。
5. **/init 先出草稿，人再手工改。** Net Ninja、Patrick Blade、Adnaan Khan、B 站 Codex 攻略、Hwee-Boon Yar，都是这个工作流。
6. **分层文件：全局／项目／子目录。** 到处都是（YouTube、Hwee-Boon、Addy Osmani、韩语 Easton 三层）。一句话版本："不是手册，是路由层"（WebAfterAI）——好规则文件是个索引，不是说明书。
7. **规则是吃亏长出来的，不是凭空写的。** Addy Osmani 六条（"no rule added unless something broke"）、Michaela Minds 三步从错误中生长、Elie Steinbock 每次审稿纠正加一行、GitHub dossier 事后捕捉、Dimeloper 规则成熟度。
8. **每条规则后面跟理由。** rulestack（Reason:）、akira_papa_AI（why-attached）、laurilllll（不可违反的规则要讲理由）。
9. **写什么、删什么都讲。** laurilllll（什么不要写）、skale（omit）、B 站 Skill 03（什么时候删没用的规则）、CodeNow 12（删掉只说"小心"的含糊规则）。
10. **固定栏目共识。** 命令（搭建／构建／测试）、代码风格、架构／目录、边界（别碰）、测试验证、Git/PR、完成定义。Addy Osmani 和 Matt Nigh 都是六个核心区。
11. **一份文件，所有工具都能读。** 可移植性（rulestack、tskamath、haboshi 单一事实来源、B 站"跨 AI 编程工具通用"）。
12. **受众全是程序员。** 只有 Chad Skelton（Codex for Non-Coders）和 Rubén Sbarsky（西语四步不用编程）沾了非程序员的边。没有一篇写给法律人；没有一篇是"审"而不是"写"；没有一篇拿真实文件做修改前后对照。

## 二、可以吸取的：7 条

1. **"越短越好"已经是全球共识——我们的 S6–S8 站在共识这边，但我们给了别人没有的东西：删除的顺序＋责任测试**（"这条删了，出事谁负责？"）。这是差异点，后续内容里值得点出来。
2. **"规则要可验证"所有人都在说，几乎没人演示。我们的双写者探针（后写的赢）就是一次现场验证，是 95 条里最像"证据"的东西。保持它突出。**
3. **"规则是吃亏长出来的"——我们的稿子没点这句。** 下一期（或简介／置顶评论）可以补：每条规则都得是吃过亏才写进去的，没吃过亏的别写。这是 Addy Osmani 那六条里最硬的一条。
4. **"不是手册，是路由层"（WebAfterAI）——表达很准，可以借来用在后续稿子里。**
5. **模板＋实例是标配——我们的视频给的是方法，没给模板。自然的下一步：一份"律师版 AGENTS.md 最小模板"当后续内容**（公众号文章或下一期视频）。饭米粒那篇（六节骨架＋12 套场景模板＋可直接粘贴的文件）是中文世界最接近这个格式的样板。
6. **定位缺口：没有法律人角度、没有"审"的角度、没有真实修改案例——我们的位置没人占。** 中文视频号上 AGENTS.md 内容几乎空白，B 站也全是 Codex 课，先发优势在我们这边。
7. **别学的：95 条里绝大多数是"写什么"的清单体；我们的路子是"怎么审"的演示体，别被清单体带回去。**

## 三、局限

- 播放量、阅读量基本核实不了（只有 2 条有数）；很多日期 unknown；小红书 0 条可验证（登录墙，需站内搜）。
- 本分析只针对"教人写 AGENTS.md"的 95 条；只提 AGENTS.md 一嘴的教程不在内。
