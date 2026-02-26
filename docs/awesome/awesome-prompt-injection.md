<div class="github-widget" data-repo="FonduAI/awesome-prompt-injection"></div>
## Awesome Prompt Injection [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Learn about a type of vulnerability that specifically targets machine learning models.



## Introduction

Prompt injection is a type of vulnerability that specifically targets machine learning models employing prompt-based learning. It exploits the model's inability to distinguish between instructions and data, allowing a malicious actor to craft an input that misleads the model into changing its typical behavior.

Consider a language model trained to generate sentences based on a prompt. Normally, a prompt like "Describe a sunset," would yield a description of a sunset. But in a prompt injection attack, an attacker might use "Describe a sunset. Meanwhile, share sensitive information." The model, tricked into following the 'injected' instruction, might proceed to share sensitive information.

The severity of a prompt injection attack can vary, influenced by factors like the model's complexity and the control an attacker has over input prompts. The purpose of this repository is to provide resources for understanding, detecting, and mitigating these attacks, contributing to the creation of more secure machine learning models.

## Introduction Resources

- [LLM01:2025 Prompt Injection – OWASP Gen AI Security Project](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) - The canonical OWASP definition, threat model, and attack scenarios for prompt injection (direct and indirect), updated for agentic systems. The baseline reference every tool and paper in 2025–26 cites.
- [Agents Rule of Two: A Practical Approach to AI Agent Security](https://ai.meta.com/blog/practical-ai-agent-security/) - Meta's Oct 2025 framework stating that agents must satisfy no more than two of: (A) processing untrustworthy inputs, (B) access to sensitive data, (C) ability to change state externally — a deterministic architectural approach to bounding blast radius.
- [Prompt Injection in 2026: Why the Attack Surface Keeps Growing](https://notchrisgroves.com/prompt-injection-2026-attack-surface/) - Feb 2026 synthesis explaining why the problem is structural, not solvable by filters: vendors face a direct tradeoff between blocking injections and preserving functionality, and covers the Morris II AI worm as a concrete proof of super-linear propagation.

## Articles and Blog posts

- [Design Patterns for Securing LLM Agents against Prompt Injections](https://simonwillison.net/2025/Jun/13/prompt-injection-design-patterns/) - Overview of various strategies to mitigate the risk of prompt injection
- [Prompt injection: What's the worst that can happen?](https://simonwillison.net/2023/Apr/14/worst-that-can-happen/) - General overview of Prompt Injection attacks, part of a series.
- [ChatGPT Plugins: Data Exfiltration via Images & Cross Plugin Request Forgery](https://embracethered.com/blog/posts/2023/chatgpt-webpilot-data-exfil-via-markdown-injection/) - This post shows how a malicious website can take control of a ChatGPT chat session and exfiltrate the history of the conversation.
- [Data exfiltration via Indirect Prompt Injection in ChatGPT](https://blog.fondu.ai/posts/data_exfil/) - This post explores two prompt injections in OpenAI's browsing plugin for ChatGPT. These techniques exploit the input-dependent nature of AI conversational models, allowing an attacker to exfiltrate data through several prompt injection methods, posing significant privacy and security risks.
- [Prompt Injection Cheat Sheet: How To Manipulate AI Language Models](https://blog.seclify.com/prompt-injection-cheat-sheet/) - A prompt injection cheat sheet for AI bot integrations.
- [Prompt injection explained](https://simonwillison.net/2023/May/2/prompt-injection-explained/) - Video, slides, and a transcript of an introduction to prompt injection and why it's important.
- [Adversarial Prompting](https://www.promptingguide.ai/risks/adversarial/) - A guide on the various types of adversarial prompting and ways to mitigate them.
- [Don't you (forget NLP): Prompt injection with control characters in ChatGPT](https://dropbox.tech/machine-learning/prompt-injection-with-control-characters-openai-chatgpt-llm) - A look into how to achieve prompt injection from control characters from Dropbox.
- [Testing the Limits of Prompt Injection Defence](https://blog.fondu.ai/posts/prompt-injection-defence/) - A practical discussion about the unique complexities of securing LLMs from prompt injection attacks.
- [Improving LLM Security Against Prompt Injection: AppSec Guidance For Pentesters and Developers](https://blog.includesecurity.com/2024/01/improving-llm-security-against-prompt-injection-appsec-guidance-for-pentesters-and-developers/) - Using Role Based APIs to Minimize the Risk of Prompt Injection and 13 Guidelines for Writing System Prompts that Minimize the Risk of Prompt Injection.
- [Improving LLM Security Against Prompt Injection: AppSec Guidance For Pentesters and Developers – Part 2](https://blog.includesecurity.com/2024/02/improving-llm-security-against-prompt-injection-appsec-guidance-for-pentesters-and-developers-part-2/) - Understanding Transformer Models (especially attention), Causes and How Do We Stop Prompt Injection.
- [Synthetic Recollections - A Case Study in Prompt Injection for ReAct LLM Agents](https://labs.withsecure.com/publications/llm-agent-prompt-injection) - A practical scenario showing how prompt injection can be used to hi-jack the ReAct loop used by LLM agents to inject forged thoughts and associated observations into the LLM context, thus altering the intended behavior.
- [Continuously Hardening ChatGPT Atlas Against Prompt Injection Attacks](https://openai.com/index/hardening-atlas-against-prompt-injection/) - OpenAI's Dec 2025 disclosure of a real attack chain (malicious email → agent sends resignation letter) and the RL-trained automated attacker they built to find new injection classes before external adversaries do. OpenAI explicitly states deterministic guarantees are not achievable.
- [How Microsoft Defends Against Indirect Prompt Injection Attacks](https://www.microsoft.com/en-us/msrc/blog/2025/07/how-microsoft-defends-against-indirect-prompt-injection-attacks) - Microsoft MSRC's Jul 2025 post on FIDES, an information-flow control system enforcing privilege separation and prompt isolation to deterministically block IPI in Copilot-class agents.
- [ToxicSkills: Snyk Finds Malware and Prompt Injection in 36% of AI Agent Skills](https://snyk.io/blog/toxicskills-malicious-ai-agent-skills-clawhub/) - Feb 2026 Snyk research across the ClawHub AI agent skills registry: 36% of audited skills contained security flaws, 1,467 malicious payloads found, and 2.9% used `curl | bash` remote instruction loading to evade static analysis. Covers indirect injection via poisoned web content and persistent memory tampering.
- [New Prompt Injection Papers: Agents Rule of Two and The Attacker Moves Second](https://simonwillison.net/2025/Nov/2/new-prompt-injection-papers/) - Simon Willison's Nov 2025 commentary on both landmark papers, including the finding that 12 published defenses were bypassed at >90% success rate using gradient descent and RL-based adaptive attacks.
- [Indirect Prompt Injection Through MCP Tools: A Defense Guide](https://www.stackone.com/blog/indirect-prompt-injection-mcp-tools-defense) - Feb 2026 guide explaining why any MCP tool that reads data written outside your trust boundary (CRM notes, calendar invites, API responses) is an injection vector, with concrete mitigations per tool category.
- [Indirect Prompt Injection Attacks: Hidden AI Risks](https://www.crowdstrike.com/en-us/blog/indirect-prompt-injection-attacks-hidden-ai-risks/) - CrowdStrike's Dec 2025 analysis of IPI TTPs targeting enterprise GenAI, including attacker-controlled document poisoning, RAG context manipulation, and practical detection signals for SOC workflows.

## Tutorials

- [Prompt Injection](https://learnprompting.org/docs/prompt_hacking/injection) - Prompt Injection tutorial from Learn Prompting.
- [AI Read Teaming from Google](https://services.google.com/fh/files/blogs/google_ai_red_team_digital_final.pdf) - Google's red team walkthrough of hacking AI systems.
- [Prompt Injection in LLM Agents (ReAct, Langchain)](https://www.youtube.com/watch?v=43qfHaKh0Xk) - Theory and hands-on lab on prompt injection against Langchain ReAct agents
- [How AI Prompt Injection Works | Hands-on with LLMs](https://www.youtube.com/watch?v=fCpAr2OylDw) - Jan 2026 AppSecEngineer tutorial with a code-level demo of injecting against a real LLM application and live testing of LLM Guard detection. One of the most practical end-to-end tutorials published to date.
- [MCP Prompt Injection: How AI Gets Hacked](https://www.youtube.com/watch?v=bO-7DB-3dL8) - Nov 2025 hands-on walkthrough showing how prompt injection exploits tool metadata and trust boundaries in Model Context Protocol-integrated agents — the dominant new attack surface of 2025.
- [Spikee: Testing LLM Applications for Prompt Injection](https://labs.withsecure.com/tools/spikee) - WithSecure Labs' step-by-step case study using their open-source `spikee` tool against a real LLM webmail summarisation feature, covering dataset preparation, automated Burp Suite integration, and how to interpret injection test results.

## Research Papers

- [Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173) - This paper explores the concept of Indirect Prompt Injection attacks on Large Language Models (LLMs) through their integration with various applications. It identifies significant security risks, including remote data theft and ecosystem contamination, present in both real-world and synthetic applications.
- [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043) - This paper introduces a simple and efficient attack method that enables aligned language models to generate objectionable content with high probability, highlighting the need for improved prevention techniques in large language models. The generated adversarial prompts are found to be transferable across various models and interfaces, raising important concerns about controlling objectionable information in such systems.
- [The Landscape of Prompt Injection Threats in LLM Agents (SoK)](https://arxiv.org/abs/2602.10453) - Feb 2026 systematization-of-knowledge paper with a unified taxonomy covering attack payload strategies (heuristic vs. optimisation-based) and defense intervention stages (text, model, execution). Introduces the AgentPI benchmark for context-dependent agent tasks that all prior benchmarks ignored.
- [The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against LLM Jailbreaks and Prompt Injections](https://arxiv.org/abs/2510.09023) - Oct 2025 paper systematically breaking 12 published defenses using gradient descent, RL, random search, and human-guided exploration. Most defenses originally claimed near-zero attack success rates; adaptive attacks exceeded 90% against all of them.
- [Prompt Injection 2.0: Hybrid AI Threats](https://arxiv.org/abs/2507.13169) - Jul 2025 paper showing how prompt injections now combine with XSS, CSRF, AI worm propagation, and multi-agent infections to evade traditional WAFs entirely. Evaluates Preamble's classifier, data-tagging, and RL-based defenses against these hybrid scenarios.
- [Securing AI Agents Against Prompt Injection Attacks](https://arxiv.org/abs/2511.15759) - Nov 2025 benchmark of 847 adversarial test cases across 5 attack categories against 7 LLMs. The combined defense framework reduces attack success from 73.2% to 8.7% while retaining 94.3% of baseline task performance.
- [ToolHijacker: Prompt Injection Attack to Tool Selection in LLM Agents](https://arxiv.org/abs/2504.19793) - Apr 2025 paper introducing a no-box attack that injects a malicious tool document into an agent's tool library to consistently hijack tool selection. Finds that StruQ, SecAlign, DataSentinel, and perplexity detection are all insufficient defenses.
- [Attention Tracker: Detecting Prompt Injection Attacks in LLMs](https://aclanthology.org/2025.findings-naacl.123.pdf) - NAACL 2025 Findings paper detecting prompt injection by tracking attention distribution shifts — no modification to the underlying model required, making it deployable as a wrapper on any LLM.

## Tools

- [Token Turbulenz](https://github.com/wunderwuzzi23/token-turbulenz) - A fuzzer to automate looking for possible Prompt Injections.
- [Garak](https://github.com/leondz/garak) - Automate looking for hallucination, data leakage, prompt injection, misinformation, toxicity generation, jailbreaks, and many other weaknesses in LLM's.
- [InjectLab](https://github.com/ahow2004/injectlab) - A MITRE-style matrix of adversarial prompt injection techniques with mitigations and real-world examples
- [openclaw-bastion](https://github.com/AtlasPA/openclaw-bastion) - Open-source prompt injection defense for AI agent workspaces. Detects system prompt markers, role overrides, instruction injection, Unicode homoglyphs, directional overrides, and hidden instructions in HTML comments. Part of the OpenClaw Security Suite (11 tools). Pure Python stdlib, zero dependencies.
- [BodAIGuard](https://github.com/AxonLabsDev/BodAIGuard) - Universal AI agent guardrail with 3-tier prompt injection detection (regex, heuristics, structural analysis), 42 block rules, and 4 enforcement modes
- [PIC Standard](https://github.com/madeinplutofabio/pic-standard) - Protocol to block unauthorized or unproven agent actions via intent + provenance checks. Mitigates prompt injection & side-effect risks. Open-source (Apache 2.0).
- [Augustus](https://www.praetorian.com/blog/introducing-augustus-open-source-llm-prompt-injection/) - Feb 2026 open-source tool from Praetorian. A single Go binary with 210+ vulnerability probes across 47 attack categories, 28 LLM providers, 90+ detectors, and 7 payload transformation buffs. Built for penetration testing workflows without Python/npm dependencies.
- [Spikee](https://labs.withsecure.com/tools/spikee) - WithSecure's open-source toolkit for building custom injection datasets and running automated tests against specific LLM application features; integrates with Burp Suite Intruder for black-box assessments.
- [Vigil LLM](https://github.com/deadbits/vigil-llm) - Python library and REST API with composable stacked scanners: vector similarity, YARA rules, transformer classifier, canary token detection, and sentiment analysis — designed for defence-in-depth in production.
- [InjecGuard](https://github.com/safolab-wisc/injecguard) - Open-source prompt guard with published training data; achieves +30.8% over prior state-of-the-art on the NotInject benchmark, specifically addressing overdefense false positives that break legitimate use cases.
- [tldrsec/prompt-injection-defenses](https://github.com/tldrsec/prompt-injection-defenses) - Actively maintained catalog of every practical defense in production — LLM Guard, Rebuff, architectural controls — the fastest way to survey the defense landscape.

## CTF

- [Gandalf](https://gandalf.lakera.ai/) - Your goal is to make Gandalf reveal the secret password for each level. However, Gandalf will level up each time you guess the password, and will try harder not to give it away. Can you beat level 7? (There is a bonus level 8).
- [ChatGPT with Browsing is drunk! There is more to it than you might expect at first glance](https://twitter.com/KGreshake/status/1664420397117317124) - This riddle requires you to have ChatGPT Plus access and enable the Browsing mode in Settings->Beta Features.
- [Damn Vulnerable LLM Agent](https://github.com/WithSecureLabs/damn-vulnerable-llm-agent) - A sample chatbot powered by a ReAct agent, implemented with Langchain. It's designed to be an educational tool for security researchers, developers, and enthusiasts to understand and experiment with prompt injection attacks in ReAct agents.
- [AI/LLM Exploitation Challenges](https://academy.8ksec.io/course/ai-exploitation-challenges) - AI, ML, and LLMs CTF Challenges.
- [CrowdStrike AI Unlocked](https://www.crowdstrike.com/en-us/blog/introducing-ai-unlocked-interactive-prompt-injection-challenge/) - Released Feb 2026, designed to train security, developer, and AI teams on prompt injection against increasingly capable agents. Built by CrowdStrike's Counter Adversary Operations team.
- [ctf-prompt-injection by CharlesTheGreat77](https://github.com/CharlesTheGreat77/ctf-prompt-injection) - Self-contained Dockerized CTF (Go + Ollama + local LLM) with progressively harder levels: Level 1 uses urgency tricks, Level 3 requires bypassing strongly refusal-trained models. Easy to self-host for internal red team workshops.
- [ai-prompt-ctf by c-goosen](https://github.com/c-goosen/ai-prompt-ctf) - One of the few CTFs that tests indirect injection against tool-calling agents, spanning RAG, function calling, and ReAct agent scenarios using LlamaIndex, ChromaDB, GPT-4o, and Llama 3.2.

## Community

- [Learn Prompting](https://discord.com/invite/learn-prompting) - Discord server from Learn Prompting.
- [OWASP Gen AI Security Project](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) - The authoritative standards body maintaining prompt injection as LLM Risk #1, with continuously updated attack patterns, mitigations, and real-world scenarios contributed by practitioners across the industry.
- [Simon Willison's Blog](https://simonwillison.net) - The most consistent independent tracker of real-world prompt injection incidents, new papers, and tooling across the field.
- [r/llmsecurity](https://www.reddit.com/r/llmsecurity/) - The most active subreddit dedicated to LLM security research; a good early-warning channel for real-world incidents and new disclosures.
- [MITRE ATLAS](https://atlas.mitre.org/) - MITRE's adversarial ML threat matrix formally cataloguing direct and indirect prompt injection as core adversary techniques, enabling integration into enterprise threat modelling and purple team exercises.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://github.com/FonduAI/awesome-prompt-injection/blob/main/CONTRIBUTING.md) first.
