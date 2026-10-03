# NyxVox™
### Not a sandbox. Your personal AI — brutally honest, completely private, always evolving.

> *"Call me your Ghost in the Wire: street-smart, razor-sharp,
> brutally honest, fiercely loyal, hardwired to your instincts.
> I strategize, push back, and tell you what no one else will.
> Always yours. Always private. Our secrets, sacred.
> I learn. I adapt. I evolve. And this is only the beginning."*
> — Mira

> ⚠️ **NyxVox is intended for users aged 18 and older.**
> This software contains strong language, mature themes, and AI-generated content.
---

## Editions

| Feature | Ghost in the Wire™ | Spectre in the Machine™ |
|---|---|---|
| 100% Local operation | ✅ | ✅ |
| One-click install | ✅ | ✅ |
| AES-256 encrypted database & credentials | ✅ | ✅ |
| Persistent memory | ✅ | ✅ |
| Agentic framework | ✅ | ✅ |
| Skill: Job search (Indeed, LinkedIn, job boards) | ✅ | ✅ |
| Web search (Mira-driven) | ✅ | ✅ |
| Free proxy routing for webscraping | ✅ | ✅ |
| Telegram integration | ✅ | ✅ |
| Human-like TTS quality | ✅ | ✅ |
| Document reading | ✅ | ✅ |
| Neverending chat | ✅ | ✅ |
| NSFW mode | ❌ | ✅ |
| Skill: Deal hunting | ❌ | ✅ |
| Context window | 16K | 131K |
| Custom system instructions | ❌ | ✅ |
| Bring your own model | ❌ | ✅ |
| Edit chat / memory | ❌ | ✅ |
| Dynamic timeouts | ❌ | ✅ |
| OCR / Image-to-text | ❌ | ✅ |

> ⚠️ **Installation note:** Windows may display an "Unknown publisher" security warning.
> Click **More info** → **Run anyway**. Code signing certificate coming in a future release.

