---
layout: default
title: "Horizon Summary: 2026-04-28 (EN)"
date: 2026-04-28
lang: en
---

> From 12 items, 8 important content pieces were selected

---

1. [Microsoft and OpenAI end exclusive deal, OpenAI free to use other clouds](#item-1) ⭐️ 10.0/10
2. [Talkie: A 13B Language Model Trained on 1930s Text](#item-2) ⭐️ 8.0/10
3. [Microsoft Releases Open-Source VibeVoice STT Model](#item-3) ⭐️ 8.0/10
4. [Microsoft-OpenAI AGI Clause Officially Removed](#item-4) ⭐️ 8.0/10
5. [Toronto SMS Blaster Arrests: 3 Men Face Charges](#item-5) ⭐️ 7.0/10
6. [Website reveals differences in color perception](#item-6) ⭐️ 7.0/10
7. [Men Who Stare at Walls: The Lost Art of Disattention](#item-7) ⭐️ 7.0/10
8. [Easyduino: Open Source KiCad Devboard Templates](#item-8) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Microsoft and OpenAI end exclusive deal, OpenAI free to use other clouds](https://www.bloomberg.com/news/articles/2026-04-27/microsoft-to-stop-sharing-revenue-with-main-ai-partner-openai) ⭐️ 10.0/10

Microsoft and OpenAI have ended their exclusive cloud and revenue-sharing agreement, effective immediately, allowing OpenAI to use competing cloud providers such as AWS and Google Cloud for its AI infrastructure. This marks a major realignment in the AI industry, as OpenAI is no longer tied to Azure, potentially shifting the balance of power among cloud providers and enabling OpenAI to access more diverse hardware like Google's TPUs. The original agreement had given Microsoft exclusive rights to host OpenAI's models and a revenue share, but OpenAI's rapid growth and need for more compute capacity likely prompted the change.

hackernews · helsinkiandrew · Apr 27, 13:22

**Background**: Microsoft and OpenAI had a multi-billion-dollar partnership where Microsoft provided exclusive cloud computing via Azure and received a percentage of OpenAI's revenue. This deal helped OpenAI scale but limited its infrastructure choices. The end of exclusivity allows OpenAI to negotiate better terms and potentially use Google's TPUs or AWS's custom chips.

**Discussion**: Commenters debated the implications: some saw Google as the biggest winner due to its TPU advantage, while others interpreted the move as a sign of OpenAI's financial struggles. A former lawyer remarked that such restructuring indicates a 'cash-strapped scramble.' One user noted that despite the hype, even top AI models remain unreliable and require careful review.

**Tags**: `#Microsoft`, `#OpenAI`, `#AI`, `#cloud computing`, `#partnership`

---

<a id="item-2"></a>
## [Talkie: A 13B Language Model Trained on 1930s Text](https://talkie-lm.com/introducing-talkie) ⭐️ 8.0/10

Researchers have released Talkie, a 13-billion-parameter language model trained exclusively on 260 billion tokens of pre-1931 English text, capturing the language and knowledge of the 1930s. This project offers a unique historical lens, enabling studies of past language, beliefs, and worldviews, and opens up novel AI applications in historical research and education. Two versions are available on Hugging Face: a base model (53.1 GB) and an instruction-tuned variant (26.6 GB). The model performs well on recall of pre-1930 facts but struggles with events like the Great Depression, indicating its training data cutoff.

hackernews · jekude · Apr 27, 21:55

**Background**: Large language models like GPT-3 are typically trained on diverse internet text spanning recent decades. Talkie diverges by using a carefully curated corpus of only historical texts, aiming to recreate the language model that would have existed in 1930 if the technology were available.

**Discussion**: Comments highlight mixed reception: some find the historical outputs fascinating, while others note inaccuracies about technology and politics, suggesting the model relies on pre-1900 information. Alec Radford's involvement adds credibility.

**Tags**: `#language model`, `#vintage data`, `#historical AI`, `#machine learning`, `#NLP`

---

<a id="item-3"></a>
## [Microsoft Releases Open-Source VibeVoice STT Model](https://simonwillison.net/2026/Apr/27/vibevoice/#atom-everything) ⭐️ 8.0/10

Microsoft released VibeVoice, an MIT-licensed Whisper-style audio model for speech-to-text with built-in speaker diarization, on January 21, 2026. The model can transcribe audio up to an hour and outputs JSON with speaker labels. VibeVoice combines speech-to-text and speaker diarization in a single open-source model, reducing the need for separate pipelines. Its MIT license encourages broad adoption for applications like podcast transcription and meeting analysis. VibeVoice can process up to 59 minutes of audio per run, with a default max-tokens of 8,192 (~25 minutes), and requires about 30–60GB of RAM. It achieves ~50 tokens/sec in prompt processing and ~38 tokens/sec in generation on an M5 Max MacBook Pro.

rss · Simon Willison · Apr 27, 23:46

**Background**: Speaker diarization is the task of partitioning an audio stream into segments labeled by speaker identity, answering 'who spoke when'. Whisper-style models are end-to-end speech recognition systems based on transformers, originally popularized by OpenAI's Whisper. VibeVoice extends this by integrating diarization directly into the model, whereas traditional approaches use separate systems.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speaker_diarisation">Speaker diarisation</a></li>
<li><a href="https://ml-explore.github.io/mlx/build/html/index.html">MLX — MLX 0.31.1 documentation</a></li>

</ul>
</details>

**Tags**: `#speech-to-text`, `#AI`, `#Microsoft`, `#open-source`, `#machine learning`

---

<a id="item-4"></a>
## [Microsoft-OpenAI AGI Clause Officially Removed](https://simonwillison.net/2026/Apr/27/now-deceased-agi-clause/#atom-everything) ⭐️ 8.0/10

The AGI clause that would void Microsoft's IP rights upon AGI achievement has been removed in the amended partnership agreement between Microsoft and OpenAI, announced on April 27, 2026. This removal fundamentally restructures one of the most influential AI partnerships, affecting IP rights, exclusivity, and incentives around AGI development. The clause originally defined AGI as systems capable of generating $100 billion in profits for early investors; later it required verification by an independent expert panel. With the removal, Microsoft loses exclusivity but retains IP rights until 2030 or AGI declaration, whichever is first.

rss · Simon Willison · Apr 27, 18:38

**Background**: The clause was part of the 2019 Microsoft-OpenAI partnership, designed to limit Microsoft's control if OpenAI achieved AGI. AGI (Artificial General Intelligence) refers to a hypothetical AI system that matches or surpasses human capabilities across virtually all cognitive tasks. The exact definition of AGI has been a point of contention, with the clause evolving from a simple milestone to a profit-based metric.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/918981/openai-microsoft-renegotiate-contract">Microsoft and OpenAI’s famed AGI agreement is dead</a></li>
<li><a href="https://arstechnica.com/ai/2026/04/no-longer-exclusive-microsoft-agrees-to-let-openai-see-other-cloud-providers/">OpenAI ends its exclusive partnership with Microsoft - Ars ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Artificial_general_intelligence">Artificial general intelligence - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AGI`, `#OpenAI`, `#Microsoft`, `#AI governance`, `#IP rights`

---

<a id="item-5"></a>
## [Toronto SMS Blaster Arrests: 3 Men Face Charges](https://www.tps.ca/media-centre/stories/unprecedented-sms-blaster-arrests/) ⭐️ 7.0/10

Three men were arrested in Toronto for using SMS blasters to send phishing texts, marking what authorities call an unprecedented case in Canada. This case highlights vulnerabilities in telecom networks that allow SMS spoofing, and underscores the growing threat of phishing scams delivered via mobile devices. The SMS blaster devices could disrupt cellular network connections and potentially block calls to 911, and the suspects allegedly hijacked thousands of phones to send spam.

hackernews · gnabgib · Apr 27, 20:44

**Background**: SMS blasters are portable devices that mimic cell towers, exploiting weaknesses in the SS7 protocol to send fake SMS messages without carrier verification. This technique bypasses typical spam filters and allows scammers to spoof sender IDs. SS7 vulnerabilities have been known for years but remain largely unpatched in many networks.

<details><summary>References</summary>
<ul>
<li><a href="https://gizmodo.com/canadian-police-arrest-three-men-behind-sms-blaster-scam-that-allegedly-hijacked-thousands-of-phones-2000751386">Canadian Police Arrest Three Men Behind SMS Blaster Scam That ...</a></li>
<li><a href="https://www.techradar.com/computing/cyber-security/new-sms-blaster-text-scams-are-on-the-rise-security-experts-warn-stay-safe-by-changing-this-one-phone-setting">New ‘SMS blaster’ text scams are on the rise, security ...</a></li>
<li><a href="https://dailysecurityreview.com/cyber-security/application-security/ss7-alarm-tcap-tag-exploit-lets-attackers-intercept-sms-and-track-users/">SS7 Alarm: TCAP Tag Exploit Lets Attackers Intercept SMS and ...</a></li>

</ul>
</details>

**Discussion**: Comments on the news highlight mixed reactions: some question the novelty of the devices, noting that law enforcement uses similar stingray technology. Others discuss how SS7 weaknesses enable such attacks and compare the situation to widespread SMS spam in Brazil, where many users rely solely on WhatsApp.

**Tags**: `#cybersecurity`, `#SMS spam`, `#phishing`, `#telecom security`, `#law enforcement`

---

<a id="item-6"></a>
## [Website reveals differences in color perception](https://ismy.blue/) ⭐️ 7.0/10

A new interactive website called 'Is my blue your blue?' asks users to categorize colors as blue or green, revealing where each individual draws the boundary between these hues. This experiment highlights that color perception is subjective and varies significantly across individuals and cultures, challenging the assumption that everyone sees colors the same way. The site presents colors ranging from clearly blue to clearly green, and users must click 'blue' or 'green' for each; the results show the user's personal boundary relative to the population average.

hackernews · theogravity · Apr 27, 20:24

**Background**: Color perception is influenced by both biology and language; cultures differ in how they name and categorize colors, such as the Japanese word 'ao' covering both blue and green. The phenomenon of color boundary variation is a well-known topic in cognitive science and linguistics.

**Discussion**: Commenters shared personal anecdotes about disagreements with others over color category, and some expressed frustration that the binary choice between blue and green did not allow for intermediate colors like turquoise or teal. Cultural differences, such as the Japanese 'blue' traffic light, were also noted.

**Tags**: `#color perception`, `#cognitive science`, `#linguistics`, `#interactive experiment`, `#pop science`

---

<a id="item-7"></a>
## [Men Who Stare at Walls: The Lost Art of Disattention](https://www.alexselimov.com/posts/men_who_stare_at_walls/) ⭐️ 7.0/10

The essay discusses the overlooked importance of letting the mind wander without digital distractions, coining the term 'disattention' to describe these unstructured moments of mental downtime. In a smartphone-saturated world, constant digital engagement robs people of crucial mental breaks that foster creativity, problem-solving, and emotional processing; reclaiming disattention could improve mental health and productivity. The article contrasts disattention with meditation, noting that while meditation is structured, disattention is spontaneous and unstructured; it highlights the instinct to fill every spare moment with doomscrolling as a hard habit to break.

hackernews · aselimov3 · Apr 27, 11:08

**Background**: Disattention refers to the natural state of letting the mind drift without focusing on a particular task, often occurring during mundane activities like staring at a wall or driving. In the modern attention economy, smartphones constantly demand attention, erasing these valuable mental pauses that allow subconscious processing.

**Discussion**: Commenters strongly agree with the essay, sharing personal anecdotes about losing disattention to smartphones. One user notes that smartphones steal not just attention but disattention itself; others compare it to meditation and emphasize the difficulty of resisting the urge to fill downtime with scrolling.

**Tags**: `#attention`, `#mindfulness`, `#smartphone addiction`, `#mental health`, `#productivity`

---

<a id="item-8"></a>
## [Easyduino: Open Source KiCad Devboard Templates](https://github.com/Hanqaqa/Easyduino) ⭐️ 7.0/10

Easyduino provides open-source KiCad PCB designs for Arduino and ESP32 devboards, serving as templates for learning and customization. This fills a gap for open-source hardware designs of popular devboards, enabling hobbyists and engineers to modify and learn from proven layouts. The repository includes KiCad project files for boards like Arduino Uno and ESP32 DevKit, allowing users to easily adapt designs.

hackernews · Hanqaqa · Apr 27, 17:45

**Background**: KiCad is a free and open-source electronic design automation (EDA) tool for schematic capture and PCB layout. Arduino and ESP32 devboards are widely used in prototyping, but their official PCB designs are often proprietary or not easily editable. Easyduino offers open-source KiCad templates that replicate these boards, enabling customization and learning.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kicad.org/">KiCad - Schematic Capture & PCB Design Software</a></li>

</ul>
</details>

**Discussion**: Commenters praised Easyduino for filling a learning gap, with one user noting it helps overcome 'unknown unknowns' in ESP32 PCB design. Another shared that creating their own Arduino UNO PCB improved their understanding of routing practices.

**Tags**: `#PCB design`, `#KiCad`, `#Arduino`, `#ESP32`, `#open source hardware`

---