# Measurement Units | 测量单位约定

What cannot be measured consistently cannot be handed across halls with confidence.

凡不能被稳定测量之物，便不能被有把握地跨殿交接。

---

## Common Rule | 共用原则

Every reading written for another hall must name its unit, reference point, and acceptable range.

凡写给其他分殿的读数，都必须同时写明单位、基准点与可接受范围。

## Preferred Forms | 优先写法

| Quantity | Preferred form | Notes |
| --- | --- | --- |
| Voltage 电压 | `V` | Write the nominal value and allowed drift. 写明标称值与允许漂移。 |
| Current 电流 | `A` or `mA` | Use `mA` for low-signal work. 小信号优先用 `mA`。 |
| Resistance 电阻 | `ohm` or `k ohm` | Do not omit whether the value is nominal or measured. 不得省略标称值或实测值身份。 |
| Time 时长 | `ms` or `s` | Timing windows in control paths should prefer `ms`. 控制路径时间窗优先用 `ms`。 |
| Frequency 频率 | `Hz` | State sampling or update rate when relevant. 必要时说明采样或更新频率。 |
| Distance 距离 | `mm` | Bench-scale mechanisms default to `mm`. 工位级机构默认使用 `mm`。 |
| Angle 角度 | `deg` | Declare the zero position before reporting angles. 报告角度前先声明零位。 |
| Load 载荷 | `g` or `kg` | State whether the value is static or moving. 说明是静载还是运动载荷。 |
| Logic state 逻辑状态 | named state plus trigger condition | Use words, not memory alone. 逻辑状态要写成状态名与触发条件，而非只靠记忆。 |

## Recording Conventions | 记录约定

1. Separate value and unit with a space: `5 V`, `120 ms`, `3 mm`. 数值与单位之间保留空格，如 `5 V`、`120 ms`、`3 mm`。
2. Declare tolerance with `plus/minus`, such as `5 V plus/minus 0.2 V`. 容差使用 `plus/minus` 写法，例如 `5 V plus/minus 0.2 V`。
3. Mark baselines explicitly, such as `rest-angle 0 deg` or `lift-start 12 mm`. 基线必须显式写出，例如 `rest-angle 0 deg` 或 `lift-start 12 mm`。
4. When units change across halls, write both the local reading and the receiving hall's usable interpretation. 跨殿换算时，同时写出本殿读数与接收分殿可用解释。

## Cross-Hall Translation | 跨殿换算

- golemcraft should write timing windows and state thresholds so circuitry can probe them directly. golemcraft 应把时序窗口与状态阈值写成 circuitry 可直接测得的形式。
- circuitry should report drive and sensor values in forms mechanica can connect to travel, force, or stop position. circuitry 应把驱动与传感读数写成 mechanica 可关联到行程、受力或止位的形式。
- mechanica should report travel, alignment, and load so golemcraft can decide whether a state transition is early, late, or unsafe. mechanica 应把行程、对位与载荷写成 golemcraft 可判断状态转移早晚与风险的形式。

## Example Set | 示例写法

- Control pulse: `120 ms plus/minus 10 ms` 控制脉冲：`120 ms plus/minus 10 ms`
- Rest contact threshold: `below 0.5 V counts as settled` 静止触点阈值：`低于 0.5 V 视为已归定`
- Gate travel: `42 mm from rest to open mark` 门体行程：`从静止位到开启位共 42 mm`
- Counterweight offset: `3 mm inward from previous mark` 配重偏移：`较上次标记向内 3 mm`

## Guild Saying | 公会短谚

An uncertain measurement is only a rumor wearing numbers.

不确定的测量，不过是披着数字外衣的传言。