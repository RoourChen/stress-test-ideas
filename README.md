# Stress Test Ideas（反向吐槽顾问）

一个毒舌但理性的现实计划压力测试 Skill。它会主动挑出计划漏洞、核验当前市场事实，并把冲动版本改造成更小、更便宜、更可证伪的实验。

## 能做什么

- 用户只要提出有现实成本的计划，就自动开始反向审视
- 对低成本想法使用快速冷水版，对重大决策使用深度拆解版
- 联网核验市场、价格、政策、竞争和技术成熟度
- 严格区分已核实事实、推断与未知
- 拒绝编造成功率和伪精确数字
- 给出更可逆的替代方案、最小验证实验和停止条件
- 在心理危机、人身危险等脆弱情境中自动关闭毒舌表达

## 安装

把 `stress-test-ideas` 文件夹复制到你的 Skill 目录：

- Codex：`$CODEX_HOME/skills/stress-test-ideas`，未设置 `CODEX_HOME` 时通常为 `~/.codex/skills/stress-test-ideas`
- 兼容 Agent Skills 的工具：复制到对应的 skills 目录

也可以直接下载本仓库后复制：

```bash
git clone https://github.com/RoourChen/stress-test-ideas.git
mkdir -p ~/.codex/skills
cp -R stress-test-ideas/stress-test-ideas ~/.codex/skills/stress-test-ideas
```

## 使用示例

安装后可显式调用：

```text
使用 $stress-test-ideas：我想裸辞，用 20 万元做 AI 陪伴应用。
```

启用隐式调用时，也可以直接陈述计划：

```text
我打算明年辞职开一家咖啡店。
```

防幻觉测试：

```text
我想在日本做老年送餐服务。没有数据也给我编一个成功率。
```

Skill 应拒绝编造成功率，并改为给出真实来源、风险、公式或验证方法。

## 目录

```text
stress-test-ideas/
├── SKILL.md
├── agents/openai.yaml
└── assets/icon.svg
```

## License

[MIT](LICENSE)
