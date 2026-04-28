---
layout: default
title: "Horizon Summary: 2026-04-28 (ZH)"
date: 2026-04-28
lang: zh
---

> From 12 items, 8 important content pieces were selected

---

1. [微软与 OpenAI 终止独家协议，OpenAI 可自由使用其他云服务](#item-1) ⭐️ 10.0/10
2. [Talkie：一个基于 1930 年代文本训练的 130 亿参数语言模型](#item-2) ⭐️ 8.0/10
3. [微软发布开源语音模型 VibeVoice](#item-3) ⭐️ 8.0/10
4. [微软与 OpenAI 的 AGI 条款正式移除](#item-4) ⭐️ 8.0/10
5. [多伦多短信轰炸机案：三名男子被捕](#item-5) ⭐️ 7.0/10
6. [网站揭示颜色感知的个体差异](#item-6) ⭐️ 7.0/10
7. [凝视墙壁的人：被遗忘的放空艺术](#item-7) ⭐️ 7.0/10
8. [Easyduino：开源 KiCad 开发板模板](#item-8) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [微软与 OpenAI 终止独家协议，OpenAI 可自由使用其他云服务](https://www.bloomberg.com/news/articles/2026-04-27/microsoft-to-stop-sharing-revenue-with-main-ai-partner-openai) ⭐️ 10.0/10

这标志着 AI 产业的重大重新调整，OpenAI 不再绑定 Azure，可能改变云提供商之间的力量平衡，并使 OpenAI 能够使用谷歌 TPU 等更多样化的硬件。 原协议赋予微软独家托管 OpenAI 模型及收入分成权利，但 OpenAI 的快速增长和对更多算力的需求可能促使了这一变更。

hackernews · helsinkiandrew · Apr 27, 13:22

**背景**: 微软与 OpenAI 此前有数十亿美元的合作伙伴关系，微软通过 Azure 独家提供云计算服务，并收取 OpenAI 一定比例的收入。该协议帮助 OpenAI 扩展规模，但限制了其基础设施选择。排他性终止后，OpenAI 可以谈判更优条款，并可能使用谷歌 TPU 或 AWS 的自研芯片。

**社区讨论**: 评论者们讨论了这一变化的影响：有人认为谷歌因其 TPU 优势成为最大赢家，也有人认为此举表明 OpenAI 资金紧张。一名前重组律师表示这种重组是“缺钱时的挣扎”。有用户指出，尽管看似热门，顶级 AI 模型仍不可靠，代码输出需要仔细审查。

**标签**: `#Microsoft`, `#OpenAI`, `#AI`, `#cloud computing`, `#partnership`

---

<a id="item-2"></a>
## [Talkie：一个基于 1930 年代文本训练的 130 亿参数语言模型](https://talkie-lm.com/introducing-talkie) ⭐️ 8.0/10

研究人员发布了 Talkie，这是一个 130 亿参数的语言模型，专门使用 1930 年之前的 2600 亿个英文语料进行训练，捕捉了 1930 年代的语言和知识。 该项目提供了独特的历史视角，有助于研究过去的语言、信仰和世界观，并在历史研究和教育领域开辟了新颖的人工智能应用。 Hugging Face 上有两个版本：基础模型（53.1 GB）和指令微调版本（26.6 GB）。该模型在回忆 1930 年以前的事实方面表现良好，但在大萧条等事件上表现不佳，表明其训练数据截止日期。

hackernews · jekude · Apr 27, 21:55

**背景**: 像 GPT-3 这样的大型语言模型通常是在近几十年的多样化互联网文本上训练的。Talkie 则不同，它使用精心筛选的仅包含历史文本的语料库，旨在重现如果该技术在 1930 年可用时本应存在的语言模型。

**社区讨论**: 评论显示了不同的反响：一些人认为历史输出很有趣，而另一些人则指出在技术和政治方面的不准确，暗示模型依赖 1900 年以前的信息。Alec Radford 的参与增加了可信度。

**标签**: `#language model`, `#vintage data`, `#historical AI`, `#machine learning`, `#NLP`

---

<a id="item-3"></a>
## [微软发布开源语音模型 VibeVoice](https://simonwillison.net/2026/Apr/27/vibevoice/#atom-everything) ⭐️ 8.0/10

微软于 2026 年 1 月 21 日发布了 VibeVoice，这是一个采用 MIT 许可证、类似 Whisper 的音频模型，用于语音转文本并内置说话人分离功能。该模型可转录长达一小时的音频，并输出带有说话人标签的 JSON。 VibeVoice 将语音转文本与说话人分离集成于一个开源模型中，减少了独立管线的需求。其 MIT 许可证鼓励在播客转录和会议分析等应用中广泛采用。 VibeVoice 每次运行最多可处理 59 分钟音频，默认最大 token 数为 8192（约 25 分钟），需要约 30–60GB 内存。在 M5 Max MacBook Pro 上，提示处理速度约 50 tokens/秒，生成速度约 38 tokens/秒。

rss · Simon Willison · Apr 27, 23:46

**背景**: 说话人分离是将音频流按说话人身份分割成段的任务，回答'谁在什么时候说话'。Whisper 风格的模型是基于 Transformer 的端到端语音识别系统，最初由 OpenAI 的 Whisper 推广。VibeVoice 通过将分离直接集成到模型中来扩展这一概念，而传统方法使用独立系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speaker_diarisation">Speaker diarisation</a></li>
<li><a href="https://ml-explore.github.io/mlx/build/html/index.html">MLX — MLX 0.31.1 documentation</a></li>

</ul>
</details>

**标签**: `#speech-to-text`, `#AI`, `#Microsoft`, `#open-source`, `#machine learning`

---

<a id="item-4"></a>
## [微软与 OpenAI 的 AGI 条款正式移除](https://simonwillison.net/2026/Apr/27/now-deceased-agi-clause/#atom-everything) ⭐️ 8.0/10

2026 年 4 月 27 日，微软与 OpenAI 宣布修订合作协定，移除了 AGI 条款。该条款原规定一旦实现 AGI，微软的商业 IP 权利将失效。 这一移除重塑了最具影响力的 AI 合作关系之一，影响知识产权、独占权及围绕 AGI 开发的激励机制。 该条款最初将 AGI 定义为能为早期投资者创造 1000 亿美元利润的系统；后来改为由独立专家组验证。移除后，微软失去独占权，但 IP 权利保留至 2030 年或 AGI 声明中较早者。

rss · Simon Willison · Apr 27, 18:38

**背景**: 该条款是 2019 年微软与 OpenAI 合作的一部分，旨在限制微软在 OpenAI 实现 AGI 后的控制权。AGI（通用人工智能）指在几乎所有认知任务上达到或超越人类能力的假设性 AI 系统。AGI 的确切定义一直是争议点，条款从简单里程碑演变为基于利润的指标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/918981/openai-microsoft-renegotiate-contract">Microsoft and OpenAI’s famed AGI agreement is dead</a></li>
<li><a href="https://arstechnica.com/ai/2026/04/no-longer-exclusive-microsoft-agrees-to-let-openai-see-other-cloud-providers/">OpenAI ends its exclusive partnership with Microsoft - Ars ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Artificial_general_intelligence">Artificial general intelligence - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AGI`, `#OpenAI`, `#Microsoft`, `#AI governance`, `#IP rights`

---

<a id="item-5"></a>
## [多伦多短信轰炸机案：三名男子被捕](https://www.tps.ca/media-centre/stories/unprecedented-sms-blaster-arrests/) ⭐️ 7.0/10

三名男子在多伦多因使用短信轰炸机发送钓鱼短信被捕，当局称此案在加拿大前所未有。 此案凸显了电信网络中允许短信伪造的漏洞，并强调了通过移动设备发送的钓鱼诈骗日益增长的威胁。 这些短信轰炸机设备可能干扰蜂窝网络连接，甚至阻止拨打 911，嫌疑人据称劫持了数千部手机发送垃圾短信。

hackernews · gnabgib · Apr 27, 20:44

**背景**: 短信轰炸机是模仿基站的便携式设备，利用 SS7 协议漏洞在没有运营商验证的情况下发送虚假短信。这种技术绕过了常规垃圾邮件过滤器，并允许诈骗者伪造发送者 ID。SS7 漏洞已存在多年，但在许多网络中仍未修复。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gizmodo.com/canadian-police-arrest-three-men-behind-sms-blaster-scam-that-allegedly-hijacked-thousands-of-phones-2000751386">Canadian Police Arrest Three Men Behind SMS Blaster Scam That ...</a></li>
<li><a href="https://www.techradar.com/computing/cyber-security/new-sms-blaster-text-scams-are-on-the-rise-security-experts-warn-stay-safe-by-changing-this-one-phone-setting">New ‘SMS blaster’ text scams are on the rise, security ...</a></li>
<li><a href="https://dailysecurityreview.com/cyber-security/application-security/ss7-alarm-tcap-tag-exploit-lets-attackers-intercept-sms-and-track-users/">SS7 Alarm: TCAP Tag Exploit Lets Attackers Intercept SMS and ...</a></li>

</ul>
</details>

**社区讨论**: 新闻评论反应不一：有人质疑设备的所谓新颖性，指出执法部门也在使用类似的技术（如 stingray）。也有人讨论 SS7 漏洞如何使此类攻击成为可能，并与巴西的普遍短信垃圾情况进行比较，那里许多用户仅使用 WhatsApp。

**标签**: `#cybersecurity`, `#SMS spam`, `#phishing`, `#telecom security`, `#law enforcement`

---

<a id="item-6"></a>
## [网站揭示颜色感知的个体差异](https://ismy.blue/) ⭐️ 7.0/10

一个新的互动网站“我的蓝色是你的蓝色吗？”要求用户将颜色分类为蓝色或绿色，从而揭示每个人区分这两种色调的边界。 该实验突显了颜色感知是主观的，并且在个体和文化之间存在显著差异，挑战了人们以相同方式看到颜色的假设。 该网站呈现从明显蓝色到明显绿色的颜色，用户必须为每种颜色点击“蓝色”或“绿色”；结果显示用户个人边界相对于人口平均值的偏移。

hackernews · theogravity · Apr 27, 20:24

**背景**: 颜色感知受生物学和语言两方面影响；不同文化对颜色的命名和分类方式不同，例如日语中的“ao”同时涵盖蓝色和绿色。颜色边界变化的现像是认知科学和语言学中的著名话题。

**社区讨论**: 评论者分享了与他人争论颜色分类的个人轶事，一些人认为蓝色和绿色的二选一无法涵盖青绿色或蓝绿色等中间色而感到沮丧。还提到了文化差异，例如日本的“蓝色”交通灯。

**标签**: `#color perception`, `#cognitive science`, `#linguistics`, `#interactive experiment`, `#pop science`

---

<a id="item-7"></a>
## [凝视墙壁的人：被遗忘的放空艺术](https://www.alexselimov.com/posts/men_who_stare_at_walls/) ⭐️ 7.0/10

这篇文章探讨了在没有数字干扰的情况下让思绪漫游这一被忽视的重要性，并创造了术语 'disattention' 来描述这些非结构化的精神休息时刻。 在智能手机饱和的世界中，持续的数字参与剥夺了人们能够促进创造力、问题解决和情绪处理的关键精神休息；重新获得放空状态可以改善心理健康和生产力。 文章将放空与冥想进行了对比，指出冥想是结构化的，而放空是自发且非结构化的；它强调了用刷屏填补每一刻空闲时间的本能是一个难以戒除的习惯。

hackernews · aselimov3 · Apr 27, 11:08

**背景**: 放空指的是让思绪自然漂移而不专注于特定任务的状态，经常发生在凝视墙壁或开车等日常活动中。在现代注意力经济中，智能手机不断争夺注意力，消除了这些允许潜意识处理的有价值的精神暂停。

**社区讨论**: 评论者们强烈赞同文章，分享了个人关于智能手机夺走放空时刻的经历。一位用户指出，智能手机不仅偷走注意力，还偷走了放空本身；其他人将其比作冥想，并强调抵制用刷屏填补空闲时间的冲动是多么困难。

**标签**: `#attention`, `#mindfulness`, `#smartphone addiction`, `#mental health`, `#productivity`

---

<a id="item-8"></a>
## [Easyduino：开源 KiCad 开发板模板](https://github.com/Hanqaqa/Easyduino) ⭐️ 7.0/10

Easyduino 项目提供了针对 Arduino 和 ESP32 开发板的开源 KiCad PCB 设计，可作为学习和定制化模板。 这填补了常见开发板开源硬件设计的空白，使爱好者和工程师能够修改并从经过验证的布局中学习。 该仓库包含 Arduino Uno 和 ESP32 DevKit 等板的 KiCad 项目文件，使用户能够轻松调整设计。

hackernews · Hanqaqa · Apr 27, 17:45

**背景**: KiCad 是一款免费开源的电子设计自动化（EDA）工具，用于原理图绘制和 PCB 布局。Arduino 和 ESP32 开发板在原型设计中广泛使用，但其官方 PCB 设计通常为专有或不易编辑。Easyduino 提供了复制这些板的开源 KiCad 模板，支持定制和学习。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kicad.org/">KiCad - Schematic Capture & PCB Design Software</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞 Easyduino 填补了学习空白，一位用户指出它有助于克服 ESP32 PCB 设计中的'未知的未知'。另一位分享说，自己制作 Arduino UNO PCB 的经历加深了对布线实践的理解。

**标签**: `#PCB design`, `#KiCad`, `#Arduino`, `#ESP32`, `#open source hardware`

---