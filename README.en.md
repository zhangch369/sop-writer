# SOP Writer

[中文](README.md) | [English](README.en.md)

SOP Writer is a Statement of Purpose (SOP) writing skill for PhD applications, designed for use with Claude Code and Codex. It is particularly suited to economics applications and helps applicants describe their research experience, individual contributions, and future research plans clearly and concretely.

## Features

| Mode | When to use it | Focus |
| --- | --- | --- |
| Full-draft revision | You have a complete draft | Improve structure, highlight research contributions, and meet the word limit |
| Section revision | A particular passage needs work | Clarify questions, methods, individual contributions, and program fit |
| Drafting from scratch | You have research experience and ideas | Organize material, develop an outline, and draft one section at a time |

The guiding principle is to devote space to evidence of research ability. Add useful detail about research questions, methodological choices, and personal contributions, while trimming generic expressions of enthusiasm, repeated CV information, and filler.

## Installation

Clone the repository into the personal skills directory for your tool:

**Claude Code**

```sh
git clone https://github.com/zhangch369/sop-writer.git ~/.claude/skills/sop-writer
```

**Codex**

```sh
git clone https://github.com/zhangch369/sop-writer.git ~/.codex/skills/sop-writer
```

If the destination already exists, inspect its contents before proceeding to avoid overwriting local changes. Start a new session after installation so the tool can discover the skill.

## Usage

In Claude Code, invoke `/sop-writer`. In Codex, explicitly ask the assistant to use `sop-writer` when revising your statement.

Provide the target program's prompt and word limit, along with your draft or research ideas. For research experience, describe the work you personally undertook, the methods you used, and the problems you solved. These details allow for more specific, useful revisions.

The skill instructions are currently written in Chinese. You can request an English draft or revision, as in the examples below.

**Revise a full draft**

> Use sop-writer to revise this SOP in English. Make my research contributions clear, keep it within 1,000 words, and flag any claims that need additional factual details from me.

**Improve a section**

> Use sop-writer to revise this research experience paragraph in English. Clarify the research question, my responsibilities, the methodological choices, and the problems I addressed.

**Start from an outline**

> Use sop-writer to build an English SOP outline from my experience and target program. Identify missing information first, then draft one section at a time.

## Sources and Attribution

The skill draws on the following guidance, organized into a reusable writing workflow:

| Source | Relevant guidance |
| --- | --- |
| Chris Blattman, [PhD applicants: Writing your statement of purpose](https://chrisblattman.com/blog/2022/01/11/phd-applicants-writing-your-statement-of-purpose/) (January 11, 2022) | Develop specific research ideas, increase information density, and reduce irrelevant narrative |
| UC San Diego Department of Economics, [Writing Personal Statements](https://economics.ucsd.edu/undergraduate-program/resources/how-to-prepare-for-a-phd-in-econ/prep-your-application/writing-personal-statements.html) | Describe concrete research and coursework contributions, methods, problem-solving, and mathematical preparation; explain potential research interests clearly and seek advisor feedback |

The first version was developed in February 2026 through collaboration with Claude Code. The three working modes, Chinese revision examples, and checklists include AI-assisted organization and expansion; they should not all be attributed to the original sources.

This is an independently developed skill with no official affiliation with the authors or institutions listed above. See [SOURCES.md](SOURCES.md) (in Chinese) for detailed provenance and the scope of adaptation.

## Further Resources

[Economics Mentoring Program — PhD Application Resources](https://www.economicsmentoringprogram.com/phd-application-resources) brings together economics PhD application advice, sample SOPs, and other resources. Its Statement of Purpose section also links to the Blattman article above.

The examples can help readers compare approaches to writing and organization. As the resource page cautions, they are not universal benchmarks for quality or structure. Your statement should reflect your own experience and the requirements of the target program.

## Writing Principles

- Follow the target program's prompt, word limit, and application requirements.
- Use only the applicant's actual experience; illustrative examples are not personal credentials.
- Verify research claims, references, courses, and faculty information, and explicitly flag missing details.
- Treat suggested section proportions as flexible guidance and adapt them to the application.

## Repository Files

| File | Contents |
| --- | --- |
| [README.md](README.md) | Chinese documentation |
| [SKILL.md](SKILL.md) | Skill instructions, working modes, revision examples, and checklists, in Chinese |
| [SOURCES.md](SOURCES.md) | Sources and adaptation notes, in Chinese |

## Editing History

| Date | Changes |
| --- | --- |
| 2026-10-24 | Prepared the public version with installation, usage, and source documentation |
| 2026-10-24 | Documented the UC San Diego personal statement guidance |
| 2026-10-24 | Added Economics Mentoring Program application resources |
| 2026-10-24 | Polished the Chinese README and added an editing history |
| 2026-10-24 | Added this English README and links between the two language versions |

Subsequent changes are preserved in the Git commit history for version comparison.
