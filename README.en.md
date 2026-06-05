<div align="center">

[简体中文](./README.md) · **English**

<img src="./assets/logo.png" width="100" alt="MochiAPI" />

# MochiAPI

### Claude Code · Codex, routed directly — pay as you go

`Unlimited · full-quality · 10× refund on fakery`

[**🚀 Sign up**](https://mochiapi.com)　·　[**📖 Docs**](https://docs.mochiapi.com)　·　[**📊 Status**](https://status.mochiapi.com)　·　[**💬 Community**](https://qm.qq.com/q/bZI5UKMBuE)

</div>

---

## 💰 Pricing

Online top-up at **RMB : credit = 1 : 1** (¥1 = $1 credit, never expires). You're billed by the **group ratio** picked when you create a key:

| Group | Ratio | Models | Notes |
| --- | --- | --- | --- |
| `vip1_aws` | **1x** | Claude Opus / Sonnet / Haiku | Cheapest Claude route |
| `vip1_max` | 1.5x | Claude Opus / Sonnet / Haiku | MAX pool, 10× refund |
| `vip2_plus` | **0.15x** | GPT-5.2 ~ 5.5 | Cheapest GPT route |
| `vip2_pro` | 0.3x | GPT-5.2 ~ 5.5 | Stable GPT route |
| `grok` | 0.1x | Grok 4.20 | xAI direct |
| `vip4_ds_pro` | 0.23x | DeepSeek | Official API direct |
| `vip3_api` | 3x | Gemini 3 Pro / Flash | Official API, higher ratio |
| `default` | 5x | All models | ⚠️ Fallback when no group is set — most expensive |

> The ratio is a billing coefficient on your credit — **lower is cheaper** (`0.15x` = billed at 15%). **Always pick the right group** when creating a key; don't use `default`. Live ratios: console → Tokens → My available groups.

**~$100 of credit roughly buys**: Sonnet coding ~350–500 runs · Opus refactors ~70–120 · Haiku ~1500–2500 · GPT-5.5 ~350–500 · Grok ~3000–5000.

---

## 🚀 Get started (one-click import, fastest)

**① Install the tools**

| Tool | Windows | macOS / Linux |
| --- | --- | --- |
| **CLI** (pick what you need) | [⬇ claude.exe](https://github.com/Subaru486desuwa/MochiAPI/releases/latest/download/claude.exe) / [⬇ codex.exe](https://github.com/Subaru486desuwa/MochiAPI/releases/latest/download/codex.exe) | `curl -fsSL https://claude.ai/install.sh \| bash` (Claude) · `brew install codex` (Codex) |
| **CC Switch** (one-click configurator) | [Releases](https://github.com/farion1231/cc-switch/releases) | `brew install --cask cc-switch` |

**② Sign up + create a key**

Sign up at [mochiapi.com](https://mochiapi.com) → top up → Tokens → Add. **Pick a group** (`vip1_aws` for Claude, `vip2_plus` for GPT).

**③ One-click import to CC Switch**

In the token list, find your key, click **⋮ → "Import to CC Switch" → pick the target CLI** (Claude Code / Codex) → your browser opens CC Switch, hit **"Import"**. Restart your terminal and just run `claude` / `codex`.

<details>
<summary>Prefer manual config? (click to expand)</summary>

**Claude Code** — `~/.claude/settings.json`:

```json
{
  "ANTHROPIC_BASE_URL": "https://mochiapi.com",
  "ANTHROPIC_AUTH_TOKEN": "sk-your-key"
}
```

**Codex** — `~/.codex/config.toml`:

```toml
model_provider = "MochiAPI"

[model_providers.MochiAPI]
  name     = "Mochi"
  base_url = "https://mochiapi.com/v1"
  env_key  = "MOCHI_API_KEY"
```

Any OpenAI-compatible tool works with `https://mochiapi.com/v1` + your key.

</details>

---

## Links

🌐 [Website](https://mochiapi.com)　·　📖 [Docs](https://docs.mochiapi.com)　·　📊 [Status](https://status.mochiapi.com)　·　💬 [QQ group](https://qm.qq.com/q/bZI5UKMBuE)

<div align="center">
<sub>🍡 MochiAPI · <a href="https://mochiapi.com">mochiapi.com</a></sub>
</div>
