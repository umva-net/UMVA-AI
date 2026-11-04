# UMVA AI — Documentation

Comprehensive guide to **UMVA AI** (`umva.net/umva-ai`). This covers the product
overview, key features, model catalog with pricing, how billing works, editor
integration (including the free Zed editor), payment methods, and everything a
developer or user needs to understand and use the platform.

---

## 1. Overview

**UMVA AI** is billed as the **cheapest AI inference & AI-powered coding platform
on the planet**. It lets you bring your own editor — including the free Zed editor
— and connect through a **OpenAI- and Anthropic-compatible API**.

No subscriptions — just **pure pay-as-you-go**. Pay with cards or crypto. No
limits, no commitments.

| Feature | Detail |
| --- | --- |
| **Pricing model** | Pay-as-you-go (no subscription, no minimum) |
| **Starting cost** | Start with just $1 |
| **Editors** | Zed, VS Code, JetBrains, Neovim & more |
| **Context window** | Up to 1M tokens |
| **Text pricing** | From $0.06 per million input tokens |
| **Payments** | Cards & crypto |

---

## 2. Key Features

### Cheapest AI Inference
- Text models start at **$0.06 per million input tokens** — a fraction of competitors.
- No hidden fees, no markup.
- Pay-as-you-go, no subscription, cards & crypto accepted, up to 1M token context.

### Bring Your Own Editor
Connect any AI-capable editor to UMVA AI — always pay-as-you-go:

| Feature | Description |
| --- | --- |
| **Lightning Fast** | Native performance in modern editors like Zed; instant startup, zero lag |
| **AI Agent Ready** | Plan, generate, debug, and refactor code with natural language |
| **Agentic Workflows** | Run multi-step AI agents across files/projects via OpenAI/Anthropic-compatible API |
| **Cross-Platform** | macOS, Windows, and Linux — free Zed editor or your existing IDE |
| **Terminal & Git Built-In** | Editors like Zed ship with integrated terminal + git — complete workflow |
| **No Subscription** | Download a free editor, use UMVA AI pay-as-you-go; a small top-up starts you |
| **Privacy First** | Code stays on your machine; only selected context is sent for AI requests |
| **Open & Extensible** | Works with Zed, VS Code, JetBrains, Neovim, Cursor, any OpenAI-compatible client |

---

## 3. Why Choose UMVA AI?

| Benefit | Detail |
| --- | --- |
| **Lowest Prices** | Text models from $0.06/1M input tokens — a fraction of competitors |
| **No Subscriptions** | Pay only for what you use — no monthly bills, no annual contracts |
| **Cards & Crypto** | Visa, Mastercard, Amex, or crypto (USDT, USDC, BTC, ETH) — no limits |
| **Works With Any Editor** | Zed, VS Code, JetBrains, Neovim, or any OpenAI-compatible tool |
| **Large Context** | Up to 1M token context — process an entire codebase in one request |
| **Every Modality** | Text, image, video, speech-to-text, and text-to-speech models from one API |
| **API Access** | OpenAI- and Anthropic-compatible API from any editor or application |
| **24/7 Support** | WhatsApp, live chat, or ticketing — help with integration & troubleshooting |

### Payment Methods
- **Credit & Debit Cards:** Visa, Mastercard, Amex, Verve
- **Cryptocurrency:** USDT, USDC, BTC, ETH, BNB
- **Bank Transfer:** Direct deposit & wire transfer
- **User Balance:** Pay with your UMVA balance

---

## 4. AI Model Catalog & Pricing

Pay-as-you-go, per-token billing, no subscriptions. Text models are billed **per
million tokens**; image, video, and audio models are billed **per unit** (per
image, per second, per minute, or per million characters).

### Image Generation

| Model | Type | Price | Billing |
| --- | --- | --- | --- |
| **umva-vision** (UMVA Vision) | Image Generation | $0.100000 / image | Per image |

### Text Completion Models

#### UMVA Fast (`umva-fast`) — *RECOMMENDED*
| Property | Value |
| --- | --- |
| Input | $0.0600 / 1M tokens |
| Output | $0.1800 / 1M tokens |
| Context | 1,000,000 tokens |
| Max Output | 384,000 tokens |
| Thinking | Yes |
| Vision | No |
| Tools | Yes |

