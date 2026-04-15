# Handoff Note Example | 交接说明示例

Use this as a model when one hall passes a finished part to another before proof.

当一个分殿在受试前将已完成部分交给另一分殿时，可将此作为说明模型。

---

## Construct | 构造

`lantern-gate-sentinel`

## From and To | 交出与接收

- From: circuitry
- To: mechanica

## Delivered Part | 交付部分

Sensor-triggered drive pulse with confirmed stop signal.

具备停止确认的传感驱动脉冲。

## Expected Use | 预期用途

To engage the gate arm only after the presence signal is stable for one full count.

仅在来者存在信号稳定满一个计次后，驱动门臂动作。

## Known Limits | 已知限制

- Pulse length remains safe only within the current spring tension range
- A loose return joint may create false retriggering

## Required Checks Before Acceptance | 接收前必查项

- Mechanica confirms the gate arm is balanced mechanica 确认门臂已完成平衡
- Stop contact can report rest position back to circuitry 停止触点可将静止位置回报 circuitry
- No second pulse appears during return travel 回位过程中不会出现第二次脉冲

## Approval | 批准

Approved for chamber entry after joint dry run.

经联合空载试运行后，批准进入试验间。