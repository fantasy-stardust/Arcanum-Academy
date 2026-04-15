# Assembly Standards | 装配规范

These standards apply when a construct draws work from more than one hall.

以下规范适用于任何同时调用多个分殿成果的构造物。

---

## Shared Rules | 共用规则

1. Every construct must declare one primary charge. 每个构造物都必须先声明一个主要职责。
2. Every participating hall must declare its owned part. 每个参与分殿都必须明确自己负责的部分。
3. Every connection point must be named before assembly begins. 每一个连接点都必须在装配开始前完成命名。
4. Every revision must record what changed, why it changed, and which hall approved it. 每一次修订都必须记录改动内容、改动理由与批准分殿。
5. No construct may enter the Proving Chambers without a written handoff from all participating halls. 任何构造物若未获得所有参与分殿的书面交接说明，不得进入试验间。

## Required Record Fields | 必备记录项

- Construct name 构造名称
- Primary charge 主要职责
- Participating halls 参与分殿
- Interfaces and handoff points 接口与交接点
- Safety concerns 安全注意事项
- Measurement basis 测量基准
- Borrowed tool custody 借用器具保管
- Test status 受试状态

Safety concerns should follow [safety-discipline.md](safety-discipline.md), and shared measurements should follow [measurement-units.md](measurement-units.md).

安全注意事项应遵循 [safety-discipline.md](safety-discipline.md)，共用测量写法应遵循 [measurement-units.md](measurement-units.md)。

## Minimum Integration Check | 最低整合检查

- Code can identify the expected states or commands 代码能识别预期状态或指令
- Circuits can carry signal or power without ambiguity 电路能无歧义地承载信号或供电
- Mechanisms can respond without forced strain 机构能在不被强迫受力的情况下响应
- Failures can be traced to a specific point of handoff 失效能被追溯到明确的交接点

## Closing Rule | 结尾规则

If a construct cannot be explained clearly across halls, it is not yet ready to be trusted.

若一件构造物无法被跨分殿清楚解释，它便还不配被信赖。