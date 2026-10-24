# SOP Writer

SOP Writer 是一个面向博士申请的 Statement of Purpose（SOP）写作技能，可用于 Claude Code 和 Codex。它尤其适合经济学申请，帮助申请人把研究经历、个人贡献和未来研究计划写得具体、清晰。

## 核心功能

| 模式 | 适用场景 | 工作重点 |
| --- | --- | --- |
| 全篇优化 | 已有完整草稿 | 调整结构、突出研究贡献、控制篇幅 |
| 分段修改 | 需要改进特定段落 | 具体化问题、方法、个人贡献与项目匹配 |
| 从零起草 | 已有经历与研究想法 | 梳理素材、建立提纲、逐段形成初稿 |

修改围绕一个原则展开：把篇幅留给最能体现研究能力的内容。对于研究问题、方法选择和个人贡献，补充必要的细节；对于空泛的热情表述、重复的履历介绍和填充句，则适当压缩或删去。

## 安装

根据使用的工具，将仓库克隆到对应的个人技能目录：

**Claude Code**

```sh
git clone https://github.com/zhangch369/sop-writer.git ~/.claude/skills/sop-writer
```

**Codex**

```sh
git clone https://github.com/zhangch369/sop-writer.git ~/.codex/skills/sop-writer
```

如果目标目录已存在，请先检查其中的版本，避免覆盖已有修改。安装完成后，重新打开会话以加载技能。

## 使用方式

在 Claude Code 中可以通过 `/sop-writer` 调用；在 Codex 中，可以直接要求助手使用 `sop-writer` 修改文书。

开始前，请提供目标项目的文书题目和字数限制，以及已有草稿或研究想法。描述研究经历时，尽量说明自己承担的工作、使用的方法和解决的问题，这些信息能帮助技能提出更有针对性的修改。

**全篇优化**

> 用 sop-writer 修改这份 SOP，重点写清我的研究贡献，控制在 1,000 英文词以内。标出需要我补充事实的地方。

**分段修改**

> 用 sop-writer 优化这段研究经历，写清研究问题、我承担的工作、方法选择和解决的问题。

**从零起草**

> 用 sop-writer 根据我的经历和目标项目生成 SOP 提纲，先列出缺失信息，再逐段起草。

## 参考来源

本技能以以下写作指导为基础，将其中的建议整理为可重复使用的中文工作流程：

| 来源 | 对应内容 |
| --- | --- |
| Chris Blattman：[PhD applicants: Writing your statement of purpose](https://chrisblattman.com/blog/2022/01/11/phd-applicants-writing-your-statement-of-purpose/)（2022 年 1 月 11 日） | 具体展开研究想法，提高信息密度，减少无关叙述 |
| UC San Diego 经济系：[Writing Personal Statements](https://economics.ucsd.edu/undergraduate-program/resources/how-to-prepare-for-a-phd-in-econ/prep-your-application/writing-personal-statements.html) | 写清研究与课程经历中的实际工作、方法选择、问题解决过程和数学背景；清晰表达潜在研究兴趣，并寻求导师反馈 |

技能初版于 2026 年 2 月通过与 Claude Code 协作完成。在参考建议的基础上，进一步整理了三种工作模式、中文修改示例和检查清单。这些内容包含 AI 辅助组织与扩展，不应全部视为原作者的表述。

本项目独立整理，与上述作者或机构不存在官方关联。各项指导的来源及改编范围见 [SOURCES.md](SOURCES.md)。

## 延伸资源

[Economics Mentoring Program — PhD Application Resources](https://www.economicsmentoringprogram.com/phd-application-resources) 汇集经济学博士申请建议、SOP 示例及其他申请资源。其 Statement of Purpose 栏目也收录了上述 Blattman 文章。

这些示例可以帮助读者比较不同的表达方式和组织思路。页面也提醒，示例的质量与结构不应被视为统一标准；写作时仍需围绕自己的经历和目标项目的要求作出选择。

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

## 编辑记录

| 日期 | 修改内容 |
| --- | --- |
| 2026-10-24 | 整理公开版本，补充安装、使用与来源说明 |
| 2026-10-24 | 补充 UC San Diego 个人陈述指导的来源说明 |
| 2026-10-24 | 加入 Economics Mentoring Program 申请资源 |
| 2026-10-24 | 润色 README，改善段落衔接与使用说明，保留参考来源 |

后续修改通过 Git 提交记录保留，便于查看版本差异。
