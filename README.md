# Y.PENG · AI Skills & Research Tools

> AI Skills for catalyst R&D, literature search, agent tooling, and self-hosted solutions.

About me — I work on electrocatalyst R&D for hydrogen energy (PEMFC/WE). In my spare time I vibe-code small research tools and tune my AI agents — skills, plugins, etc.

---

## 🧩 Skills

| Skill | Description | GitHub | Version |
|---|---|---|---|
| **catalyst-search-skill** | Bilingual catalysis literature search: retrieves literature from ScienceDirect/arXiv/OpenAlex/Google Scholar and outputs a structured literature matrix (GB/T 7714 citations, prioritizing high-IF, highly-cited works from the last 5–10 years). | [repo](https://github.com/ANDYPENG09/catalyst-search-skill) | v1.0.x |
| **catalyst-design-skill** | Bilingual catalyst design guidance: layered, traceable methodology for HER/OER/ORR/PEMWE electrocatalysis, with literature sources, confidence levels and validation paths. | [repo](https://github.com/ANDYPENG09/catalyst-design-skill) | v1.0.x |
| **opencode-responses-bridge-skill** | Zero-dependency local proxy adapting OpenAI Chat Completions ↔ Responses API (streaming SSE, tool calls, reasoning, multimodal), letting any OpenAI-compatible client use Responses-API-only models such as OpenCode Go gpt-5.6-luna. | [repo](https://github.com/ANDYPENG09/opencode-responses-bridge-skill) | v1.2.0 |

## 🔌 Plugins & Tools

| Category | Project | Description | GitHub | Version |
|---|---|---|---|---|
| Hermes | **hermes-gpt-light-theme** | Clean light-mode dashboard theme for Hermes Agent, inspired by the OpenAI ChatGPT / Codex interface — white canvas, high-contrast text, green accent, fixed Analytics token colors. | [repo](https://github.com/ANDYPENG09/hermes-gpt-light-theme) | v1.0 |
| Hermes | **hermes-cache-hit-rate** | Lightweight dashboard plugin for Hermes Agent showing the token cache hit rate on the Analytics page — cache read / uncached input / output breakdown, 7-day trend, theme-aware, zero token cost. | [repo](https://github.com/ANDYPENG09/hermes-cache-hit-rate) | v1.0 |
| Zotero | **zotero-ima-sync** | Zotero plugin: syncs items with PDF attachments to Tencent ima knowledge base, building a searchable literature RAG library (selected items / collection / all; OpenAPI + MCP dual mode; compatible with Zotero 7/8/9). | [repo](https://github.com/ANDYPENG09/zotero-ima-sync) | v0.0.1 |
| XRD | **XRD-FileConventor** | Standalone offline XRD powder-diffraction file converter (Rigaku / Bruker / Jade-MDI / generic text), MIT licensed. | [repo](https://github.com/ANDYPENG09/XRD-FileConventor) | v1.x |
| XRD | **xrd-toolkit** | Showcase of offline, single-file, zero-dependency HTML tools for powder XRD data analysis. | [repo](https://github.com/ANDYPENG09/xrd-toolkit) · [live](https://andypeng09.github.io/xrd-toolkit/) | v1.0 |

## 📚 Solutions & Guides

| Project | Description | GitHub | Version |
|---|---|---|---|
| **hermes-multi-task-concurrency-solution** | Fixes replies silently dropped under concurrent Hermes sessions: forces the non-thread-safe nemo-relay scope stack into Noop mode at the root. Deployment-agnostic (local pip, Docker Compose, NAS app-store), with a verified stress test and rollback steps. | [repo](https://github.com/ANDYPENG09/hermes-multi-task-concurrency-solution) | v1.0 |

**Upstream reports:**
- [Hermes Agent #81227 — desktop turns aborted with a misleading "session storage could not be written" error under compression-lock contention; conversations appear to vanish after disconnects (diagnosis + workaround + fix suggestions)](https://github.com/NousResearch/hermes-agent/issues/81227)
- [Hermes Agent #81286 — Two frontends (Web Dashboard + Desktop) on one session: the last to type captures the session, the other freezes until it types](https://github.com/NousResearch/hermes-agent/issues/81286)

---

*Maintained by Y.PENG · All public skills licensed MIT unless noted.*
