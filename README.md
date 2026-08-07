# Hey, I'm Vinen 👋

<a href="https://x.com/Vinen77">X @Vinen</a> · <a href="https://www.xiaohongshu.com/user/profile/60e658c80000000001009ac9">rednote</a>

AI agent engineer passionate about building tools helping people.

---

## pi-discuss-mode

[**pi-discuss-mode**](https://github.com/zwrong/pi-discuss-mode) ⭐ 12 — A read-only discussion mode for Pi Coding Agent: discuss code safely, without changing a single line.

[Pi Package](https://pi.dev/packages/pi-discuss-mode?name=pi-discuss-mode) · **200+ monthly downloads** · [Demo video](https://github.com/user-attachments/assets/0a8cdc37-6413-4d6e-88ec-e0adec7fc036)

- **Two-layer safety**: a `before_agent_start` hook injects the discussion-mode system prompt, while a `tool_call` interceptor acts as a real-time safety net — destructive operations are blocked even if the model ignores the prompt.
- **One-command install**: published to the Pi package registry, `pi install pi-discuss-mode`.

---

## Open Source Contributions

### Vibe Trading

[**Vibe-Trading**](https://github.com/HKUDS/Vibe-Trading) ⭐ 30.0K — Your personal AI trading agent. Multi-agent architecture for quantitative research, backtesting, risk management, and auto-trading — all via natural language.

**My contributions:**
- [`feat(cli):` add `vibe-trading resume <session-id>` and exit session-id display](https://github.com/HKUDS/Vibe-Trading/pull/218) — Enables users to resume interrupted trading sessions by ID, plus shows the session ID on exit for easy recovery.
- [`feat(agent):` complete trace.jsonl overhaul — zero truncation, message entries, tool result offload](https://github.com/HKUDS/Vibe-Trading/pull/206) — Rewrote the agent tracing system to eliminate truncation, properly serialize conversation messages, and offload large tool results.
- [`fix(loop):` enrich trace entries with call_id for tool-call correlation](https://github.com/HKUDS/Vibe-Trading/pull/168) — Added `call_id` to trace entries so tool calls and their results can be reliably correlated in logs and replay.

### Kaku

[**Kaku**](https://github.com/tw93/Kaku) ⭐ 5.7K — A fast, out-of-the-box terminal built for AI coding.

**My contributions:**
- [`feat(gui):` close tabs with `Backspace` in Tab Navigator](https://github.com/tw93/Kaku/pull/499) — Added Backspace-to-close in the built-in Tab Navigator: closes the selected tab while keeping the navigator open, with safe handling for the last remaining tab and confirmation for tabs with running processes.

### Paper2Slides

[**Paper2Slides**](https://github.com/HKUDS/Paper2Slides) ⭐ 3.8K — Convert research papers, reports, and documents into professional slides and posters with one command. Supports PDF, Word, Excel, PowerPoint, Markdown.

**My contributions:**
- [Bug: Dependency resolution failed & version conflict with fastapi/anyio during installation](https://github.com/HKUDS/Paper2Slides/issues/1) — Identified and reported a critical install-time dependency conflict.
- [Docs: Incorrect mapping of "gemini-3-pro-image-preview" to "Nano Banana" in README](https://github.com/HKUDS/Paper2Slides/issues/2) — Caught a model name mapping error in the documentation.

---

## Also Building

- [**DASC7606-Deep-Learning-Review**](https://github.com/zwrong/DASC7606-Deep-Learning-Review) ⭐ 26 — Comprehensive review notes for HKU DASC7606 Deep Learning course. Covers core concepts, architectures, and exam prep with rich illustrations.
- [**Calendar-Agent**](https://github.com/zwrong/Calendar-Agent) ⭐ 3 — AI Calendar Agent powered by DeepSeek API + CalDAV. Natural language CRUD on Apple Calendar, supports Chinese & English.
- [**iCalendar**](https://github.com/zwrong/iCalendar) ⭐ 2 — Calendar MCP server for iCloud, letting AI agents read and manage your calendar seamlessly.
- [**typora-opencode-theme**](https://github.com/zwrong/typora-opencode-theme) ⭐ 1 — A dark Typora theme inspired by OpenCode with GitHub Night code highlighting.
