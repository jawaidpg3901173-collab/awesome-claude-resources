# Awesome Claude Resources

The best Claude **skills**, **plugins** and **connectors (MCP servers)** in one place.

Every project below belongs to its original authors. Each entry links to the original repository, which is always the most up-to-date version, and to a fork kept on this account. Please star the originals and follow their licenses.

---

## 1. Official: Anthropic and GitHub

Start here. These are maintained by the companies themselves.

| Repository | What's inside | Fork |
|---|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) | Anthropic's official Agent Skills (Word, Excel, PowerPoint, PDF and more) and the skills spec | [fork](https://github.com/jawaidpg3901173-collab/skills) |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Anthropic's official plugin marketplace (300+ plugins) | [fork](https://github.com/jawaidpg3901173-collab/claude-plugins-official) |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | Work plugins: productivity, sales, support, product, marketing, legal, finance, data, enterprise search, bio-research | [fork](https://github.com/jawaidpg3901173-collab/knowledge-work-plugins) |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code: changelog, issues and example plugins | [fork](https://github.com/jawaidpg3901173-collab/claude-code) |
| [github/github-mcp-server](https://github.com/github/github-mcp-server) | GitHub's official MCP connector for repos, issues, PRs and Actions | [fork](https://github.com/jawaidpg3901173-collab/github-mcp-server) |

## 2. Directories: find everything else

Large curated lists. Use these to discover more.

| Repository | What's inside | Fork |
|---|---|---|
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | The main hand-picked list of skills, hooks, slash commands, plugins and tools | [fork](https://github.com/jawaidpg3901173-collab/awesome-claude-code) |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | The largest list of MCP connectors (web directory: [glama.ai/mcp/servers](https://glama.ai/mcp/servers)) | [fork](https://github.com/jawaidpg3901173-collab/awesome-mcp-servers) |
| [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) | A second, independently curated MCP list | [fork](https://github.com/jawaidpg3901173-collab/awesome-mcp-servers-wong2) |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Curated skills and ready-made workflows for 78 SaaS apps | [fork](https://github.com/jawaidpg3901173-collab/awesome-claude-skills) |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 1,000+ skills for Claude and other agents | [fork](https://github.com/jawaidpg3901173-collab/awesome-agent-skills) |
| [quemsah/awesome-claude-plugins](https://github.com/quemsah/awesome-claude-plugins) | Automatically updated index of about 15,000 plugin repositories | [fork](https://github.com/jawaidpg3901173-collab/awesome-claude-plugins) |
| [rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit) | Agents, skills, commands, hooks and MCP configs in one toolkit | [fork](https://github.com/jawaidpg3901173-collab/awesome-claude-code-toolkit) |

## 3. Skill packs and frameworks

| Repository | What's inside | Fork |
|---|---|---|
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 177 science skills and 100+ scientific databases (genomics, clinical, drug discovery, data analysis) | [fork](https://github.com/jawaidpg3901173-collab/scientific-agent-skills) |
| [obra/superpowers](https://github.com/obra/superpowers) | The most popular skills framework, focused on software development | [fork](https://github.com/jawaidpg3901173-collab/superpowers) |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | Everything Claude Code: agents, skills, memory and security checks | [fork](https://github.com/jawaidpg3901173-collab/ECC) |
| [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | Guide to CLAUDE.md, skills, hooks, sub-agents and context engineering | [fork](https://github.com/jawaidpg3901173-collab/claude-code-best-practice) |

## 4. App connectors

| Repository | What's inside | Fork |
|---|---|---|
| [mikechambers/adb-mcp](https://github.com/mikechambers/adb-mcp) | Connects Claude to Adobe Photoshop and other Adobe apps | [fork](https://github.com/jawaidpg3901173-collab/adb-mcp) |

---

## How to install

- **Claude app (Cowork):** browse and add plugins at [claude.com/plugins](https://claude.com/plugins/), and connectors under Settings → Connectors.
- **Claude Code plugins:**
  ```bash
  claude plugin marketplace add anthropics/knowledge-work-plugins
  claude plugin install sales@knowledge-work-plugins
  ```
- **Skills:** copy a skill folder (the one containing `SKILL.md`) into `~/.claude/skills/`, or upload it in the Claude app under Settings → Capabilities → Skills.

## Safety

Skills, plugins and MCP servers can run code on your computer. Read a repository before installing it, install only what you need, and check with your IT team before installing on a work device.

## Credits and licenses

All content belongs to the original authors and is shared under each repository's own license. This page only collects links. Forks here may lag behind the originals, so always use the original link for the latest version.
