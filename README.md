# SOP Writer

面向博士申请的 Statement of Purpose（SOP）写作技能，侧重经济学研究经历与研究计划的清晰表达，可用于 Claude Code 和 Codex。

## 核心功能

| 模式 | 适用场景 | 工作重点 |
| --- | --- | --- |
| 全篇优化 | 已有完整草稿 | 调整结构、突出研究贡献、控制篇幅 |
| 分段修改 | 需要改进特定段落 | 具体化问题、方法、个人贡献与项目匹配 |
| 从零起草 | 已有经历与研究想法 | 梳理素材、建立提纲、逐段形成初稿 |

核心原则：在重要内容上增加具体信息，在无关内容上减少篇幅。重点呈现研究问题、方法选择、个人贡献和研究判断，减少空泛热情、重复履历与填充句。

## 安装

将仓库克隆到所用工具的个人技能目录，选择以下一种方式：

**Claude Code**

```sh
git clone https://github.com/zhangch369/sop-writer.git ~/.claude/skills/sop-writer
```

**Codex**

```sh
git clone https://github.com/zhangch369/sop-writer.git ~/.codex/skills/sop-writer
```

如果目标目录已存在，请先检查已有版本。安装后重新打开会话，以便工具发现技能。

## 使用方式

在 Claude Code 中调用 `/sop-writer`，或在支持技能的助手中明确指定使用 `sop-writer`。

为了获得有针对性的修改，请提供目标项目的题目与字数限制、真实研究经历、个人贡献，以及已有草稿或研究想法。

**全篇优化**

> 用 sop-writer 修改这份 SOP，重点写清我的研究贡献，控制在 1,000 英文词以内。标出需要我补充事实的地方。

**分段修改**

> 用 sop-writer 优化这段研究经历，写清研究问题、我承担的工作、方法选择和解决的问题。

**从零起草**

> 用 sop-writer 根据我的经历和目标项目生成 SOP 提纲，先列出缺失信息，再逐段起草。

## 内容来源

本技能主要参考 Chris Blattman 的文章：

**[PhD applicants: Writing your statement of purpose](https://chrisblattman.com/blog/2022/01/11/phd-applicants-writing-your-statement-of-purpose/)** — Chris Blattman，2022 年 1 月 11 日。

初版于 2026 年 2 月通过与 Claude Code 协作整理，将写作建议转化为可重复使用的中文工作流程，随后补充了经济学博士申请中关于研究经历、方法训练与潜在研究兴趣的指导。补充材料的原始网页来源尚未确认，因此不作具体机构归属。

本项目是独立整理的技能，不是原作者或任何大学发布、认可的官方工具。中文表述、工作模式、修改示例和检查清单包含 AI 辅助整理与扩展，不能全部归为原作者的观点或原话。更多信息见 [SOURCES.md](SOURCES.md)。

## 使用原则

- 以目标项目的实际题目、篇幅和申请要求为准。
- 仅使用申请人的真实经历；示例不能直接视为个人经历。
- 核实研究事实、文献引用、课程与教授信息，缺失信息应明确标注。
- 将篇幅比例等建议作为修改参考，根据具体申请任务调整。

## 文件说明

| 文件 | 内容 |
| --- | --- |
| [SKILL.md](SKILL.md) | 技能指令、工作模式、修改示例与检查清单 |
| [SOURCES.md](SOURCES.md) | 参考来源与整理说明 |
