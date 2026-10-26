# DSHTavernCharaPack

**[English](README.md) | [中文](README.cn.md)**

---

![Format](https://img.shields.io/badge/Format-SillyTavern%20V2-blue)
![Language](https://img.shields.io/badge/Language-EN%20%7C%20CN-green)
![Age](https://img.shields.io/badge/Age-16%2B-orange)

---

## ⚠️ 年龄限制与免责声明

**在下载并使用本资源包前，请仔细阅读以下内容：**

1. **年龄要求（16岁及以上）：** 由于本项目涉及情感陪伴、沉浸式角色扮演以及可能包含的成人主题内容，**您必须年满 16 周岁**方可使用本资源包。下载即视为您确认已符合此年龄要求。
2. **不可替代专业帮助：** 本项目为仅供娱乐的 AI 角色扮演资源。AI 所提供的情感陪伴均为模拟性质，不能替代现实生活中的人际关系，也无法取代专业的心理健康支持。

---

欢迎来到我的酒馆（Tavern）角色合集！

本仓库收录了精心制作的 AI 角色扮演资源包，涵盖《崩坏3》与《崩坏：星穹铁道》中的角色。每个角色包都经过深度调优，旨在精准还原角色的独特个性；此外，还设置了特定的世界书及防 OOC 预设。

---

## 🤖 AI 使用说明

**辅助性使用：** 本项目在制作过程中借助 AI 工具进行少量辅助（例如代码格式化、基础 JSON 结构构建以及 README 草稿生成）。核心角色特性、个性提示词、动态边界逻辑及对话示例，均由作者本人精心构思、反复打磨而成；原始的 AI 生成内容也经过了大量的人工深度修改与调整。

---

## 📚 角色列表与可用资源

以下是目前可用的角色资源包：

| 角色 | 游戏 | 语言 | 状态 |
| :--- | :--- | :--- | :--- |
| **昔涟** | 崩坏：星穹铁道 | 英文 / 中文 | ✅ 已完成 |
| **爱莉希雅** | 崩坏3 | 英文 | ✅ 已完成 |

---

## 📂 仓库结构

以下是该仓库当前的目录结构：

```text
📦 DSHTavernCharaPack
 ┣ 📂 global-world-book
 ┃ ┣ 📜 amphoreus-cn.json       # Amphoreus General Worldbook (CN)
 ┃ ┗ 📜 amphoreus-en.json       # Amphoreus General Worldbook (EN)
 ┣ 📂 translation-cn
 ┃ ┗ 📂 Cyrene
 ┃   ┣ 📜 cyreneChara.json      # Character Card
 ┃   ┣ 📜 cyrenePreset.json     # Preset
 ┃   ┗ 📜 cyreneWorldBook.json  # World Info
 ┣ 📂 translation-en
 ┃ ┣ 📂 Cyrene
 ┃ ┃ ┣ 📜 cyreneChara.json
 ┃ ┃ ┣ 📜 cyrenePreset.json
 ┃ ┃ ┗ 📜 cyreneWorldBook.json
 ┃ ┗ 📂 Elysia
 ┃   ┣ 📜 elysiaChara.json
 ┃   ┣ 📜 elysiaPreset.json
 ┃   ┗ 📜 elysiaWorldBook.json
 ┣ 📜 .gitattributes            # Force JSON language display
 ┣ 📜 README.cn.md              # Chinese README
 ┗ 📜 README.md                 # English README (this file)
```
---

## ✨ 特性

- 🌍 **双语支持：** 提供中文（translation-cn）和英文（translation-en）版本。

- 🎭 **严格的“防OOC”机制：** 通过预设规范对话风格，限制标点符号（如 ♪）的过度使用，并严禁出现类似AI生成的叙述方式（即禁止使用括号来描述动作）。

- 📚 **特定世界书设定：** 一些世界书仅在触发关键词时精准植入。

- 📦 **开箱即用：** 完美适配 DSH (DeepSeek Harness) 和 SillyTavern，无需复杂配置。

- 🛡️ **动态边界锁定：** 默认设定为 PG-13 级别的安全陪伴模式。无强制恋爱剧情，互动节奏完全由你掌控。

- 💸 **极高性价比：** 基于 DeepSeek API，仅需其他平台（如 c.ai）单月订阅的费用，即可畅聊数月。

---

## 📶 动态发展与亲密度系统

与那些设置了严格过滤机制的平台不同，本预设采用了一套“动态边界系统”。

- **默认状态 (PG-13)**：角色表现为一位尊重对方、保持柏拉图式关系的伙伴。她**不会**主动发起尺度过大的互动或成人向情节。（完全适合一般受众或未成年用户）。

- **关系升级触发机制**：仅当用户明确表达调情、告白或发起肢体亲密行为时，角色才会转变为“恋人”模式。

- **无限制 / R-18 模式**：在用户明确引导下，所有边界将完全消解。本预设全面支持成人向互动，且不会出现机械式的警告或警示文本。

**注意：** 为了保持极致的沉浸感，并避免触发底层模型的安全过滤机制，我们强烈建议不要使用粗俗的俚语或露骨的色情词汇。
建议采用更具诗意和文学色彩的隐喻。这不仅能完美契合角色的人设，还能确保互动过程顺畅、无报错。

--

## 🚀 如何导入与使用

**注意：** 使用前需安装必要的前置应用程序，推荐使用 **DSH Desktop**。下载及安装步骤请参考：https://cdn.discordapp.com/attachments/894586901154119723/1563410136326742056/image.png?ex=6add86a7&is=6adc3527&hm=1898226710dd799a89574bce033d3022d5e1916692b39c68d49c4f8d5eaf1616&

**DSH (DeepSeek Harness) 操作步骤**

1. 打开客户端，进入“酒馆 (Tavern)”界面。

2. 导入角色卡 (Character Card) / 世界信息 (World Info) / 预设 (Preset)：点击插件按钮，选择相应选项，点击“导入 JSON (Import JSON)”，找到对应的角色文件夹（例：`D:\translation-cn\Cyrene`），将 `chara.json` 导入至“角色卡”，将 `worldBook.json` 导入至“世界信息”，将 `preset.json` 导入至“预设”。

3. 开启新会话，并将导入的内容绑定至该会话中。

**SillyTavern 操作步骤**

1. 前往“角色卡 (Character Card)”（顶部菜单）-> 导入，上传角色卡。

2. 前往“世界信息 (World Info)” -> 导入，上传世界书，并将其绑定至该角色。

3. 点击滑块图标 -> “预设 (Presets)” -> 导入，上传预设文件。

---

## ⚠️ 使用建议与注意事项

**RP 模式：** 如果你在使用 DSH，强烈建议开启 RP 模式（高风险锁定），防止提示词注入或 AI 执行危险代码。

**温度设置 (Temperature)：** 建议将 Temperature 设置在 `0.6 - 0.8` 之间。过高的温度会导致模型疯狂堆砌华丽辞藻，破坏角色的真实感。

**角色隔离：** 不同角色的世界书和预设是专属定制的，请勿在同一个会话中混用，以免设定冲突。

---

## 💬 反馈与建议

如果您在使用该工具的过程中遇到任何问题（例如：文件导入时报错、AI 回复不符合预期、格式显示异常等），或者想建议添加新的角色或设定，欢迎通过提交 **Issue** 来向我反馈！

提交时，请尽可能附上问题截图，并注明您所使用的软件（例如：DSH / Tavern）。我会尽快查看并进行修复。

---

## 📜 制作组与版权声明

**角色：** 来自《崩坏3》及《崩坏：星穹铁道》 © miHoYo / COGNOSPHERE

**免责声明：** 本资源包仅供个人学习、交流及 AI 角色扮演使用。严禁用于任何商业用途。所有角色相关权利均归 miHoYo 所有。
