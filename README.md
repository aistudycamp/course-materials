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

| # | Guide |
|---|-------|
| 01 | [Install Claude Code](how-to-guides/01-install-claude-code.html) |
| 02 | [Install a Skill](how-to-guides/02-install-a-skill.html) |
| 03 | [Write a CLAUDE.md](how-to-guides/03-write-a-claude-md.html) |
| 04 | [Git Basics](how-to-guides/04-git-basics.html) |
| 05 | [Recover from Mistakes](how-to-guides/05-recover-from-mistakes.html) |
| 06 | [Keep Claude Focused](how-to-guides/06-keep-claude-focused.html) |
| 07 | [Debug with Claude](how-to-guides/07-debug-with-claude.html) |
| 08 | [Deploy with Vercel](how-to-guides/08-deploy-with-vercel.html) |
| 09 | [Connect InstantDB](how-to-guides/09-connect-instant-db.html) |
| 10 | [Break Down Big Ideas](how-to-guides/10-break-down-big-ideas.html) |
| 11 | [Write a Spec](how-to-guides/11-write-a-spec.html) |
| 12 | [Manage API Keys](how-to-guides/12-manage-api-keys.html) |
| 13 | [Connect Google Workspace CLI](how-to-guides/13-connect-google-workspace-cli.html) |
| 14 | [Tool Landscape](how-to-guides/14-tool-landscape.html) |
| 15 | [Understanding Models](how-to-guides/15-understanding-models.html) |
| 16 | [Claude Products Explained](how-to-guides/16-claude-products-explained.html) |

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
