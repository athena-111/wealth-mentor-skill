# Wealth Mentor Skill v1.0.0

AI Agent 财富判断能力框架。

Wealth Mentor 面向 Codex 与其他 Agent 系统，帮助 Agent 诊断财富问题、拆解变量、识别风险并形成条件判断。它不是财富机器人、投资顾问、财富预测工具或自动决策工具。

> Wealth Mentor 不是替用户决定财富路径，而是帮助用户建立更好的财富判断能力。

## Features

- 财富问题诊断
- 多模型分析
- 长期价值判断
- 风险与安全边际识别
- 条件判断与验证行动

## Architecture

```text
User Question
↓
Problem Diagnosis
↓
Decision Framework
↓
Council Reasoning
↓
Risk Analysis
↓
Conditional Judgment
↓
Validation Action
```

架构详情见 [docs/architecture.md](docs/architecture.md)。

## Usage

将本目录放入 Agent 的 Skill 目录，并让 Agent 读取 `SKILL.md`。本项目不需要 API、数据库、后台服务或代码运行环境。安装说明见 [INSTALLATION.md](INSTALLATION.md)。

## Example

用户问：“我要不要辞职创业？”

Skill 不直接回答“创业”或“不创业”，而会诊断创业动机，检查市场验证、个人优势、现金流安全和失败可恢复性，调用相关委员会模型，并给出条件判断与下一步验证动作。

## Documentation

- [系统架构](docs/architecture.md)
- [核心理念](docs/philosophy.md)
- [评价标准](docs/evaluation.md)
- [贡献指南](CONTRIBUTING.md)

## License

[MIT License](LICENSE)
