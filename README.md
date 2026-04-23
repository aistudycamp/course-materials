# AI Study Camp - Course Materials

Shareable materials built for [AI Study Camp](https://aistudycamp.com) students.

## Exercises

Interactive, hands-on exercises. Each one follows the same format: clone the folder, open in Claude Code, learn a concept, walk through an example, build something real you can keep using.

| Exercise | Description | Time |
|----------|-------------|------|
| [Skill Builder](exercises/skill-builder/) | Build your first Claude Code skill from scratch | ~1 hr |
| [AI Audit](exercises/ai-audit/) | Map out your work tasks and identify where AI can help | ~1 hr |
| [Morning Briefing](exercises/morning-briefing/) | Connect Gmail and Calendar, build a daily briefing skill | ~2 hrs |
| [Workflow Visualizer](exercises/workflow-visualizer/) | Describe a process in plain words, get a visual flowchart | ~1.5 hrs |
| [Meeting-to-Action](exercises/meeting-to-action/) | Turn messy meeting notes into structured summaries with action items | ~1.5 hrs |
| [Presentation Builder](exercises/presentation-builder/) | Turn rough notes into polished HTML slide decks | ~1.5 hrs |
| [Data Cleanup](exercises/data-cleanup/) | Clean up messy data and get a summary report | ~1.5 hrs |
| [Build Your Workflows](exercises/build-your-workflows/) | Capstone - pick items from your audit and build real workflows | ~2-3 hrs |

```bash
cd exercises/skill-builder
claude
```

## How-To Guides

Step-by-step guides for common pain points. Open the HTML files in your browser.

- [Install Claude Code](how-to-guides/install-claude-code.html)
- [Install a Skill](how-to-guides/install-a-skill.html)
- [Write a CLAUDE.md](how-to-guides/write-a-claude-md.html)
- [Git Basics](how-to-guides/git-basics.html)
- [Recover from Mistakes](how-to-guides/recover-from-mistakes.html)
- [Keep Claude Focused](how-to-guides/keep-claude-focused.html)
- [Debug with Claude](how-to-guides/debug-with-claude.html)
- [Deploy with Vercel](how-to-guides/deploy-with-vercel.html)
- [Break Down Big Ideas](how-to-guides/break-down-big-ideas.html)
- [Manage API Keys](how-to-guides/manage-api-keys.html)
- [Connect Google Workspace CLI](how-to-guides/connect-google-workspace-cli.html)
- [Tool Landscape](how-to-guides/tool-landscape.html)
- [Claude Products Explained](how-to-guides/claude-products-explained.html)

## Decks

HTML slide decks used in lectures.

- `agents-vs-workflows.html` - Week 4 lecture: when to use agents vs. simple workflows

## Skills

Installable Claude Code skills. Drop any folder into `~/.claude/skills/` and it's ready to use.

- `idea-breakdown/` - give Claude one big idea or a list of automation candidates; get back a classified, prioritized build plan with agent vs. workflow recommendations

See [guide 02](how-to-guides/02-install-a-skill.html) for how to install a skill from this repo.

## Other Tools

- **cc-level-up** - Claude Code personal trainer plugin. Scans your setup, grades it A-F, and tells you what to improve. Install via: `/plugin marketplace add tiobenito/cc-level-up`
  - Repo: [tiobenito/cc-level-up](https://github.com/tiobenito/cc-level-up)