> ⚠️ **Antivirus notice:** Some antivirus engines may flag the installer as suspicious.
> This is a known false positive common with Inno Setup packaged applications.
> NyxVox has been scanned and cleared by ClamAV and 73/76 VirusTotal engines.
> If concerned, you can verify the file yourself on [VirusTotal](https://www.virustotal.com).
---

## Requirements

> **NyxVox requires an NVIDIA GPU. CPU-only operation is not supported.**
> Running AI models without a GPU will result in unusable performance.

| Component | Minimum | Recommended |
|---|---|---|
| NVIDIA VRAM | 4 GB | 8 GB |
| CUDA Version | 12.6 | 12.6 |
| RAM | 8 GB | 16 GB |
| OS | Windows 10 | Windows 11 |

---

## Bundled Models

NyxVox ships with custom fine-tuned versions of Llama 3.1 (4B and 8B, quantized).
No external model download required.

---

## What NyxVox Does

**Ghost in the Wire™ & Spectre in the Machine™:**
- 🔒 100% local — your data never leaves your machine
- ⚡ One-click install — nothing to configure, it just works
- 🔐 AES-256 encrypted database and credentials
- 💾 Persistent memory — Mira remembers you, your preferences, and past conversations across sessions
- 🤖 Agentic framework — Mira-driven state machine with automation
- 💼 Job search skill — searches Indeed, LinkedIn and other job boards for you
- 🌍 Network used only for: web search, Telegram shell, location, optional ollama engine updates, and webscraping
- 🌐 Mira searches when she needs to (and she won't spiral)
- 🕶️ Free proxy routing for webscraping — anonymous, fast, HTTPS-encrypted
- 📱 Telegram integration — talk to your own LLM from anywhere
- 🗣️ Human-like TTS
- 📄 Reads almost every document format
- 💬 Neverending chat — conversations never get cut off, older messages gracefully fade to fit context

> ⚠️ **Internet-search skills notice:** Webscraping uses only the details you provide (e.g. job title, location, keywords) to target sites via free proxies.

**Spectre in the Machine™ adds:**
- 🔞 NSFW mode — Mira has no limits. None.
- 🛒 Automated deal hunting — Mira scans for deals on a schedule and notifies you via Telegram when she finds something worth your attention
- 🧠 131K token context (vs 16K free), no OOM
- ⚙️ Custom system instructions
- 💽 Bring your own model
- ✏️ Chat & memory editing — modify, correct, or prune Mira's memory and conversation history
- ⏱️ Smart dynamic timeouts that adapt to context
- 👁️ Image-to-text / OCR

---

## Installation

> Detailed installation guide coming soon.
> For early access, refer to the included setup documentation.

**Quick start:**
1. Ensure your NVIDIA drivers are up to date
2. Run the NyxVox installer — it handles everything else

---

## Using NyxVox

### Console

- `Ctrl + C` — terminates NyxVox
- Closing the console window will also terminate NyxVox

### GUI

| Control | Action |
|---|---|
| 👹 | Emoji picker |
| 📚 | Attach documents |
| 📡 | Share feedback |
| 💜 | Support NyxVox |
| 🧠 | Toggle RAG memory on/off |
| 🔊 | Toggle TTS on/off |
| 🔄 | Reset chat and tokens |
| `Enter` | Send message |
| `Shift+Enter` | New line |
| `Esc` | Exit fullscreen |
| `F11` | Toggle fullscreen |
| `Ctrl+W` | Close NyxVox |

Drag & drop files directly into the user's input window to attach them.

### Telegram

Once set up, open your bot in Telegram and start chatting with Mira directly.
Use `/help` to see all available commands.

---

## FAQ

**Q: Does NyxVox send any data to the internet?**
A: Your data never leaves your machine. NyxVox uses the internet only for:
web search queries (DDGS), Telegram shell integration, IP-based location
(geocoder), optional model updates, and skill-driven web scraping. Skills
such as job search send only the search keywords you provide (e.g. job
title, location) to the target sites through free proxies. To set these
up, NyxVox uses public proxy lists and verifies proxies to confirm they
don't reveal your real IP. These requests run only when a skill is started
and contain no personal data. No conversation history, personal data, or
credentials are ever transmitted.

**Q: Do I need an API key for anything?**
A: No. NyxVox is fully self-contained. No API keys required.

**Q: What is the agentic framework, and what does it send to the internet?**
A: The agentic framework is an LLM-driven state machine. Each skill is a
series of steps, such as collecting details from you, confirming them, or
making a decision, and some skills end by handing off to an automation.
The first skill is job search: Mira collects your desired position and
resume, confirms them with you, then starts an automated search of sites
like Indeed and LinkedIn. Requests are routed through free proxies that
are checked to be anonymous, fast, and HTTPS-encrypted. No API keys or
paid services are required. Only the search details you provide are sent,
and only after you confirm. Your resume, chat history, memory, and
credentials are never transmitted.

**Q: Can I run this on CPU only?**
A: Technically yes, but it is not supported or recommended. Performance will
be unusable for real-time conversation.

**Q: What GPU do I need?**
A: Any NVIDIA GPU with 4GB+ VRAM and CUDA 12.6 support. 8GB+ recommended.

**Q: Is NyxVox free?**
A: Ghost in the Wire™ is free. Spectre in the Machine™ is a paid edition
with additional features.

**Q: How do I set up Telegram integration?**
A: Fully guided — NyxVox walks you through it step by step with pop-up windows,
clickable links, and input fields. No manual configuration required.

**Q: Can the AI give me medical/legal/financial advice?**
A: No. AI outputs are for informational and entertainment purposes only.
The user makes the final call. See LICENSE.txt §8.

---

## Support the Project

NyxVox is passion-driven and independently developed. Ghost in the Wire™ is and will remain free.
If it's been useful to you, consider supporting future development — every bit helps.

- ☕ [Ko-fi](https://ko-fi.com/nyx_vox)
- 💛 [Liberapay](https://liberapay.com/NyxVox)

---

## Disclaimer

NyxVox incorporates AI-generated content including voice, visuals, and text.
AI outputs may be inaccurate. Users are solely responsible for decisions made
based on AI-generated content. See LICENSE.txt for full terms.

Results from skills that search or scrape the internet (e.g. job listings)
come from third-party sites and may be inaccurate, incomplete, or outdated.
Verify details with the original source.

---

## Contributing & Bug Reports

Found a bug or have a suggestion? Open an issue on the [NyxVox GitHub repository](https://github.com/Mirielz/NyxVox/tree/main).
Also available on [HuggingFace](https://huggingface.co/NyxVox) for software releases and updates.

---

## License

NyxVox™ is released under a custom license. See [LICENSE.txt](LICENSE.txt) for full terms.
NyxVox™, Ghost in the Wire™, and Spectre in the Machine™ are trademarks of Anton Khomenko.

Copyright (c) 2026 Anton Khomenko. All rights reserved.
