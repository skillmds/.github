<p align="center">
  <a href="https://skillmd.com"><img src="https://skillmd.com/brand/banner.png" alt="SkillMD — the open registry of Agent Skills" width="560"></a>
</p>

<h3 align="center">The open registry of Agent Skills. The registry that lints.</h3>

<p align="center">
  <a href="https://skillmd.com">skillmd.com</a> ·
  <a href="https://skillmd.com/search">Browse 25,000+ skills</a> ·
  <a href="https://skillmd.com/docs">Docs</a> ·
  <a href="https://skillmd.com/blog">Blog</a> ·
  <a href="https://github.com/skillmds/skillmd">Source</a>
</p>

---

**Agent Skills** are `SKILL.md` files: Markdown instructions with a small YAML header that Claude Code, Cursor, Codex, Gemini CLI, GitHub Copilot, Windsurf and 60+ other agents load on demand. One format, every agent. [What is an Agent Skill?](https://skillmd.com/docs/what-is-an-agent-skill)

**SkillMD** is where they live. Every skill on [skillmd.com](https://skillmd.com) is linted against the format, security-scanned for what it can do (scripts, network, secrets), pinned to a commit, and shown with its verdict and independent scanner results. Installing writes files and does nothing else.

```bash
npx skillmds search "pdf"          # search the registry
npx skillmds add anthropic/pdf     # install into every agent on your machine
npx skillmds lint ./my-skill       # lint your own before you share it
```

### What's here

| Repo | What it is |
|---|---|
| [**skillmd**](https://github.com/skillmds/skillmd) | The open-source toolchain (MIT): the `skillmd` CLI, the `skillmds` MCP server, the GitHub Action and the `@skillmd/core` SKILL.md engine the registry itself runs. |

npm: [`skillmds`](https://www.npmjs.com/package/skillmds) · [`@skillmd/core`](https://www.npmjs.com/package/@skillmd/core) · MCP registry: `com.skillmd/skillmd` · hosted MCP: `https://api.skillmd.com/mcp`

### Find skills

- **By agent:** [Claude Code](https://skillmd.com/agents/claude-code) · [Cursor](https://skillmd.com/agents/cursor) · [Codex](https://skillmd.com/agents/codex) · [Gemini CLI](https://skillmd.com/agents/gemini-cli) · [GitHub Copilot](https://skillmd.com/agents/github-copilot) · [Windsurf](https://skillmd.com/agents/windsurf) · [all 60+](https://skillmd.com/agents)
- **By category:** [Coding & Dev Tools](https://skillmd.com/category/coding) · [AI & ML](https://skillmd.com/category/ai-ml) · [DevOps](https://skillmd.com/category/devops) · [Security](https://skillmd.com/category/security) · [Integrations & APIs](https://skillmd.com/category/integrations) · [all categories](https://skillmd.com/categories)
- **By people:** [publishers](https://skillmd.com/publishers) · [official skills from verified publishers](https://skillmd.com/browse/official) · [leaderboard](https://skillmd.com/browse/top) · [new this week](https://skillmd.com/browse/latest)

### Publish yours

```bash
npx skillmds publish ./my-skill
```

You get a page at `skillmd.com/skills/<you>/<name>`, a safety verdict, one-command installs for every agent, and a live README badge. Guides: [Publishing a skill](https://skillmd.com/blog/publishing-a-skill-to-the-registry) · [Writing skills that get used](https://skillmd.com/blog/writing-skills-that-get-used) · [The SKILL.md format](https://skillmd.com/docs/format)

### Read

[The complete guide to AI agent skills](https://skillmd.com/blog/ai-agent-skills-complete-guide) · [Agent Skills vs MCP servers](https://skillmd.com/blog/agent-skills-vs-mcp-servers) · [One SKILL.md for every agent](https://skillmd.com/blog/one-skill-md-for-every-agent-compatibility-matrix) · [The case for an open skill format](https://skillmd.com/blog/the-case-for-an-open-skill-format)

---

<p align="center">
  Machine-readable: <a href="https://skillmd.com/llms.txt">llms.txt</a> · <a href="https://skillmd.com/openapi.json">OpenAPI</a> · <a href="https://skillmd.com/stats">live stats</a><br>
  Security reports and everything else: <a href="mailto:hi@skillmd.com">hi@skillmd.com</a>
</p>
