# Golem Verification | 代码与系统验证

This protocol applies to constructs whose main burden lies in logic, automation, state control, or software behavior.

本规程适用于主要负担落在逻辑、自动化、状态控制或软件行为上的构造物。

---

## Minimum Proof | 最低验证

1. The construct starts in a known state 构造能够从已知状态开始
2. Expected inputs produce expected outputs 预期输入能够得到预期输出
3. Failure states are visible and documented 失效状态可见且已被记录
4. Revision history explains the current behavior 修订记录能解释当前行为
5. A second apprentice can reproduce the basic run 另一位学徒能够复现基础运行

## Failure Markers | 失败标记

- Silent state corruption 无声状态损坏
- Unnamed dependencies 未命名依赖
- Behavior that changes without revision record 无修订记录却发生变化的行为
- Recovery steps that exist only in memory 只能靠口头记忆完成的恢复步骤

## Pass Condition | 通过条件

The construct may proceed only when its logic can be rerun, explained, and repaired without guesswork.

只有当其逻辑能够在不依赖猜测的情况下被重跑、解释与修复时，构造物才可通过。