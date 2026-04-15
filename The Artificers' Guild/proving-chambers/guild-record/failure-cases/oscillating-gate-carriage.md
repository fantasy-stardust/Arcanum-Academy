# Oscillating Gate Carriage | 摆振门车案例

## Construct | 构造

`gate-carriage-mk1`

## Intended Charge | 目标职责

To open a small study gate when a signal was received, then return to rest without overshoot.

在接收到信号后开启小型学习门，并在回位时不发生过冲。

## First Visible Symptom | 首发症状

The carriage reached the open position, but shook twice on return and struck the frame stop with growing force.

门车虽然到达了开启位置，但在回位时连续摆振两次，并以不断增大的力撞击止挡。

## Traced Cause | 追溯原因

The feedback threshold in golemcraft was too late, the control pulse in circuitry remained longer than intended, and the counterweight in mechanica had been placed slightly beyond the balanced point.

golemcraft 中的反馈阈值设定过晚，circuitry 中的控制脉冲持续时间长于预期，而 mechanica 中的配重又略微越过了平衡位置。

## Correction | 修正方式

The pulse window was shortened, the threshold was moved earlier, and the counterweight was reset one mark inward on the frame.

控制脉冲窗口被缩短，反馈阈值被提前，配重则在构架上向内回调了一格。

## Lesson Kept | 留下的教训

When three halls cooperate, a small excess in each hall may combine into one violent failure.

当三个分殿协作时，每一殿里那一点点“只是略多”的偏差，最后可能汇合成一次剧烈失效。