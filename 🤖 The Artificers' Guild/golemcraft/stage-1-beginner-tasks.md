# Stage I Beginner Tasks | 第一阶段 入门任务

The first workings of this forge are not judged by size, but by clarity: a small tool with a clear name is worth more than a grand contrivance no one can explain.

本殿的起步之作，不以大小评判，而以清晰评判：一件命名清楚的小工具，胜过一件无人说得明白的宏大装置。

---

## Leaf Charge | 卷叶之责

This leaf turns the hall's study path into a first set of workable tasks. Follow it after reading [README.md](README.md) and before attempting any cross-hall build.

此卷将本殿的学习路径化为第一组可执行任务。应先读 [README.md](README.md)，再依此起步，之后才尝试任何跨殿造物。

## Before First Working | 起步前先备

- [../task-board/stage-1-foundations.md](../task-board/stage-1-foundations.md)
- [../design-vault/safety-discipline.md](../design-vault/safety-discipline.md)
- [../design-vault/measurement-units.md](../design-vault/measurement-units.md)
- [stage-1-practice-templates.md](stage-1-practice-templates.md)

## Beginner Task Sequence | 入门任务顺序

| Task | Working charge | Record to keep | Minimum format |
| --- | --- | --- | --- |
| 1. Name a state chain 命名一条状态链 | Describe a tiny routine with 3-5 named states and state what causes each transition. 用 3-5 个具名状态描述一个小流程，并写明每次转移由何触发。 | One state list with transition conditions and one suspected failure threshold. 一份状态表，以及一条可疑失效阈值。 | Template one in [stage-1-practice-templates.md](stage-1-practice-templates.md). 使用 [stage-1-practice-templates.md](stage-1-practice-templates.md) 中的模板一。 |
| 2. Build a repeatable count 构造一次可复现计次 | Write a small program that performs a repeated action and records the count or time over three runs. 写一个小程序，让它执行重复动作，并在三次运行中记录计数或时长。 | A short run log showing repeated behavior. 一份展示重复行为的短日志。 | Template two in [stage-1-practice-templates.md](stage-1-practice-templates.md). 使用 [stage-1-practice-templates.md](stage-1-practice-templates.md) 中的模板二。 |
| 3. Trace a fault by logging 以日志追索一处故障 | Take a small bug or wrong output, add logging without changing the intended logic, then trace where expectation and result part ways. 面对一个小 bug 或错误输出，在不改逻辑意图的前提下补日志，再追到预期与结果分离之处。 | One written failure trace naming the first visible symptom. 一份写明首发症状的故障追索记录。 | Template three in [stage-1-practice-templates.md](stage-1-practice-templates.md). 使用 [stage-1-practice-templates.md](stage-1-practice-templates.md) 中的模板三。 |
| 4. Write a function contract 写下一份函数契约 | Extract a small function, name its input, output, and one case in which it should fail safely. 抽出一个小函数，写明其输入、输出，以及一条应当安全失败的情况。 | A short contract note plus one safe-failure example. 一份简短契约说明，加一条例行安全失败样例。 | Template four in [stage-1-practice-templates.md](stage-1-practice-templates.md). 使用 [stage-1-practice-templates.md](stage-1-practice-templates.md) 中的模板四。 |
| 5. Build a testable utility 构造一件可测试的小工具 | Create a small utility such as a formatter, timer, or file sorter, then test it with at least three clear cases. 制作一件小型工具，如格式整理器、计时器或文件归类器，并以至少三条清晰用例验证。 | A test record showing what each case proves. 一份说明各测试证明何事的验证记录。 | Template five in [stage-1-practice-templates.md](stage-1-practice-templates.md). 使用 [stage-1-practice-templates.md](stage-1-practice-templates.md) 中的模板五。 |

## Suggested Output Templates | 建议练习产物模板

Use the matching numbered template in [stage-1-practice-templates.md](stage-1-practice-templates.md). The hall does not ask for a grand report at this stage, only a record complete enough that another apprentice could reread the work without guessing.

请配套使用 [stage-1-practice-templates.md](stage-1-practice-templates.md) 中同编号的模板。本阶段并不要求宏大报告，只要求记录完整到足以让另一位学徒复读而不必猜测。

## Minimum Output | 最低产出

Before leaving this leaf, the apprentice should hold:

离开此卷之前，学徒至少应持有：

- One named control path that another reader can follow 一条他人可读懂的具名控制路径
- One repeatable run log with clear values or timing 一份带清楚数值或时序的可复现运行日志
- One fault trace that names where expectation first broke 一份说明预期首次断裂于何处的故障追索记录
- One function note that states responsibility and safe-failure boundary 一份说明职责与安全失败边界的函数说明
- One test record proving more than the best case alone 一份不只验证最佳情况的测试记录

## Watchfires | 警示灯

- A vague name hides a vague thought. 含糊的命名，往往掩盖含糊的思想。
- A log added only after panic rarely teaches enough. 只在慌乱之后补上的日志，往往教不了太多。
- A test that proves only success has not yet measured trust. 只验证成功的测试，还没有真正量到信赖。

## Advancement Mark | 升阶标记

An apprentice may leave Stage I in golemcraft when all of the following hold:

当下列诸项都成立时，学徒方可离开 golemcraft 的第一阶段：

- A control path can be explained without hand-waving. 能在不含糊其辞的情况下解释一条控制路径。
- One behavior can be measured and reproduced across repeated runs. 至少一种行为可被测量，并能在重复运行中复现。
- At least one verification record exists and says what was proven. 至少存在一份验证记录，并写明究竟证明了什么。
- Another apprentice could read the note, run the work, and not rely on guesswork. 另一位学徒读完说明后，能够运行此物而不必依赖猜测。

When that mark is met, proceed to [../task-board/stage-2-cross-hall-paths.md](../task-board/stage-2-cross-hall-paths.md).

达到此标记后，再前往 [../task-board/stage-2-cross-hall-paths.md](../task-board/stage-2-cross-hall-paths.md)。