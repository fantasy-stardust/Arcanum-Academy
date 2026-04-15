# Lantern Gate Sentinel | 灯门守望构造

## Purpose | 用途

To sense approach, raise a small lantern gate, and return to rest after passage.

感测来者接近、抬起一扇小型灯门，并在通行后回归静止。

## Hall Contributions | 分殿分工

- golemcraft: state logic, timing, and event sequence 信息技术负责状态逻辑、时序与事件流程
- circuitry: sensor reading, trigger signal, and drive switching 电子负责传感读取、触发信号与驱动切换
- mechanica: gate arm, hinge balance, and return motion 机械负责门臂、铰接平衡与回位运动

## Core Interfaces | 核心接口

- `glm-to-crc-control` defines when the sensor event becomes a command
- `crc-to-mch-drive` defines how the drive pulse reaches the gate arm
- `mch-to-glm-feedback` defines how the return position is reported back

## First Lessons | 初次教训

The construct worked only after all three halls reduced their own excess: shorter pulse length, lighter return weight, and clearer state thresholds.

这件构造之所以最终能够正常工作，是因为三个分殿都各自削减了自己那一点“多余”：更短的脉冲、更轻的回位配重，以及更清楚的状态阈值。

## Record Status | 入档状态

`current`