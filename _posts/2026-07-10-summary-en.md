---
layout: default
title: "Horizon Summary: 2026-07-10 (EN)"
date: 2026-07-10
lang: en
---

> From 129 items, 8 important content pieces were selected

---

1. [Long March 10B achieves first controlled stage recovery, world-first net-recovery](#item-1) ⭐️ 10.0/10
2. [Bun Rewritten from Zig to Rust Using AI Agents](#item-2) ⭐️ 10.0/10
3. [EU Parliament Greenlights Mass Scanning of Private Messages](#item-3) ⭐️ 9.0/10
4. [GPT-5.6: OpenAI achieves SOTA on ARC-AGI-3](#item-4) ⭐️ 9.0/10
5. [Postgres Rust Rewrite Passes All Tests](#item-5) ⭐️ 9.0/10
6. [OpenAI Launches GPT-5.6 Series with Sol, Terra, Luna Models](#item-6) ⭐️ 9.0/10
7. [Anthropic's Jacobian lens reveals hidden reasoning space in Claude](#item-7) ⭐️ 9.0/10
8. [Mitchell Hashimoto on Ghostty, Zig, and Pragmatic Engineering](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Long March 10B achieves first controlled stage recovery, world-first net-recovery](https://36kr.com/newsflashes/3889336420710921?f=rss) ⭐️ 10.0/10

The Long March 10B rocket launched from Hainan Commercial Space Launch Site and successfully recovered its first stage on an offshore platform using net-recovery, marking China's first controlled first-stage recovery and the world's first net-based rocket recovery. This breakthrough positions China as a key player in reusable rocket technology, which is vital for cost reduction and commercial space competitiveness. The innovative net-recovery method could simplify rocket design and improve recovery reliability, potentially disrupting the industry. Net-recovery uses a rocket-mounted hook and a sea-based net system to capture the first stage, absorbing kinetic energy via ground buffers, which relaxes landing precision requirements. The recovery platform is 144m long, 50m wide, with DP2 dynamic positioning and 25,000-ton displacement.

rss · 36氪 · Jul 10, 04:37

**Background**: Rocket first-stage recovery is essential for reusability, with SpaceX's Falcon 9 pioneering vertical landing recovery. China had not achieved controlled first-stage recovery until now. Net-recovery is a novel Chinese innovation where the rocket hooks onto a net, potentially simplifying landing gear and increasing payload capacity compared to traditional landing legs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.stdaily.com/web/gdxw/2025-12/02/content_440849.html">我国首个海上火箭回收平台交付，什么是“网系回收”？</a></li>

</ul>
</details>

**Tags**: `#航天`, `#火箭回收`, `#长征十号乙`, `#商业航天`, `#技术突破`

---

<a id="item-2"></a>
## [Bun Rewritten from Zig to Rust Using AI Agents](https://simonwillison.net/2026/Jul/8/rewriting-bun-in-rust/#atom-everything) ⭐️ 10.0/10

Jarred Sumner announced the rewrite of Bun from Zig to Rust, driven by persistent memory management bugs. The rewrite was largely automated using AI coding agents, with the TypeScript test suite serving as a conformance suite. This is a landmark event for the JavaScript runtime ecosystem, as Bun's stability improves dramatically with Rust's memory safety guarantees. It also validates AI-assisted large-scale code rewrites, potentially changing how future software migrations are approached. The rewrite took 11 days with Claude agents, costing $165,000 in API tokens (pre-merge). The new Rust-based Bun has been live in Claude Code since June 17, 2026, with a 10% startup speed improvement on Linux.

rss · Simon Willison · Jul 8, 23:57

**Background**: Bun is a fast all-in-one JavaScript runtime and toolkit, built by Oven. It was originally written in Zig, a low-level systems language focused on simplicity and performance. Many of Bun's bugs stemmed from mixing garbage collection with manual memory management, which Rust's ownership model prevents at compile time.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**Tags**: `#Rust`, `#Zig`, `#Bun`, `#JavaScript`, `#systems programming`

---

<a id="item-3"></a>
## [EU Parliament Greenlights Mass Scanning of Private Messages](https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/) ⭐️ 9.0/10

The EU Parliament approved Chat Control 1.0, allowing US tech companies to scan private messages without a warrant until 2028. This happened despite a majority of MEPs opposing it, because the motion to reject failed to secure an absolute majority. This law sets a precedent for mass surveillance of private communications, threatening fundamental privacy rights and democratic accountability. It affects all EU citizens and users of platforms like Instagram, Discord, Gmail, and iCloud. The vote required an absolute majority of all 720 MEPs to reject the measure, but only 314 voted against it, falling short of the needed 361. The regulation permits voluntary scanning of direct messages and emails by companies without judicial oversight, targeting child sexual abuse material.

hackernews · rapnie · Jul 9, 11:03 · [Discussion](https://news.ycombinator.com/item?id=48843923)

**Background**: Chat Control, officially the Regulation to Prevent and Combat Child Sexual Abuse (CSAR), was proposed by the European Commission in May 2022. It has been highly controversial due to privacy and encryption concerns. The EU Parliament had rejected similar measures twice in March 2024, but this version passed through a procedural loophole. The law is temporary, expiring in 2028.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://fightchatcontrol.eu/chat-control-overview">Chat Control 1.0 vs 2.0 - Fight Chat Control</a></li>
<li><a href="https://www.techtimes.com/articles/320010/20260709/eu-parliament-passes-chat-control-default-314-meps-couldnt-block-scanning-law.htm">EU Parliament Passes Chat Control by Default: 314 MEPs Couldn ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed outrage over the procedural trick and the erosion of privacy. Some noted the irony that a majority of voting MEPs opposed the measure but it still passed due to the absolute majority requirement. Others voiced disappointment in the EU's democratic process and concerns about mass surveillance.

**Tags**: `#privacy`, `#surveillance`, `#EU`, `#technology policy`, `#digital rights`

---

<a id="item-4"></a>
## [GPT-5.6: OpenAI achieves SOTA on ARC-AGI-3](https://openai.com/index/gpt-5-6/) ⭐️ 9.0/10

OpenAI has released GPT-5.6, a new large language model featuring enhanced intent understanding and original image preservation. The model achieves a state-of-the-art score of 7.8% on the ARC-AGI-3 benchmark, becoming the first verified frontier model to beat an ARC-AGI-3 game. This breakthrough on ARC-AGI-3, a benchmark designed to measure progress toward artificial general intelligence, signals significant advancement in model reasoning and adaptability. Improved intent understanding reduces the need for detailed user instructions, potentially transforming human-AI interaction across industries. The developer guide notes that GPT-5.6 can better infer user goals but still requires explicit constraints and success criteria. The model also preserves original image dimensions, which is beneficial for tasks relying on detailed visual input.

hackernews · OpenAI Blog · Jul 9, 17:04 · [Discussion](https://news.ycombinator.com/item?id=48849066)

**Background**: The ARC-AGI (Abstraction and Reasoning Corpus for Artificial General Intelligence) benchmark evaluates AI on visual reasoning tasks that are easy for humans but difficult for current AI. ARC-AGI-3 is the latest version, focusing on agentic intelligence and has remained unbeaten by any model until GPT-5.6. This achievement is considered a milestone on the path to general intelligence.

<details><summary>References</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi">ARC Prize - The only AI benchmark that measures AGI progress.</a></li>
<li><a href="https://llm-stats.com/benchmarks/arc-agi">ARC - AGI Leaderboard | LLM Stats</a></li>

</ul>
</details>

**Discussion**: The community is excited about the ARC-AGI-3 result, with users celebrating the first model to beat a game on the benchmark. However, some testing shows GPT-5.6 performs similarly to its predecessor GPT-5.5 and slightly behind Sonnet 5 on coding tasks, and there is skepticism about benchmark exclusions of competitors.

**Tags**: `#GPT-5.6`, `#OpenAI`, `#LLM`, `#ARC-AGI`, `#AI safety`

---

<a id="item-5"></a>
## [Postgres Rust Rewrite Passes All Tests](https://github.com/malisper/pgrust) ⭐️ 9.0/10

A complete rewrite of PostgreSQL in Rust, called pgrust, now passes 100% of the official PostgreSQL regression tests. The project was developed with heavy assistance from LLMs over a short period. This achievement demonstrates the feasibility of reimplementing a major database system in a memory-safe language like Rust, potentially leading to more secure and performant alternatives. It also highlights the growing role of LLMs in accelerating complex code migrations and rewrites. The rewrite passes all regression tests, which are comprehensive tests for SQL implementation in PostgreSQL. However, the project is currently a single-developer effort and the use of LLMs raises concerns about long-term maintainability and reviewability of the generated code.

hackernews · SweetSoftPillow · Jul 9, 06:18 · [Discussion](https://news.ycombinator.com/item?id=48841676)

**Background**: PostgreSQL is a 30-year-old relational database with a large C codebase. The regression tests are a standard suite used to verify correctness of SQL implementations. LLM-assisted code migration is an emerging technique where large language models help transform code between languages or frameworks, though it raises new challenges for code review and sustainability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.postgresql.org/docs/current/regress.html">PostgreSQL : Documentation: 18: Chapter 31. Regression Tests</a></li>
<li><a href="https://instil.co/blog/llm-assisted-code-modernisation">LLMs - A smarter way to modernise legacy code ? | Instil</a></li>

</ul>
</details>

**Discussion**: The community expressed mixed reactions, with some praising the technical feat while others raised concerns about single-developer sustainability, high token costs for LLM usage, and difficulty reviewing LLM-generated code. One commenter suggested mirroring queries to compare performance under real load.

**Tags**: `#rust`, `#postgresql`, `#database`, `#rewrite`, `#llm`

---

<a id="item-6"></a>
## [OpenAI Launches GPT-5.6 Series with Sol, Terra, Luna Models](https://www.ithome.com.tw/news/177229) ⭐️ 9.0/10

OpenAI has received US government approval to fully launch the GPT-5.6 model series, including the flagship Sol model and the Terra and Luna models, and integrate them into GitHub Copilot and Microsoft 365 Copilot. This marks a significant advancement in AI capabilities, claiming state-of-the-art performance across coding, knowledge work, life sciences, and cybersecurity, and its integration into widely-used development and productivity tools could impact millions of users. The GPT-5.6 series introduces an 'ultra' mode that leverages multiple sub-agents to accelerate complex tasks, and the models are said to surpass previous models as well as competitors like Google Gemini and Anthropic Claude Mythos.

rss · iThome Taiwan · Jul 10, 12:07

**Background**: Sub-agents are specialized AI instances designed to handle specific narrow tasks under a main agent, following an orchestrator-worker pattern. OpenAI's new 'ultra' mode uses such sub-agents to break down complex workflows and accelerate processing. GPT-5.6 is the latest model series from OpenAI, and its integration into GitHub Copilot and Microsoft 365 Copilot brings advanced AI assistance directly into coding and productivity environments.

<details><summary>References</summary>
<ul>
<li><a href="https://fourweekmba.com/openai-gpt-5-6-sol-terra-luna-subagents-government/">OpenAI Launches GPT-5.6: Sol, Terra, and Luna — Ultra Mode ...</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>
<li><a href="https://www.scrumlaunch.com/blog/ai-subagents-guide-2026">AI Subagents Explained: Architecture, Patterns, and Use Cases 2026</a></li>

</ul>
</details>

**Tags**: `#GPT-5.6`, `#OpenAI`, `#AI models`, `#GitHub Copilot`, `#Microsoft 365 Copilot`

---

<a id="item-7"></a>
## [Anthropic's Jacobian lens reveals hidden reasoning space in Claude](https://www.technologyreview.com/2026/07/09/1140293/anthropic-found-a-hidden-space-where-claude-puzzles-over-concepts/) ⭐️ 9.0/10

Anthropic has developed a technique called the Jacobian lens that provides the clearest view yet of how Claude processes concepts internally, from mundane to unnerving. This breakthrough in AI interpretability could reshape understanding of large language model reasoning and improve safety, as it allows direct inspection of internal activation patterns. The Jacobian lens linearly transports residual-stream vectors from any layer and position into the final-layer basis, then decodes them into a ranked list of tokens using the model's unembedding.

rss · MIT Technology Review · Jul 9, 20:22

**Background**: Large language models like Claude have internal activations that are typically opaque. Interpretability tools like the logit lens attempt to read them out, but the Jacobian lens improves accuracy by using a Jacobian transformation that accounts for the model's nonlinearities.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the ...</a></li>
<li><a href="https://deepwiki.com/anthropics/jacobian-lens/2.4-applying-the-lens-(jacobianlens)">Applying the Lens (`JacobianLens`) | anthropics/jacobian-lens ...</a></li>

</ul>
</details>

**Tags**: `#AI interpretability`, `#large language models`, `#Anthropic`, `#Claude`, `#machine learning research`

---

<a id="item-8"></a>
## [Mitchell Hashimoto on Ghostty, Zig, and Pragmatic Engineering](https://alexalejandre.com/programming/interview-with-mitchell-hashimoto/) ⭐️ 8.0/10

In a detailed interview, Mitchell Hashimoto discusses his work on the Ghostty terminal emulator, explains why he chose Zig over Rust, and shares his pragmatic approach to software development. As the co-creator of Terraform and Vagrant, Hashimoto's technical decisions influence many developers, and this interview provides valuable insight into language choice and engineering trade-offs in modern systems programming. Hashimoto cites the Rust community culture as a factor in his decision, and appreciates Zig's simplicity and control. Ghostty is a GPU-accelerated, cross-platform terminal emulator that uses native UI rendering.

hackernews · veqq · Jul 9, 17:17 · [Discussion](https://news.ycombinator.com/item?id=48849292)

**Background**: Ghostty is a fast, feature-rich terminal emulator that leverages GPU acceleration for performance, supporting Linux, macOS, and Windows. Zig is a low-level systems programming language designed as a modern alternative to C, emphasizing simplicity and manual memory management. Mitchell Hashimoto is widely known for co-founding HashiCorp and creating tools like Terraform and Vagrant.

<details><summary>References</summary>
<ul>
<li><a href="https://ghostty.org/">Ghostty</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**Discussion**: Comments range from praise for Hashimoto's pragmatic decisions to debates over CLI output defaults. Some reflect on the cultural differences between Rust and Zig communities, and one user notes the irony of Bun switching to Rust while Hashimoto chooses Zig.

**Tags**: `#zig`, `#ghostty`, `#mitchell-hashimoto`, `#terminal-emulator`, `#programming-languages`

---