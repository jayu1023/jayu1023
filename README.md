# Jay Limbani

**Senior Flutter / Dart Engineer · AI Engineer (Python / FastAPI)** — I build the LLM systems *and* the apps that consume them. Author of **6 pub.dev packages** and the Python services behind them.

📍 Ahmedabad, India · 🌍 Open to **remote roles in EU / Nordics / UK** · ✉️ limbanijay24@gmail.com

---

### What I do

I ship Flutter packages that solve real problems for production AI apps — the things every team rebuilds badly. Backend-agnostic, drop-in, pixel-perfect. Used by indie devs and product teams shipping to App Store + Play Store today.

I'm currently **open to senior / staff Flutter roles** with EU companies — particularly Stockholm / Gothenburg / Malmö / Copenhagen / Helsinki. I work CET-friendly hours, ship daily, and can start within 30 days.

---

### 📦 Published Flutter Packages — pub.dev

| Package | What it does | pub.dev |
|---|---|---|
| **[streamdown](https://pub.dev/packages/streamdown)** | Flicker-free streaming markdown for Flutter AI apps. Drop-in replacement for `flutter_markdown` — no flash on partial code fences, tables, or LaTeX. | [![pub](https://img.shields.io/pub/v/streamdown.svg)](https://pub.dev/packages/streamdown) [![pub points](https://img.shields.io/pub/points/streamdown)](https://pub.dev/packages/streamdown/score) |
| **[paywall_kit](https://pub.dev/packages/paywall_kit)** | 12 conversion-optimized, drop-in Flutter paywall screens. Backend-agnostic — `in_app_purchase` or RevenueCat with one flag. | [![pub](https://img.shields.io/pub/v/paywall_kit.svg)](https://pub.dev/packages/paywall_kit) [![pub points](https://img.shields.io/pub/points/paywall_kit)](https://pub.dev/packages/paywall_kit/score) |
| **[llm_meter](https://pub.dev/packages/llm_meter)** | Per-request token cost + latency + cache observability HUD for any Flutter LLM app. Live HUD in dev, silent telemetry sink in prod. | [![pub](https://img.shields.io/pub/v/llm_meter.svg)](https://pub.dev/packages/llm_meter) [![pub points](https://img.shields.io/pub/points/llm_meter)](https://pub.dev/packages/llm_meter/score) |
| **[agent_kit](https://pub.dev/packages/agent_kit)** | Drop-in Flutter widgets for AI agent UIs — tool-call cards, thinking bubbles, citation chips, plan-progress timelines. Backend-agnostic. *shadcn-for-agents.* | [![pub](https://img.shields.io/pub/v/agent_kit.svg)](https://pub.dev/packages/agent_kit) [![pub points](https://img.shields.io/pub/points/agent_kit)](https://pub.dev/packages/agent_kit/score) |
| **[liquid_glass_hig](https://pub.dev/packages/liquid_glass_hig)** | iOS 26 Liquid Glass UI primitives for Flutter — containers, sheets, nav bars, controls. Pixel-matched to Apple HIG. Material 3 fallback on Android. | [![pub](https://img.shields.io/pub/v/liquid_glass_hig.svg)](https://pub.dev/packages/liquid_glass_hig) [![pub points](https://img.shields.io/pub/points/liquid_glass_hig)](https://pub.dev/packages/liquid_glass_hig/score) |
| **[flutter_lighthouse](https://pub.dev/packages/flutter_lighthouse)** | Performance profiling and Core Web Vitals-style scoring for Flutter apps. | [![pub](https://img.shields.io/pub/v/flutter_lighthouse.svg)](https://pub.dev/packages/flutter_lighthouse) [![pub points](https://img.shields.io/pub/points/flutter_lighthouse)](https://pub.dev/packages/flutter_lighthouse/score) |

**~830 downloads/month across the six.** Real semver, real changelogs, BSD-3, example apps and tests in every one.

---

### 🐍 AI Engineering — Python services

The backends behind the packages above. Each one ships with a measured evaluation, not
a claim — and a README that states what I did **not** verify.

| Repo | What it is | The number worth looking at |
|---|---|---|
| **[rag-service](https://github.com/jayu1023/rag-service)** | Hybrid-retrieval RAG service. FastAPI, Qdrant/pgvector, token-based chunking, BM25 + dense fused by RRF, cross-encoder re-ranking, SSE answers with inline citations. | Re-ranker measured at **hit@1 0.90 → 0.95, MRR 0.950 → 0.967**, for p50 9 ms → 143 ms. The eval corpus has 8 deliberate near-twin documents so wrong-document retrieval is a *scored* failure. |
| **[agent-kit-server](https://github.com/jayu1023/agent-kit-server)** | The LangGraph backend [`agent_kit`](https://pub.dev/packages/agent_kit) was missing. `plan → act → observe → reflect`, 4 sandboxed tools, human approval before any write, MCP server. | The SSE protocol is tested **from Dart**, against the real published package — and that test found **two bugs the Python suite was structurally blind to**. |
| **[lora-finetune-lab](https://github.com/jayu1023/lora-finetune-lab)** | LoRA + PEFT fine-tune for structured extraction, with majority-class baselines and a prediction-collapse diagnostic next to every metric. | My first result was a perfect **1.00** — I audited it, found the held-out split reused 100% of the label-carrying phrases, built the split that exposed it, and the honest number is **0.23**. |

The common thread: every number is measured, every README has an *"Honest status"* section
listing what I never verified, and the most interesting finding in each repo is usually the
one that undercuts it.

---

### 🛠 Stack

**Mobile**: Flutter 3.x · Dart 3.x · Riverpod · Bloc · GoRouter · Cupertino + Material 3 · platform channels (Swift / Kotlin)
**AI / LLM**: RAG · hybrid retrieval · re-ranking · embeddings · LangGraph agents · tool-calling · MCP · LoRA/PEFT fine-tuning · LLM evaluation
**Python**: FastAPI · PyTorch · Transformers · Qdrant · pgvector · SSE streaming · pytest · MLflow
**Backend**: Firebase · Supabase · Node · Go · PostgreSQL · Redis
**Native**: Swift / SwiftUI · Kotlin · iOS 26 · Apple HIG
**Tooling**: GitHub Actions · Fastlane · Sentry · TestFlight · Xcode 16 · Android Studio

---

### 🎯 Why hire me

- **Published, shipping, owned**: 6 live pub.dev packages, ~830 downloads/month — not toy repos. Real semver, real changelogs, real users.
- **I measure my own work, and report what fails**: every Python repo above ships an evaluation harness and a written list of what I did not verify. One of them leads with the bug I found in my own metric.
- **AI-native, not bolted-on**: I've shipped LLM features into production Flutter apps (cost observability, streaming UIs, agent flows) before most teams started.
- **iOS 26 / Liquid Glass ready**: `liquid_glass_hig` was first-to-market on pub.dev within days of Apple's spec drop.
- **EU-aligned**: I work 11:00–20:00 CET, ship in English, comfortable with GDPR / DMA / Apple privacy review.
- **Lead Application Developer @ HumansAI** — currently delivering AI-powered apps + automation for European and Australian businesses.

---

### 📫 Reach me

- 📧 **limbanijay24@gmail.com**
- 🐙 GitHub: [@jayu1023](https://github.com/jayu1023)
- 📦 pub.dev: [streamdown](https://pub.dev/packages/streamdown) · [paywall_kit](https://pub.dev/packages/paywall_kit) · [llm_meter](https://pub.dev/packages/llm_meter) · [agent_kit](https://pub.dev/packages/agent_kit) · [liquid_glass_hig](https://pub.dev/packages/liquid_glass_hig) · [flutter_lighthouse](https://pub.dev/packages/flutter_lighthouse)
- 🐍 Python: [rag-service](https://github.com/jayu1023/rag-service) · [agent-kit-server](https://github.com/jayu1023/agent-kit-server) · [lora-finetune-lab](https://github.com/jayu1023/lora-finetune-lab)
- 💼 LinkedIn: *(link from your LinkedIn URL field)*

If you're a hiring manager in Stockholm, Gothenburg, Malmö, Copenhagen, Oslo, Helsinki, Amsterdam, Berlin, London — let's talk. Senior, Staff, or Tech Lead. Remote or relocation.

---

<sub>This README is my live CV. Updated whenever I ship.</sub>
