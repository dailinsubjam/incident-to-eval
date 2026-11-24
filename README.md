# incident-to-eval

从真实故障构建可回放的 RCA Agent 评测案例，覆盖证据冻结、输入与查询接入、正式答卷提取、评分校准和回归比较。

[阅读 Skill](SKILL.md) · 版本 0.1.0

将整个目录放入目标 Agent 支持的 Skill 目录，保留 `SKILL.md`、`references/` 和 `agents/` 的相对结构。可使用以下请求开始：

> 使用 incident-to-eval，把这个真实故障整理为适配当前 Agent 的可回放评测案例。

本包提供构建方法和接入指南，不自带 Agent、回放服务或评分 runner。优先复用目标项目已有接口与工具；示例均为虚构设计，不包含真实事故数据。

参考文档分别说明[案例与证据设计](references/case-design.md)、[接入与回放](references/adapters.md)、[评分与比较](references/evaluation.md)及[三种接入示例](references/examples.md)。

