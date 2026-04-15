# Circuit Validation | 电路验证

This protocol applies to constructs whose burden lies in power, signal, sensing, or controlled response.

本规程适用于负担主要落在供电、信号、传感或受控响应上的构造物。

---

## Minimum Proof | 最低验证

1. Power enters within the intended range 供电输入处于预期范围内
2. Signal path can be traced from source to response 信号路径可从源头追踪至响应端
3. Components remain stable under expected operation 元件在预期工作下保持稳定
4. Measured values match the declared design closely 实测值与设计声明大体相符
5. Fault points can be isolated without dismantling the whole construct 无需完全拆解即可隔离故障点

## Failure Markers | 失败标记

- Unexpected heat or unstable draw 异常发热或电流波动
- Floating signal paths 漂浮不定的信号路径
- Component orientation not recorded 元件方向未被记录
- Measured behavior conflicts with the schematic 实测行为与电路图相冲突

## Pass Condition | 通过条件

The circuit may proceed only when its path can be read, its behavior measured, and its faults traced without obscurity.

只有当电路的路径可读、行为可测、故障可追时，它才可通过。