# 复习队列

本队列从 Stage 2 开始使用，按学习事件触发复习，不规定每次学习时长，也不追溯修改 Stage 1 的既有状态。

复习的目标是从记忆中重新提取并暴露缺口，而不是再次通读课程正文。出现重要错误时，先记录缺口、针对性纠正，再用替代题验证。

## 复习检查点

| Checkpoint | Trigger | Task | PASS 标准 |
|---|---|---|---|
| R0 | 完成当前课程时 | 完成 5 道闭卷题和费曼复述 | Learning Goals 均有正确回答，重要错误通过替代题 |
| R1 | 完成上一课后至少隔一个自然日的下一次独立学习会话 | 回答上一课 3 道快速回忆题 | 无重要概念错误；有误则先纠正再继续新课学习 |
| R2 | 完成当前 Stage 时 | 完成一个混合虚构案例和一页阶段总结 | 能连接本阶段课程并说明判断边界 |
| R3 | 进入下一 Stage 前 | 复测上一 Stage 最薄弱的知识点 | 能在不看笔记时正确解释并应用 |

## 当前队列

只有实际开始课程后才新增记录。

| Course | Checkpoint | Reviewed | Result | Main Gap | Next Trigger | Evidence |
|---|---|---|---|---|---|---|
| Return & Compounding | R0 | 2026-08-26 | PASS | 年化计算必须保留复利关系；区分名义收益与实际收益。 | 2026-08-27 或之后的下一次独立学习会话（R1） | [学习证据](../02-risk-and-return/01-return-and-compounding.md#学习证据) |
| Volatility | R0 | 2026-08-26 | PASS | 波动大不等于收益更高；低波动不等于安全。 | 2026-08-27 或之后的下一次独立学习会话（R1，与 Return & Compounding 一并） | [学习证据](../02-risk-and-return/02-volatility.md#学习证据) |
| Return & Compounding + Volatility | R1 | 2026-08-27 | PASS | 无重要概念错误；复习中进一步确认路径会影响复利结果，低波动不等于安全。 | 完成 Stage 2 时（R2） | [Return & Compounding 学习证据](../02-risk-and-return/01-return-and-compounding.md#学习证据)；[Volatility 学习证据](../02-risk-and-return/02-volatility.md#学习证据) |
| Drawdown | R0 | 2026-08-27 | PASS | 最大回撤须以峰值为分母计算；不应把被迫卖出当作可接受条件。 | 2026-08-28 或之后的下一次独立学习会话（R1） | [学习证据](../02-risk-and-return/03-drawdown.md#学习证据) |
| Risk Capacity | R0 | 2026-08-27 | PASS | 稳定收入不能消除短期确定用途资金的期限风险；承受得起不等于必须承担。 | 2026-08-28 或之后的下一次独立学习会话（R1） | [学习证据](../02-risk-and-return/04-risk-capacity.md#学习证据) |
| Risk Tolerance | R0 | 2026-08-27 | PASS | 压力测试要同时检查情绪性卖出与必要目标是否受影响；主观接受不等于安排合适。 | 2026-08-28 或之后的下一次独立学习会话（R1） | [学习证据](../02-risk-and-return/05-risk-tolerance.md#学习证据) |
| Common Risks | R0 | 2026-08-27 | PASS | 低波动或担保印象不等于安全；分散和转移不等于风险消失。 | 2026-08-28 或之后的下一次独立学习会话（R1） | [学习证据](../02-risk-and-return/06-common-risks.md#学习证据) |

`Result` 只使用：

- `PASS`：达到该检查点标准，可以继续。
- `REVISIT`：仍有重要缺口；完成纠正和替代题后更新本行。

`Evidence` 链接到对应课程的“学习证据”标题，或 Stage 结束后的阶段总结。记录只包含抽象答案、错误类型与虚构或彻底去敏的案例。
