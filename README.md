<div align="center">

# 🍡 MochiAPI

### 一颗麻薯，替你跑通 Claude Code / GPT Pro
*MochiAPI — for Claude Code and GPT Pro*

**不限次 · 不降智 · 假一赔十**　｜　Claude · Codex · Gemini 全量直连
*Unlimited use · full-quality routing · transparent billing — Claude, Codex and Gemini, routed directly*

[**🚀 立即注册 / Sign up →**](https://mochiapi.com)　·　[**📖 文档 / Docs**](https://docs.mochiapi.com)　·　[**📊 服务状态 / Status**](https://status.mochiapi.com)　·　[**💬 QQ 群 / Community**](https://qm.qq.com/q/bZI5UKMBuE)

`★ 99.9% 可用率` &nbsp; `★ ×10 假一退赔` &nbsp; `★ 1M context 不截断` &nbsp; `★ 24h 站长直达`

</div>

> **已经有 key 了？** 直接跳到 [⚡ 30 秒接入 ↓](#-30-秒接入--get-started-in-30-seconds)。
> **Already have a key?** Jump straight to [⚡ Get started ↓](#-30-秒接入--get-started-in-30-seconds).

---

## 关于这颗麻薯 / A small, honest story

中转站很多，但大多藏在一个公司、一套客服话术、一份你永远联系不到的工单系统后面。

**MochiAPI 不是。** 它就是一个人、一颗麻薯、一份账本——每一次掉线是站长自己半夜醒来修，每一笔账都摊在桌面上给你看。在这里，**你不是工单号，你是直接认识站长的人。**

> There are plenty of API gateways. Most hide behind a company, a script, and a ticketing system you can never reach a human through.
>
> **MochiAPI doesn't.** One person, one mochi, one ledger — when it goes down, the maintainer wakes up at night and fixes it, and every charge sits in an open book. Here, **you're not a ticket number — you're someone who knows the person running the service.**

---

## 💛 为什么选 MochiAPI / Why MochiAPI

下面每一条，你都能自己测出来。我们不靠话术，靠可验证的事实说话。
*Every claim below is testable. We don't sell hype — we sell things you can verify yourself.*

### 1. 降智？我赔十倍 / Full quality, or tenfold credit　`×10`

原版直连，**模型指纹可验证**。遇到任何阉割、缓存伪装、偷偷换小模型——全额退款，再赔十倍额度。不是口号，是写进规则的承诺。

> Original models, routed directly — **fingerprints you can verify**. If you ever catch a downgraded, cached, or swapped model: full refund, plus ten times the credit back. Not a slogan, a rule.

### 2. 一个人，一颗麻薯，一份账本 / Small team, accountable service　`24h 站长直达`

没有客服外包，没有 KPI。每一次掉线站长自己醒来修，**QQ / 邮件直接联系到本人**。出了问题，你对话的是修代码的那个人，不是话术机器人。

> No outsourced support, no KPIs. Every outage gets fixed by the person who wrote the code. Reach the maintainer **directly via QQ or email** — you talk to the human, not a bot.

### 3. MAX + GPT Pro 高质量直连 / MAX + GPT Pro direct access　`1M tokens 不截断`

Claude **MAX** 与 Codex / **GPT Pro** 同等品质直连，**1M context 不截断**，按量透明计费。该有的质量一点不省，该花的钱一分不藏。

> Claude **MAX** and Codex / **GPT Pro** at the same quality, direct — with **1M context, never truncated**, billed transparently by usage.

---

## ⚡ 30 秒接入 / Get started in 30 seconds

> 不用改代码，不用学新 SDK。把 `base_url` 指向麻薯，原来的工具照常跑。
> 把下面的 `sk-xxxx` 换成你在 [mochiapi.com](https://mochiapi.com) 注册后拿到的真实 key 即可。
>
> No code rewrite, no new SDK. Point your `base_url` at Mochi and keep your existing tools.
> Replace `sk-xxxx` with the real key from your [mochiapi.com](https://mochiapi.com) account.

### Claude Code

编辑 `~/.claude/settings.json` / Edit `~/.claude/settings.json`：

```json
{
  "ANTHROPIC_BASE_URL": "https://mochiapi.com",
  "ANTHROPIC_AUTH_TOKEN": "sk-xxxx"
}
```

然后直接运行 / then just run：

```bash
claude
```

### Codex

编辑 `~/.codex/config.toml` / Edit `~/.codex/config.toml`：

```toml
model_provider = "MochiAPI"

[model_providers.MochiAPI]
  name     = "Mochi"
  base_url = "https://mochiapi.com/v1"
  env_key  = "MOCHI_API_KEY"
```

然后 / then：

```bash
export MOCHI_API_KEY="sk-xxxx" && codex
```

### 通用 OpenAI 兼容端点 / Any OpenAI-compatible client

```text
base_url = https://mochiapi.com/v1
```

任何兼容 OpenAI 协议的工具、SDK、应用，填这个地址就能用。
Works with any tool, SDK, or app that speaks the OpenAI protocol.

**👉 [现在就去拿 key / Grab your key now →](https://mochiapi.com)**

---

## 🧩 支持的模型 / Supported models

所有模型均为**原版直连**，模型指纹可验证。
*All models are routed directly to original upstreams, with verifiable fingerprints.*

| 家族 / Family | 说明 / Details |
| --- | --- |
| **Claude（含 MAX）** | MAX 高质量直连，1M context 不截断 / MAX direct, full 1M context |
| **Codex / GPT Pro** | 同等品质直连 / same-quality direct access |
| **Gemini** | 全量直连 / fully routed |
| **更多主流模型 / More** | OpenAI 兼容端点统一接入 / via OpenAI-compatible endpoint |

---

## 💰 价格与计费 / Pricing

在线充值，**人民币与额度 1:1**——充 1 元 = 1 美元额度口径，透明计费。
*Online top-up at **RMB 1 : 1 USD credit** — ¥1 = $1 of credit.*

- 💴 **充多少用多少，不限次** / Pay as you go, unlimited use
- 🧾 **按量计费，账单透明** / Usage-based, transparent billing
- 📦 **订阅套餐可选** / Subscription plans available

> 没有隐藏倍率，没有暗扣。充多少、用多少、退多少，都在你自己的账本里看得见。
> No hidden multipliers, no silent skimming — what you put in and what you spend is all visible in your own ledger.

**👉 [去充值开跑 / Top up and start →](https://mochiapi.com)**

---

## 🛡️ 服务保障 / Reliability

- **99.9% 可用率**——不是自封的数字，[实时状态页](https://status.mochiapi.com)随时查真值。
  *99.9% uptime — not a self-awarded number; check the [live status page](https://status.mochiapi.com) anytime.*
- **假一赔十**——降智、阉割、缓存伪装，全额退款再赔十倍额度。
  *Tenfold refund — any downgrade or fakery means full refund plus 10× credit.*
- **站长 24h 直达**——掉线了，修它的人就在 QQ 群和邮箱另一头。
  *24h direct line — when it's down, the person fixing it is right there in QQ and email.*

> 我们不要求你相信这页文字——把状态页加进书签，自己看。
> Don't take this page's word for it — bookmark the status page and watch it yourself.

---

## 💬 联系与社群 / Contact & community

- 🌐 官网 / Website：<https://mochiapi.com>
- 📖 文档 / Docs：<https://docs.mochiapi.com>
- 📊 服务状态 / Status：<https://status.mochiapi.com>
- 💬 QQ 交流群 / QQ group：<https://qm.qq.com/q/bZI5UKMBuE>

掉线、计费、接入有任何问题，群里或邮件直接找站长本人。
For any downtime, billing or setup issue, reach the operator directly — in the group or by email.

---

## 🍡 现在，尝一口 / Now, take a bite

如果你也受够了找不到人、说不清账、偷偷降智的中转站——
来试试这颗麻薯。温柔一点，透明一点，离写代码的人近一点。

> If you're tired of gateways with no human, murky billing, and quiet downgrades —
> come try this little mochi. A bit softer, a bit clearer, a bit closer to the people who actually write the code.

<div align="center">

**[🚀 现在注册，30 秒接入 / Sign up now, live in 30s →](https://mochiapi.com)**

*不限次 · 不降智 · 假一赔十 — Unlimited · full-quality · transparent.*

</div>

---

<sub>🍡 MochiAPI · 一个人，一颗麻薯，一份账本 / One person, one mochi, one ledger · <a href="https://mochiapi.com">mochiapi.com</a></sub>
