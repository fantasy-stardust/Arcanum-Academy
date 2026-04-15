# Stage II Cross-Hall Paths | 第二阶段 跨殿衔接

At this stage the apprentice stops treating another hall as a black box and begins learning the language of handoff.

到这一阶段，学徒不再把其他分殿视作黑箱，而开始学习交接的语言。

---

## Required Leaves | 必读卷叶

- [../joint-constructs/integration-guides/code-to-circuit.md](../joint-constructs/integration-guides/code-to-circuit.md)
- [../joint-constructs/integration-guides/circuit-to-mechanism.md](../joint-constructs/integration-guides/circuit-to-mechanism.md)
- [../joint-constructs/integration-guides/feedback-loops.md](../joint-constructs/integration-guides/feedback-loops.md)
- [../design-vault/interface-template.md](../design-vault/interface-template.md)
- [../design-vault/handoff-note-example.md](../design-vault/handoff-note-example.md)

## Crossing Paths | 三道交接

| Crossing | Learn to declare | Proof of understanding |
| --- | --- | --- |
| Code to circuit 逻辑至信号 | State names, trigger conditions, and timing windows 状态名、触发条件与时序窗口 | Write one interface that a signal path can test directly. 写出一份可被信号路径直接验证的接口说明。 |
| Circuit to mechanism 信号至运动 | Drive conditions, stop conditions, and allowable load 驱动条件、停止条件与允许载荷 | Name one measurement that predicts mechanical misbehavior before collision. 写出一项能在碰撞前预测机构失常的测量。 |
| Motion to feedback 运动至回返 | Rest state, return criteria, and correction trigger 静止状态、回位判定与修正触发 | Trace one observed motion back into a control decision. 把一次观测到的运动追回成一次控制判断。 |

## Required Work Before Advancing | 进阶前必做

Before leaving Stage II, prepare the following for at least one imagined construct:

离开第二阶段前，至少应为一件设想中的构造准备以下材料：

- One completed interface note 一份完整接口说明
- One named handoff note 一份具名交接说明
- One short list of shared measurements 一组简短共用测量
- One explicit failure suspicion at a handoff point 一条明确指向交接点的失效怀疑

## Failure First | 先看失效

Read [../proving-chambers/guild-record/failure-cases/oscillating-gate-carriage.md](../proving-chambers/guild-record/failure-cases/oscillating-gate-carriage.md) before attempting a joint build. It shows how a small excess in three halls becomes one violent error.

在尝试联合造物前，应先读 [../proving-chambers/guild-record/failure-cases/oscillating-gate-carriage.md](../proving-chambers/guild-record/failure-cases/oscillating-gate-carriage.md)。它展示了三殿里各自一点小过量如何汇成一次剧烈失误。

## Exit Mark | 出关标记

You leave Stage II only when another hall could take your note and act without guessing.

唯有当另一座分殿能拿起你的记录而不必猜测就开始行动时，你才算真正走出第二阶段。