*Use case:* Cheap fast coding.

#### UMVA Plus (`umva-plus`)
| Property | Value |
| --- | --- |
| Input | $0.2000 / 1M tokens |
| Output | $0.6000 / 1M tokens |
| Context | 1,000,000 tokens |
| Max Output | 384,000 tokens |
| Thinking | Yes |
| Vision | Yes |
| Tools | Yes |

*Use case:* Precise coding.

#### UMVA Pro (`umva-pro`)
| Property | Value |
| --- | --- |
| Input | $0.4400 / 1M tokens |
| Output | $1.3200 / 1M tokens |
| Context | 1,000,000 tokens |
| Max Output | 384,000 tokens |
| Thinking | Yes |
| Vision | No |
| Tools | Yes |

*Use case:* Super intelligence.

---

## 5. How Billing Works

Simple, transparent, fair — no surprises, no hidden fees:

1. **Top Up Your Wallet** — Deposit any amount using credit/debit card or crypto.
   No minimum, no subscription.
2. **Use AI & Get Billed** — Every AI request deducts from your balance based on
   token usage. Real-time cost tracking during streaming.
3. **Replenish Anytime** — Low balance? API returns **402**. Top up and continue
   immediately — no disruption, no re-subscription.

### Why We Are the Cheapest
- No subscription overhead — you pay only for the compute you use
- Transparent per-token and per-unit pricing with no wasted spend
- Direct inference — no middleman markup, no enterprise license fees
- Optimized infrastructure with efficient model serving reduces cost per token
- Set a **safety cap** on your account to prevent runaway costs

---

## 6. Download the Zed Editor

UMVA AI does **not** ship its own self-hosted IDE. It recommends the free,
open-source **Zed editor** — fast and native for macOS, Windows, and Linux.
Install Zed, then point it at UMVA's OpenAI- or Anthropic-compatible endpoints
using your UMVA API key. The editor is **completely free**; you only pay for AI
inference.

Current recommended version: **Zed v1.26.2**.

### Downloads by Platform

| Platform | Architecture | Size | Format |
| --- | --- | --- | --- |
| macOS | Apple Silicon (ARM64) | 84 MB | DMG |
| macOS | Intel (x64) | 92 MB | DMG |
| Windows | x64 | 62 MB | EXE |
| Windows | ARM64 | 55 MB | EXE |
| Linux | x64 | 86 MB | TAR.GZ |
| Linux | ARM64 | 82 MB | TAR.GZ |

### System Requirements
- macOS 11+ (Big Sur) or later
- Windows 10 22H2+ / Windows 11
- Linux: glibc 2.31+, GTK 3.24+
- 4GB RAM minimum • 500MB disk space
- Internet connection for AI features

### Getting Started
1. Download and install Zed for your OS
2. Launch the Zed editor
3. Sign in to your UMVA account and generate an AI API key
4. Add UMVA AI as a custom OpenAI-compatible provider in Zed
5. Top up your wallet and start coding with AI

---

## 7. Key Takeaways

- **Cheapest AI inference** — text models from $0.06/1M input tokens.
- **No subscription** — pure pay-as-you-go, start with as little as $1.
- **Any editor** — connect Zed, VS Code, JetBrains, Neovim, or any
  OpenAI-compatible client.
- **Large context** — up to 1M token context window.
- **All modalities** — text, image, video, speech-to-text, and text-to-speech.
- **Flexible payments** — cards, crypto (USDT, USDC, BTC, ETH, BNB), bank
  transfer, or UMVA balance.
- **Safety cap** — set an account cap to prevent runaway costs.
- **Unified API** — OpenAI- and Anthropic-compatible endpoints.

---

## 8. Support & Contact

- **Support:** 24/7 via WhatsApp, live chat, or ticket system
- **Website:** umva.net
- **Location:** Kicukiro, Masaka, 2669+HFF Kigali, Rwanda
- **Email:** info@umva.net
- **Phone:** +250 799 643 498 / +250 799 640 980
