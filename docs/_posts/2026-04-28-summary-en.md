---
layout: default
title: "Horizon Summary: 2026-04-28 (EN)"
date: 2026-04-28
lang: en
---

> From 12 items, 7 important content pieces were selected

---

1. [Microsoft and OpenAI end exclusive deal](#item-1) ⭐️ 9.0/10
2. [4TB of Voice Samples and IDs Stolen from 40K Mercor Contractors](#item-2) ⭐️ 8.0/10
3. [Interactive Color Perception Test Sparks Debate on Blue vs Green](#item-3) ⭐️ 8.0/10
4. [Microsoft releases VibeVoice: open-source speech-to-text with speaker diarization](#item-4) ⭐️ 8.0/10
5. [Talkie: 13B Language Model Trained on Pre-1931 Text](#item-5) ⭐️ 7.0/10
6. [Three Men Charged in Toronto SMS Blaster Scam](#item-6) ⭐️ 7.0/10
7. [Essay advocates staring at walls for mental downtime](#item-7) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Microsoft and OpenAI end exclusive deal](https://www.bloomberg.com/news/articles/2026-04-27/microsoft-to-stop-sharing-revenue-with-main-ai-partner-openai) ⭐️ 9.0/10

Microsoft and OpenAI have mutually agreed to end their exclusive cloud and revenue-sharing partnership, allowing OpenAI to use alternative cloud providers such as AWS and potentially Google Cloud TPUs. This restructuring breaks the previous monopoly of Azure over OpenAI‘s compute, potentially reshaping the AI infrastructure landscape and intensifying competition among cloud providers for AI workloads. The previous agreement included a clause that would nullify Microsoft's commercial IP rights if AGI were achieved, which now appears to be removed. OpenAI can now negotiate better pricing and access to Google's eighth-generation TPUs (TPU 8t/8i) for training and inference.

hackernews · helsinkiandrew · Apr 27, 13:22

**Background**: Since 2019, Microsoft had exclusive rights to provide cloud infrastructure for OpenAI, with a revenue-sharing agreement. Google TPUs are custom ASICs designed for neural network training, and the latest generation targets agentic AI workloads. The deal change follows OpenAI's financial pressures and the rise of competitors like Anthropic.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tensor_Processing_Unit">Tensor Processing Unit - Wikipedia</a></li>
<li><a href="https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/eighth-generation-tpu-agentic-era/">Our eighth generation TPUs: two chips for the agentic era</a></li>

</ul>
</details>

**Discussion**: Commenters largely see Google as the biggest winner, as OpenAI may adopt TPUs. Some question why Microsoft accepted terms that seem favorable to OpenAI, speculating it was to protect its investment. Others note the removal of the AGI clause signals a more pragmatic relationship.

**Tags**: `#AI`, `#OpenAI`, `#Microsoft`, `#cloud computing`, `#partnership`

---

<a id="item-2"></a>
## [4TB of Voice Samples and IDs Stolen from 40K Mercor Contractors](https://app.oravys.com/blog/mercor-breach-2026) ⭐️ 8.0/10

A data breach at Mercor, an AI contractor platform, leaked 4TB of voice recordings and identification documents from approximately 40,000 contractors, enabling deepfake attacks. This breach combines biometric voice data with ID scans, creating a deepfake-ready kit that can bypass voice authentication systems used in banking, video calls, and insurance, posing long-term risks since biometrics cannot be changed. The leaked data includes voice samples paired with ID document scans, allowing attackers to create convincing deepfakes. The breach was claimed by the Lapsus$ hacking group and has led Meta to pause work with Mercor.

hackernews · Oravys · Apr 27, 09:57

**Background**: Biometric data such as voice and fingerprints is increasingly used for security but cannot be changed if compromised. Deepfake technology can synthesize realistic voices from short audio samples, enabling fraud like voice phishing (vishing) and unauthorized access. The combination of voice and ID data in this breach makes it particularly dangerous because attackers can impersonate victims in real-time calls.

<details><summary>References</summary>
<ul>
<li><a href="https://app.oravys.com/blog/mercor-breach-2026">4TB of voice samples stolen from 40,000 AI contractors ... | ORAVYS</a></li>
<li><a href="https://www.halborn.com/blog/post/explained-the-mercor-hack-april-2026">Explained: The Mercor Hack (April 2026)</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/deepfake-voice-attacks-are-outpacing-defenses-what-security-leaders-should-know/">Deepfake Voice Attacks are Outpacing Defenses: What Security Leaders Should Know</a></li>

</ul>
</details>

**Discussion**: Commenters noted the irony of offering free voice verification to victims, which requires sending more voice data to another AI company. There was criticism of Mercor for tricking contractors and poor security, with calls for stronger consequences. Many emphasized that biometrics are 'forever passwords' and urged people to avoid sharing them.

**Tags**: `#security breach`, `#AI`, `#biometrics`, `#deepfake`, `#privacy`

---

<a id="item-3"></a>
## [Interactive Color Perception Test Sparks Debate on Blue vs Green](https://ismy.blue/) ⭐️ 8.0/10

An interactive web app at ismy.blue allows users to identify their personal boundary between blue and green, revealing surprising variations in individual color perception. This simple tool highlights the subjectivity of color perception and connects to broader discussions on linguistic relativity, showing that language and culture may influence how we categorize colors. The test presents a series of colors transitioning from blue to green, asking users to label each as either blue or green, and then estimates where their personal boundary lies compared to the population.

hackernews · theogravity · Apr 27, 20:24

**Background**: Color perception is not universal; languages vary in how they name colors, and research on linguistic relativity suggests that language can influence perception. For example, some languages have a single term for blue and green, while others distinguish them early.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Linguistic_relativity">Linguistic relativity</a></li>
<li><a href="https://en.wikipedia.org/wiki/Linguistic_relativity_and_the_color_naming_debate">Linguistic relativity and the color naming debate - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration that the forced binary choice between blue and green ignored intermediate colors like teal or turquoise. Others shared personal anecdotes about disagreements with partners, and some noted an anchoring effect in the test's adaptive algorithm.

**Tags**: `#color perception`, `#psychology`, `#linguistics`, `#interactive`, `#Hacker News`

---

<a id="item-4"></a>
## [Microsoft releases VibeVoice: open-source speech-to-text with speaker diarization](https://simonwillison.net/2026/Apr/27/vibevoice/#atom-everything) ⭐️ 8.0/10

Microsoft released VibeVoice on January 21, 2026, as an MIT-licensed speech-to-text model with built-in speaker diarization. The model can be easily run on Apple Silicon Macs using the mlx-audio library and a 4-bit quantized version (5.71 GB) available on Hugging Face. VibeVoice simplifies multi-speaker transcription by integrating speaker diarization directly into the model, eliminating the need for separate pipelines. Its open-source MIT license and easy deployment via mlx-audio lower the barrier for developers and researchers to build speech applications. The model supports up to 60 minutes of audio per inference, with a default max-tokens of 8192 (about 25 minutes) that can be increased. On a 128GB M5 Max MacBook Pro, processing one hour of audio takes about 8 minutes 45 seconds with peak memory usage between 30–61 GB.

rss · Simon Willison · Apr 27, 23:46

**Background**: Speaker diarization is the task of partitioning an audio stream into segments according to who is speaking, answering 'who spoke when'. Traditional systems require separate models for speech recognition and diarization. MLX is Apple's machine learning framework for efficient inference on Apple Silicon, and mlx-audio is a community library providing audio processing pipelines built on MLX.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speaker_diarisation">Speaker diarisation</a></li>
<li><a href="https://github.com/Blaizzy/mlx-audio">GitHub - Blaizzy/ mlx - audio : A text-to-speech (TTS), speech-to-text...</a></li>

</ul>
</details>

**Tags**: `#speech-to-text`, `#machine learning`, `#open source`, `#Microsoft`, `#speaker diarization`

---

<a id="item-5"></a>
## [Talkie: 13B Language Model Trained on Pre-1931 Text](https://talkie-lm.com/introducing-talkie) ⭐️ 7.0/10

Researchers released Talkie, a 13-billion-parameter language model trained exclusively on 260 billion tokens of English text from before 1931, simulating the knowledge of a 1930s AI. Talkie offers a unique lens into historical knowledge and biases, but also reveals the challenges of enforcing strict data cutoffs; it sparks discussion about AI's relationship with time and historical accuracy. The model is available in base and instruction-tuned versions on Hugging Face, and notable contributors include Alec Radford, co-creator of GPT. Community testing shows it struggles with events like the Great Depression, indicating data leakage or imbalanced sources.

hackernews · jekude · Apr 27, 21:55

**Background**: Vintage language models are trained on text from a specific historical period to simulate what an AI from that era would know. They require rigorous data filtering to prevent modern information from leaking in. Talkie uses a curated dataset of pre-1931 texts from sources like books, newspapers, and scientific journals.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=47927903">Talkie : a 13B vintage language model from 1930 | Hacker News</a></li>

</ul>
</details>

**Discussion**: Comments highlight historical inaccuracies—the model seems more informed about 1900 than 1930, missing the Great Depression. There is excitement about Alec Radford's involvement, and some humor about the name.

**Tags**: `#language model`, `#AI`, `#vintage AI`, `#historical`, `#deep learning`

---

<a id="item-6"></a>
## [Three Men Charged in Toronto SMS Blaster Scam](https://www.tps.ca/media-centre/stories/unprecedented-sms-blaster-arrests/) ⭐️ 7.0/10

Toronto police arrested three men for using SMS blasters—portable fake cell towers—to send spam and phishing messages to nearby phones. The charges mark the first such arrests in Canada. This case highlights the growing threat of SMS blasters, which bypass carrier filters and can be used for large-scale phishing attacks. It also raises concerns about phone security and trust in cellular networks. The devices, similar to stingrays used by law enforcement, impersonate legitimate cell towers and can intercept IMSI numbers. The suspects allegedly used them to send fraudulent messages mimicking banks and government agencies.

hackernews · gnabgib · Apr 27, 20:44

**Background**: SMS blasters are portable devices that mimic cell towers, forcing nearby phones to connect to them. They can then inject spam or phishing texts that appear to come from legitimate numbers, bypassing carrier spam filters. This technology is a variant of IMSI-catchers, commonly known as stingrays, which have been used by law enforcement for surveillance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techradar.com/computing/cyber-security/new-sms-blaster-text-scams-are-on-the-rise-security-experts-warn-stay-safe-by-changing-this-one-phone-setting">New ‘SMS blaster’ text scams are on the rise, security ...</a></li>
<li><a href="https://www.kaspersky.com/blog/what-are-sms-blasters-and-how-to-protect-yourself/53810/">What an SMS blaster is, and how to protect yourself from ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/IMSI-catcher">IMSI-catcher - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted that such scams are common in Brazil, where spam leads people to use WhatsApp exclusively. Some questioned the media hype, pointing out that law enforcement uses similar devices legally. Others asked about the technical feasibility and lack of cryptographic verification in SMS.

**Tags**: `#security`, `#SMS spam`, `#stingray`, `#phishing`, `#law enforcement`

---

<a id="item-7"></a>
## [Essay advocates staring at walls for mental downtime](https://www.alexselimov.com/posts/men_who_stare_at_walls/) ⭐️ 7.0/10

An essay titled 'Men who stare at walls' argues that deliberately staring at a blank wall can help reclaim the mental downtime that smartphones have stolen. This piece resonates widely because it addresses the pervasive issue of constant digital stimulation eroding our ability to think without distractions, encouraging readers to prioritize mental stillness. The essay is a personal reflection rather than a scientific study, yet its high engagement (492 points, 219 comments) indicates strong cultural relevance and shared experience.

hackernews · aselimov3 · Apr 27, 11:08

**Background**: In modern life, smartphones fill every spare moment with content, leaving little time for mind-wandering, which is crucial for creativity and mental processing. Staring at walls is a form of deliberate disattention that can replenish cognitive resources, similar to meditation but without formal technique.

**Discussion**: Commenters largely agree with the essay, sharing personal anecdotes about reclaiming disattention through activities like staring at walls or driving. Some equate it to meditation, while others emphasize the loss of unstructured thinking time.

**Tags**: `#attention`, `#digital habits`, `#mental health`, `#meditation`, `#technology impact`

---