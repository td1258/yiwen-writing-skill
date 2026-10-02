# yiwen-writing

一款用于中文知识型短口播的 Codex Skill。它帮助你把选题、真实经历或初稿写成有判断、有案例、有机制解释和情绪余味的文稿，默认篇幅约 1—2 分钟。

这是一款独立的写作工具。名称用于描述其分析对象与写作方向，不代表亿文本人参与、认可或授权；请勿用它复制具体作品或冒充原作者。

## 安装

在尚未安装此 Skill 的环境中运行：

```bash
git clone https://github.com/td1258/yiwen-writing-skill.git ~/.codex/skills/yiwen-writing
```

安装后重新打开 Codex，或在新对话中调用 `$yiwen-writing`。更新已克隆的版本：

```bash
git -C ~/.codex/skills/yiwen-writing pull --ff-only
```

## 使用

```text
$yiwen-writing
选题：总想准备好再开始。
真实经历：我准备了半年做视频，一条也没发。
目标：一篇 1—2 分钟的中文口播稿。
```

也可以提供初稿，要求改写或只诊断结构。没有提供真实个人经历时，Skill 不会编造第一人称故事。

## 文件

- `SKILL.md`：入口、适用范围和写作判断规则。
- `references/style-protocol.md`：案例、专业背书、机制和收束的组织方法。
- `references/prose-engine.md`：口语表达与节奏检查。
- `agents/openai.yaml`：Codex 中的显示信息与默认提示。

## 许可

本仓库按 [MIT License](LICENSE) 开放。许可适用于本仓库的原创指令和文档，不授予任何第三方作品、姓名或标识的权利。
