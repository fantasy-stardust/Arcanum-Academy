# Study Bench Sentinel Brief | 学习台守望构造简报

## Purpose | 用途

Create a small construct that notices approach to a study bench, lights a signal lantern, and lowers it after the bench is left unattended.

构造一件能够感知有人接近学习台、点亮提示灯，并在台前无人后将其降下的小型装置。

## Hall Roles | 分殿分工

- golemcraft: timing logic and state switching
- circuitry: presence sensing and lamp signal
- mechanica: lifting arm and return linkage

## Minimum Success | 最低完成标准

- Detect approach reliably 能稳定感知接近
- Raise and lower the lantern without jamming 升降提示灯时不发生卡滞
- Return to rest after a short delay 能在短暂延迟后回归静止

## Suggested Proof Focus | 建议受试重点

- false triggers 误触发
- delayed return 回位延迟
- repeated strike on end stops 重复撞击止挡