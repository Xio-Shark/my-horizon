---
layout: default
title: "Horizon Summary: 2026-04-28 (ZH)"
date: 2026-04-28
lang: zh
---

> From 12 items, 7 important content pieces were selected

---

1. [微软与 OpenAI 终止独家合作](#item-1) ⭐️ 9.0/10
2. [40000 名 Mercor 承包商 4TB 语音及身份证件遭窃](#item-2) ⭐️ 8.0/10
3. [交互式色彩感知测试引发蓝绿边界讨论](#item-3) ⭐️ 8.0/10
4. [微软发布 VibeVoice：开源语音转文字，内置说话人角色标注](#item-4) ⭐️ 8.0/10
5. [Talkie：基于 1930 年前文本训练的 130 亿参数语言模型](#item-5) ⭐️ 7.0/10
6. [多伦多三人因使用短信群发器诈骗被控](#item-6) ⭐️ 7.0/10
7. [文章主张盯着墙壁以获得心理休息](#item-7) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [微软与 OpenAI 终止独家合作](https://www.bloomberg.com/news/articles/2026-04-27/microsoft-to-stop-sharing-revenue-with-main-ai-partner-openai) ⭐️ 9.0/10

微软与 OpenAI 已同意终止其独家云服务和收入分成合作，允许 OpenAI 使用 AWS 等替代云服务商，并可能使用 Google Cloud TPU。 这一重组打破了此前 Azure 对 OpenAI 算力的垄断，可能重塑 AI 基础设施格局，并加剧云服务商在 AI 工作负载上的竞争。 之前的协议包含一项条款，即在实现通用人工智能时微软的商业知识产权将失效，该条款似乎已被删除。OpenAI 现在可以协商更优惠的价格，并获取 Google 第八代 TPU（TPU 8t/8i）用于训练和推理。

hackernews · helsinkiandrew · Apr 27, 13:22

**背景**: 自 2019 年以来，微软一直独家为 OpenAI 提供云基础设施，并签订收入分成协议。Google TPU 是专为神经网络训练设计的定制 ASIC，最新一代针对智能体 AI 工作负载。此次协议变更发生在 OpenAI 面临财务压力以及竞争对手如 Anthropic 崛起之后。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tensor_Processing_Unit">Tensor Processing Unit - Wikipedia</a></li>
<li><a href="https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/eighth-generation-tpu-agentic-era/">Our eighth generation TPUs: two chips for the agentic era</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为谷歌是最大赢家，因为 OpenAI 可能会采用 TPU。有人质疑微软为何接受看似对 OpenAI 有利的条款，推测是为了保护其投资。另一些人指出，AGI 条款的移除标志着双方关系更加务实。

**标签**: `#AI`, `#OpenAI`, `#Microsoft`, `#cloud computing`, `#partnership`

---

<a id="item-2"></a>
## [40000 名 Mercor 承包商 4TB 语音及身份证件遭窃](https://app.oravys.com/blog/mercor-breach-2026) ⭐️ 8.0/10

人工智能承包商平台 Mercor 发生数据泄露，约 40000 名承包商的 4TB 语音录音和身份证件被盗，可能导致深度伪造攻击。 此次泄露将生物识别语音数据与身份证件扫描件结合，形成深度伪造攻击工具包，可绕过银行、视频通话和保险领域的语音认证系统，且生物特征无法更改，带来长期风险。 泄露数据包含语音样本与身份证件扫描件的配对信息，攻击者可据此生成逼真的深度伪造内容。该事件由 Lapsus$黑客团伙宣称负责，已导致 Meta 暂停与 Mercor 的合作。

hackernews · Oravys · Apr 27, 09:57

**背景**: 语音、指纹等生物识别数据越来越多地用于安全认证，但一旦泄露便无法更改。深度伪造技术可从短音频样本中合成逼真的语音，从而实现语音钓鱼（vishing）和未经授权访问等欺诈行为。本次泄露将语音与身份证数据结合，使得攻击者能够在实时通话中冒充受害者，危险程度极高。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://app.oravys.com/blog/mercor-breach-2026">4TB of voice samples stolen from 40,000 AI contractors ... | ORAVYS</a></li>
<li><a href="https://www.halborn.com/blog/post/explained-the-mercor-hack-april-2026">Explained: The Mercor Hack (April 2026)</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/deepfake-voice-attacks-are-outpacing-defenses-what-security-leaders-should-know/">Deepfake Voice Attacks are Outpacing Defenses: What Security Leaders Should Know</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，为受害者提供免费语音验证具有讽刺意味，因为需要向另一家 AI 公司提交更多语音数据。Mercor 欺骗承包商且安全措施不力遭到批评，人们呼吁加强问责。许多人强调生物特征相当于“永久密码”，敦促避免分享。

**标签**: `#security breach`, `#AI`, `#biometrics`, `#deepfake`, `#privacy`

---

<a id="item-3"></a>
## [交互式色彩感知测试引发蓝绿边界讨论](https://ismy.blue/) ⭐️ 8.0/10

ismy.blue 网站上的交互式网页应用让用户识别自己眼中的蓝色与绿色边界，揭示了个人色彩感知的惊人差异。 这个简单的工具凸显了色彩感知的主观性，并与语言相对论的广泛讨论相连，表明语言和文化可能影响我们对颜色的分类方式。 该测试展示一系列从蓝色过渡到绿色的颜色，要求用户将每种颜色标记为蓝色或绿色，然后评估个人边界相对于人群的位置。

hackernews · theogravity · Apr 27, 20:24

**背景**: 色彩感知并非普世通用；不同语言对颜色的命名方式各异，语言相对论的研究表明语言可能影响感知。例如，有些语言用同一个词表示蓝色和绿色，而其他语言则较早区分二者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Linguistic_relativity">Linguistic relativity</a></li>
<li><a href="https://en.wikipedia.org/wiki/Linguistic_relativity_and_the_color_naming_debate">Linguistic relativity and the color naming debate - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了对强迫在蓝色和绿色之间二选一的沮丧，认为这忽略了蓝绿色或青绿色等中间色。其他人分享了与伴侣意见分歧的个人轶事，一些人指出测试自适应算法中存在锚定效应。

**标签**: `#color perception`, `#psychology`, `#linguistics`, `#interactive`, `#Hacker News`

---

<a id="item-4"></a>
## [微软发布 VibeVoice：开源语音转文字，内置说话人角色标注](https://simonwillison.net/2026/Apr/27/vibevoice/#atom-everything) ⭐️ 8.0/10

微软于 2026 年 1 月 21 日发布了 VibeVoice，这是一个 MIT 许可的语音转文字模型，内置说话人角色标注功能。通过 mlx-audio 库和 Hugging Face 上提供的 4 位量化版本（5.71 GB），可以在 Apple Silicon Mac 上轻松运行。 VibeVoice 将说话人角色标注直接集成到模型中，简化了多说话人转录流程，无需单独的流水线。其开源 MIT 许可和通过 mlx-audio 的便捷部署降低了开发者和研究人员构建语音应用的门槛。 该模型单次推理最多支持 60 分钟音频，默认 max-tokens 为 8192（约 25 分钟），可以调高。在 128GB M5 Max MacBook Pro 上，处理一小时音频约需 8 分 45 秒，峰值内存使用在 30–61 GB 之间。

rss · Simon Willison · Apr 27, 23:46

**背景**: 说话人角色标注是将音频流按说话人身份分割的任务，回答“谁在何时说话”。传统系统需要独立的语音识别和角色标注模型。MLX 是苹果公司面向 Apple Silicon 的机器学习框架，可实现高效推理；mlx-audio 是一个社区库，提供基于 MLX 构建的音频处理流水线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speaker_diarisation">Speaker diarisation</a></li>
<li><a href="https://github.com/Blaizzy/mlx-audio">GitHub - Blaizzy/ mlx - audio : A text-to-speech (TTS), speech-to-text...</a></li>

</ul>
</details>

**标签**: `#speech-to-text`, `#machine learning`, `#open source`, `#Microsoft`, `#speaker diarization`

---

<a id="item-5"></a>
## [Talkie：基于 1930 年前文本训练的 130 亿参数语言模型](https://talkie-lm.com/introducing-talkie) ⭐️ 7.0/10

研究人员发布了 Talkie，这是一个 130 亿参数的语言模型，仅使用 1931 年之前的 2600 亿 token 英文文本进行训练，模拟 1930 年代 AI 的知识水平。 Talkie 为历史知识和偏见提供了独特的视角，但也揭示了严格数据截止的挑战；它引发了关于 AI 与时间及历史准确性关系的讨论。 该模型在 Hugging Face 上提供基础版和指令微调版，著名贡献者包括 GPT 联合创始人 Alec Radford。社区测试显示它对大萧条等事件理解困难，表明存在数据泄露或来源不平衡的问题。

hackernews · jekude · Apr 27, 21:55

**背景**: 复古语言模型使用特定历史时期的文本进行训练，以模拟那个时代 AI 的知识水平。它们需要严格的数据过滤，防止现代信息泄露。Talkie 使用了来自书籍、报纸和科学期刊等来源的 1931 年前文本的精选数据集。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=47927903">Talkie : a 13B vintage language model from 1930 | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论指出了历史不准确性——模型似乎更了解 1900 年而非 1930 年，缺失了大萧条信息。大家对 Alec Radford 的参与感到兴奋，也有一些关于名字的幽默。

**标签**: `#language model`, `#AI`, `#vintage AI`, `#historical`, `#deep learning`

---

<a id="item-6"></a>
## [多伦多三人因使用短信群发器诈骗被控](https://www.tps.ca/media-centre/stories/unprecedented-sms-blaster-arrests/) ⭐️ 7.0/10

多伦多警方逮捕了三名男子，他们使用便携式假基站（即短信群发器）向附近的手机发送垃圾和钓鱼短信。这是加拿大首次因这类设备进行逮捕。 此案凸显了短信群发器日益增长的威胁，它能够绕过运营商过滤器，用于大规模钓鱼攻击。同时，它也引发了人们对手机安全和蜂窝网络信任度的担忧。 这些设备与执法部门使用的 stingrays 类似，会冒充合法的蜂窝基站，并能截获 IMSI 号码。嫌疑人涉嫌利用它们发送冒充银行和政府机构的欺诈信息。

hackernews · gnabgib · Apr 27, 20:44

**背景**: 短信群发器是模仿蜂窝基站的便携设备，会强制附近的手机连接到它们。然后，它们可以注入看起来来自合法号码的垃圾或钓鱼短信，从而绕过运营商的垃圾过滤器。这种技术是 IMSI 捕获器（俗称 stingrays）的一种变体，此前被执法部门用于监控。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.techradar.com/computing/cyber-security/new-sms-blaster-text-scams-are-on-the-rise-security-experts-warn-stay-safe-by-changing-this-one-phone-setting">New ‘SMS blaster’ text scams are on the rise, security ...</a></li>
<li><a href="https://www.kaspersky.com/blog/what-are-sms-blasters-and-how-to-protect-yourself/53810/">What an SMS blaster is, and how to protect yourself from ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/IMSI-catcher">IMSI-catcher - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这类诈骗在巴西很常见，垃圾信息导致人们只用 WhatsApp。有人质疑媒体的夸大，指出执法部门也合法使用类似设备。还有人询问技术可行性以及短信缺乏加密验证的问题。

**标签**: `#security`, `#SMS spam`, `#stingray`, `#phishing`, `#law enforcement`

---

<a id="item-7"></a>
## [文章主张盯着墙壁以获得心理休息](https://www.alexselimov.com/posts/men_who_stare_at_walls/) ⭐️ 7.0/10

一篇题为《盯着墙看的人》的文章认为，故意盯着空白墙壁有助于重新夺回智能手机偷走的心理休息时间。 这篇文章引发广泛共鸣，因为它触及了持续数字刺激侵蚀我们无干扰思考能力的普遍问题，鼓励读者优先考虑心理宁静。 这篇文章是个人反思而非科学研究，但其高参与度（492 分，219 条评论）表明其强烈的文化相关性和共同体验。

hackernews · aselimov3 · Apr 27, 11:08

**背景**: 在现代生活中，智能手机用内容填满了每一刻空闲时间，几乎没有留给心智漫游的时间，而这对创造力和心理处理至关重要。盯着墙壁是一种刻意的分心形式，可以补充认知资源，类似于冥想但无需正式技巧。

**社区讨论**: 评论者普遍赞同这篇文章，分享个人经历，如通过盯着墙壁或开车来重新获得无注意状态。一些人将其等同于冥想，而另一些人则强调无结构思考时间的丧失。

**标签**: `#attention`, `#digital habits`, `#mental health`, `#meditation`, `#technology impact`

---