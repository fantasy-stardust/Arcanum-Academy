# The Artificers' Guild | 造机公会

Below the academy's visible halls lies a quieter dominion of benches, gears, sealed engines, and rune-lit worktables.

在学院可见殿堂之下，坐落着一片更安静的领域：那里有工作台、齿轮、封装锻机与被符文照亮的构造桌。

This is the order of makers, builders, and system-weavers, where thought is not only studied but assembled into forms that can act in the world.

这里是创造者、构筑者与系统编织者所属的学派。在这里，思想不只被研究，也被装配成能够在现实中运作的形体。

---

## Guild Charge | 公会之责

The Artificers' Guild studies computation, circuits, mechanisms, digital tools, and the disciplined design of systems. It asks every apprentice to understand what they build, to document what they change, and to test what they intend others to trust.

造机公会研习计算、电路、机械、数字工具与系统化构造之术。它要求每一位学徒理解自己建造之物，记录自己改动之处，并验证那些准备交给他人信赖的结构。

## Guild Emblem | 公会总徽

The guild's emblem is a gear halo around a crystal core. The gear halo represents assembly, repeatable process, and the discipline of interlocking parts; the crystal core represents stored logic, focused intent, and the spark that turns structure into action.

公会总徽是一枚环绕晶核的齿轮光环。齿轮光环象征装配、可重复的流程与彼此咬合的构件秩序；中央晶核则象征被收束的逻辑、集中的意志，以及让结构真正开始运转的火花。

Its heraldic colors are iron gray, ember orange, and crystal cyan.

其代表色为铁灰、炉焰橙与晶青。

## Lower Forgeworks | 下层工坊

The lower levels of the guild are traditionally divided into benches for coding, circuit rooms for signal craft, engine bays for mechanical study, vaults for archived designs, and testing chambers where constructs are proven before they are named complete.

公会的下层工坊通常分为编程台、研习信号构造的回路室、用于机械研究的锻机工位、设计归档密库，以及用于验证构造之物是否足以称作完成的试验间。

No serious mechanism is accepted into the guild record without passing through naming, assembly, and proof.

任何严肃的构造，若未经过命名、装配与验证三道程序，便不会被正式收入公会档案。

### Inner Map | 内部结构图

The map below presents the lower forgeworks as a shared workshop complex. Solid lines mark direct passage, while dotted lines trace the guild's customary paths of collaboration between code, signal, and mechanism.

下图将下层工坊描绘为一座彼此联通的构造群。实线表示直接通行，虚线表示代码、信号与机械之间的传统协作路径。

```mermaid
flowchart TB
	Descent["Lower Descent<br/>下行阶井"] --> Court["Forgewell Court<br/>炉心中庭"]
	Court --> Vault["Design Vault<br/>设计密库"]
	Court --> Proof["Proving Chambers<br/>试验间"]
	Court --> Golem["Golemcraft<br/>信息技术分殿"]
	Court --> Circuit["Circuitry<br/>电子分殿"]
	Court --> Mech["Mechanica<br/>机械分殿"]
	Golem --> Benches["Coding Benches<br/>编程台"]
	Golem --> Racks["System Racks<br/>系统架"]
	Circuit --> Signal["Signal Rooms<br/>回路室"]
	Circuit --> Solder["Soldering Tables<br/>焊接台"]
	Mech --> Engines["Engine Bays<br/>锻机工位"]
	Mech --> Frames["Assembly Frames<br/>装配架"]
	Vault -. Archived designs .-> Golem
	Vault -. Circuit plans .-> Circuit
	Vault -. Mechanical drafts .-> Mech
	Golem -. Control logic .-> Circuit
	Circuit -. Drive signals .-> Mech
	Mech -. Feedback and revision .-> Golem
	Proof -. Final trials .-> Golem
	Proof -. Final trials .-> Circuit
	Proof -. Final trials .-> Mech
```

### Paths of Collaboration | 协作路径说明

The dotted paths on the map describe how the guild's three halls traditionally complete one another. Golemcraft sends outward the control logic that gives structure to behavior; Circuitry carries that logic into signal, sensing, and response; Mechanica gives those signals weight, motion, and material consequence in the world.

