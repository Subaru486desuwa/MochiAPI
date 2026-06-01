<div align="center">

**简体中文** · [English](./README.en.md)

<img src="./assets/logo.png" width="116" alt="MochiAPI" />

# MochiAPI

### 一颗麻薯，替你跑通 Claude Code / GPT Pro

**不限次 · 不降智 · 假一赔十**　｜　Claude · Codex · Gemini 全量直连

[**🚀 立即注册 →**](https://mochiapi.com)　·　[**📖 文档**](https://docs.mochiapi.com)　·　[**📊 服务状态**](https://status.mochiapi.com)　·　[**💬 QQ 群**](https://qm.qq.com/q/bZI5UKMBuE)

`★ 99.9% 可用率`　`★ ×10 假一退赔`　`★ 1M context 不截断`　`★ 24h 站长直达`

</div>

> **已经有 key 了？** 直接跳到 [⚡ 30 秒接入 ↓](#-30-秒接入)。

---

## 关于这颗麻薯

<img src="./assets/mochi.jpg" width="180" align="right" alt="一颗麻薯" />

中转站很多，但大多藏在一个公司、一套客服话术、一份你永远联系不到的工单系统后面。

**MochiAPI 不是。** 它就是一个人、一颗麻薯、一份账本——每一次掉线是站长自己半夜醒来修，每一笔账都摊在桌面上给你看。

在这里，**你不是工单号，你是直接认识站长的人。**

---

## 💛 为什么选 MochiAPI

下面每一条，你都能自己测出来。我们不靠话术，靠可验证的事实说话。

### 1. 降智？我赔十倍　`×10`

原版直连，**模型指纹可验证**。遇到任何阉割、缓存伪装、偷偷换小模型——全额退款，再赔十倍额度。不是口号，是写进规则的承诺。

### 2. 一个人，一颗麻薯，一份账本　`24h 站长直达`

没有客服外包，没有 KPI。每一次掉线站长自己醒来修，**QQ / 邮件直接联系到本人**。出了问题，你对话的是修代码的那个人，不是话术机器人。

### 3. MAX + GPT Pro 高质量直连　`1M tokens 不截断`

Claude **MAX** 与 Codex / **GPT Pro** 同等品质直连，**1M context 不截断**，按量透明计费。该有的质量一点不省，该花的钱一分不藏。

---

## ⚡ 30 秒接入

> 不用改代码，不用学新 SDK。把 `base_url` 指向麻薯，原来的工具照常跑。
> 把下面的 `sk-xxxx` 换成你在 [mochiapi.com](https://mochiapi.com) 注册后拿到的真实 key 即可。

### Claude Code

编辑 `~/.claude/settings.json`：

```json
{
  "ANTHROPIC_BASE_URL": "https://mochiapi.com",
  "ANTHROPIC_AUTH_TOKEN": "sk-xxxx"
}
```

然后直接运行：

```bash
claude
```

### Codex

编辑 `~/.codex/config.toml`：

```toml
model_provider = "MochiAPI"

[model_providers.MochiAPI]
  name     = "Mochi"
  base_url = "https://mochiapi.com/v1"
  env_key  = "MOCHI_API_KEY"
```

然后：

```bash
export MOCHI_API_KEY="sk-xxxx" && codex
```

### 通用 OpenAI 兼容端点

```text
base_url = https://mochiapi.com/v1
```

任何兼容 OpenAI 协议的工具、SDK、应用，填这个地址就能用。

**👉 [现在就去拿 key →](https://mochiapi.com)**

---

## 🧩 支持的模型

所有模型均为**原版直连**，模型指纹可验证。

| 家族 | 说明 |
| --- | --- |
| **Claude（含 MAX）** | MAX 高质量直连，1M context 不截断 |
| **Codex / GPT Pro** | 同等品质直连 |
| **Gemini** | 全量直连 |
| **更多主流模型** | OpenAI 兼容端点统一接入 |

---

## 💰 价格与计费

在线充值，**人民币与额度 1:1**——充 1 元 = 1 美元额度口径，透明计费。

- 💴 **充多少用多少，不限次**
- 🧾 **按量计费，账单透明**
- 📦 **订阅套餐可选**

> 没有隐藏倍率，没有暗扣。充多少、用多少、退多少，都在你自己的账本里看得见。

**👉 [去充值开跑 →](https://mochiapi.com)**

---

## 🛡️ 服务保障

- **99.9% 可用率**——不是自封的数字，[实时状态页](https://status.mochiapi.com)随时查真值。
- **假一赔十**——降智、阉割、缓存伪装，全额退款再赔十倍额度。
- **站长 24h 直达**——掉线了，修它的人就在 QQ 群和邮箱另一头。

> 我们不要求你相信这页文字——把状态页加进书签，自己看。

---

## 💬 联系与社群

- 🌐 官网：<https://mochiapi.com>
- 📖 文档：<https://docs.mochiapi.com>
- 📊 服务状态：<https://status.mochiapi.com>
- 💬 QQ 交流群：<https://qm.qq.com/q/bZI5UKMBuE>

掉线、计费、接入有任何问题，群里或邮件直接找站长本人。

---

## 🍡 现在，尝一口

如果你也受够了找不到人、说不清账、偷偷降智的中转站——
来试试这颗麻薯。温柔一点，透明一点，离写代码的人近一点。

<div align="center">

**[🚀 现在注册，30 秒接入 →](https://mochiapi.com)**

*不限次 · 不降智 · 假一赔十*

</div>

---

<div align="center">
<sub>🍡 MochiAPI · 一个人，一颗麻薯，一份账本 · <a href="https://mochiapi.com">mochiapi.com</a></sub>
</div>
