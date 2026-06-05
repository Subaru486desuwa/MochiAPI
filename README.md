<div align="center">

**简体中文** · [English](./README.en.md)

<img src="./assets/logo.png" width="100" alt="MochiAPI" />

# MochiAPI

### Claude Code · Codex 直连，按量计费

`不限次 · 不降智 · 假一赔十`

[**🚀 注册**](https://mochiapi.com)　·　[**📖 文档**](https://docs.mochiapi.com)　·　[**📊 状态**](https://status.mochiapi.com)　·　[**💬 QQ 群**](https://qm.qq.com/q/bZI5UKMBuE)

</div>

---

## 💰 定价

在线充值，**人民币 : 站内额度 = 1:1**（¥1 = $1 额度，余额永不过期）。实际扣费按你建 Key 时选的**分组倍率**：

| 分组 | 倍率 | 适用模型 | 说明 |
| --- | --- | --- | --- |
| `vip1_aws` | **1x** | Claude Opus / Sonnet / Haiku | 最便宜的 Claude 通道 |
| `vip1_max` | 1.5x | Claude Opus / Sonnet / Haiku | MAX 号池，假一赔十 |
| `vip2_plus` | **0.15x** | GPT-5.2 ~ 5.5 全系 | 最便宜的 GPT 通道 |
| `vip2_pro` | 0.3x | GPT-5.2 ~ 5.5 全系 | GPT 稳定通道 |
| `grok` | 0.1x | Grok 4.20 系列 | xAI 直连 |
| `vip4_ds_pro` | 0.23x | DeepSeek 全系 | 官方 API 直连 |
| `vip3_api` | 3x | Gemini 3 Pro / Flash | 官方 API，倍率偏高 |
| `default` | 5x | 全模型 | ⚠️ 未选分组的兜底，最贵 |

> 倍率是站内额度的计费系数，**越低越便宜**（`0.15x` 即按 15% 扣费）。**建 Key 时务必选对分组**，别用 `default`。实时倍率以控制台「令牌 → 我的可用分组」为准。

**¥100 大概能跑**：Sonnet 写代码 ~350–500 次 · Opus 重构 ~70–120 次 · Haiku ~1500–2500 次 · GPT-5.5 ~350–500 次 · Grok ~3000–5000 次。

---

## 🚀 三步接入（一键导入，最快）

**① 装工具**

| 工具 | Windows | macOS / Linux |
| --- | --- | --- |
| **CLI**（按需选） | [⬇ claude.exe](https://github.com/Subaru486desuwa/MochiAPI/releases/latest/download/claude.exe) / [⬇ codex.exe](https://github.com/Subaru486desuwa/MochiAPI/releases/latest/download/codex.exe) | `curl -fsSL https://claude.ai/install.sh \| bash`（Claude）· `brew install codex`（Codex） |
| **CC Switch**（一键配置器） | [Releases 安装版](https://github.com/farion1231/cc-switch/releases) | `brew install --cask cc-switch` |

**② 注册 + 建 Key**

注册 [mochiapi.com](https://mochiapi.com) → 充值 → 「令牌 → 添加」，**务必选分组**（Claude 用 `vip1_max`，GPT 用 `vip2_pro`）。

**③ 一键导入 CC Switch**

在令牌列表找到你的 Key，点右侧 **⋮ → 「导入到 CC Switch」→ 选目标 CLI**（Claude Code / Codex）→ 浏览器唤起 CC Switch，点 **「导入」** 即可。重启终端，直接 `claude` / `codex` 开跑。

<details>
<summary>不想用 CC Switch？手动配置（点开）</summary>

**Claude Code** —— `~/.claude/settings.json`：

```json
{
  "ANTHROPIC_BASE_URL": "https://mochiapi.com",
  "ANTHROPIC_AUTH_TOKEN": "sk-你的key"
}
```

**Codex** —— `~/.codex/config.toml`：

```toml
model_provider = "MochiAPI"

[model_providers.MochiAPI]
  name     = "Mochi"
  base_url = "https://mochiapi.com/v1"
  env_key  = "MOCHI_API_KEY"
```

任何 OpenAI 兼容工具填 `https://mochiapi.com/v1` + 你的 Key 也能用。

</details>

---

## 链接

🌐 [官网](https://mochiapi.com)　·　📖 [文档](https://docs.mochiapi.com)　·　📊 [状态](https://status.mochiapi.com)　·　💬 [QQ 群](https://qm.qq.com/q/bZI5UKMBuE)

<div align="center">
<sub>🍡 MochiAPI · <a href="https://mochiapi.com">mochiapi.com</a></sub>
</div>
