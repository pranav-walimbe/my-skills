# my-skills

A small collection of agent skills I like.

## Skills Included

| Skill | Purpose | Upstream |
| --- | --- | --- |
| `grill-me` | Relentlessly question a plan, decision, or idea until its decision tree is resolved. | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling) |
| `drawio-skill` | Produce editable draw.io diagrams across architecture, UML, ERD, BPMN, SysML, infrastructure, code, and other rich visual formats. | [Agents365-ai/drawio-skill](https://github.com/Agents365-ai/drawio-skill/tree/main/skills/drawio-skill) |
| `mermaid-diagrams` | Create compact, version-controlled diagrams that render directly in Markdown documentation. | [M2LabOrg/agent-skills](https://github.com/M2LabOrg/agent-skills/tree/main/mermaid-diagrams) |
| `stop-slop` | Remove common AI-writing patterns from prose. | [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) |
| `gh` | Use GitHub CLI reliably from an agent, including JSON, pagination, repository targeting, search, and API fallback. | [cli/cli](https://github.com/cli/cli/tree/trunk/skills/gh) |
| `code-quality` | Apply unified code standards with custom Python, Rust, comment, docstring, and commit conventions. | [khasky/awesome-agent-skills](https://github.com/khasky/awesome-agent-skills/tree/main/skills/awesome-code-standards) |
| `diagnose` | Debug hard bugs and performance regressions through reproducible feedback loops and ranked hypotheses. | [maxenergy/skills](https://github.com/maxenergy/skills/tree/main/skills/engineering/diagnose) |
| `tdd` | Build features and fixes test-first using behavior-focused red-green-refactor vertical slices. | [maxenergy/skills](https://github.com/maxenergy/skills/tree/main/skills/engineering/tdd) |

## Drop into your project

Run this from the project that should receive the skills:

```sh
mkdir -p .agents/skills && curl -fsSL https://github.com/pranav-walimbe/my-skills/archive/refs/heads/main.tar.gz | tar -xz -C .agents/skills --strip-components=3 my-skills-main/.agents/skills
```