图中的虚线路径说明了公会三座分殿如何彼此补完。golemcraft 向外送出赋予行为秩序的控制逻辑；circuitry 将这些逻辑转化为信号、传感与响应；mechanica 则让这些信号在现实中获得重量、运动与物质性的结果。

Just as important is the returning path: mechanisms reveal friction, limits, and failure; those lessons travel back through circuitry as measurement and feedback, and return to golemcraft as revision, optimization, and clearer design. In this guild, craft is not treated as a straight line, but as a disciplined circuit of build, signal, motion, and return.

同样重要的是那条回返路径：机构会暴露摩擦、极限与失效；这些经验经过 circuitry 化为测量与反馈，再回到 golemcraft，成为修订、优化与更清明的设计。在造机公会中，工艺从来不是一条单向直线，而是一道由构造、信号、运动与回返组成的严整回路。

## Apprentice Progression | 公会学徒进阶图

The progression below shows the guild's common route from first handling of tools to integrated cross-hall making.

下图展示公会学徒从初识器具到跨分殿综合构造的常见进阶路线。

```mermaid
flowchart LR
	Entry["First Handling<br/>初识器具"] --> Safety["Tool Discipline<br/>器具规训"]
	Safety --> Choice["Chosen Bench<br/>定选工位"]
	Choice --> Code["Golemcraft<br/>代码与系统"]
	Choice --> Signal["Circuitry<br/>电路与信号"]
	Choice --> Motion["Mechanica<br/>机构与运动"]
	Code --> Practice["Hall Practice<br/>分殿练习"]
	Signal --> Practice
	Motion --> Practice
	Practice --> Trial["Proving Chambers<br/>试验间受试"]
	Trial --> Joint["Joint Construct<br/>联合造物"]
	Joint --> Archive["Guild Record<br/>公会入档"]
	Archive --> Artificer["Apprentice Artificer<br/>进阶造机学徒"]
```

## Guild Structures Beyond the Halls | 分殿之外的公会结构

The halls teach distinct crafts, but the guild's deeper order is kept in five shared spaces: the Design Vault for standards, the Proving Chambers for proof and record, Joint Constructs for integrated making, the Task Board for study routes, and the Construct Catalog for named exemplars.

三座分殿分别教授不同工艺，而公会更深一层的秩序则保存在另外五处共用空间中：Design Vault 负责共用规范，Proving Chambers 负责受试与入档，Joint Constructs 负责联合造物，Task Board 负责学习路线，Construct Catalog 负责典型范本。

| Directory | Charge |
| --- | --- |
| [design-vault/README.md](design-vault/README.md) | Shared conventions for names, interfaces, and assembly across halls. 跨分殿命名、接口与装配规范的共用密库。 |
| [proving-chambers/README.md](proving-chambers/README.md) | Tests, proof protocols, failure records, and rules of entry into the guild record. 试验规程、失败记录与公会入档规则。 |
| [joint-constructs/README.md](joint-constructs/README.md) | Cross-hall project templates, integration guidance, and example builds. 跨分殿项目模板、整合说明与联合造物案例。 |
| [task-board/README.md](task-board/README.md) | Sequenced study routes that turn the guild's scattered scrolls into walkable paths. 将散卷编织成可行学习路线的公会任务板。 |
| [construct-catalog/README.md](construct-catalog/README.md) | A first catalog of named constructs, planned builds, and instructive failures. 收纳典型造物、待造项目与教训案例的首卷图鉴。 |

## Present Disciplines | 现行分殿

| Directory | Subject | Charge |
| --- | --- | --- |
| [golemcraft](golemcraft/README.md) | 信息技术 | The forge of computation, code, debugging, and practical system craft. 计算、代码、调试与系统实践的锻造分殿。 |
| [circuitry](circuitry/README.md) | 电子 | The chamber of circuits, components, sensing, and signal-bearing design. 电路、元件、传感与信号构造之分殿。 |
| [mechanica](mechanica/README.md) | 机械 | The workshop of structure, transmission, assembly, and disciplined motion. 结构、传动、装配与秩序化运动之分殿。 |

## Guild Saying | 公会短谚

Forge with reason, and let craft answer thought.

以理性锻造，让工艺回应思想。