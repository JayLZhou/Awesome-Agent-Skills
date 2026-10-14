# Awesome Agent Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A **small, verified, security-aware** list of Agent Skills (the [SKILL.md](https://agentskills.io/specification) format used by Claude Code, Cursor, Codex, and more), curated for trust, not a 1,400-skill dump.

A skill is a folder with a SKILL.md that teaches an agent a workflow. The ecosystem exploded, and so did the risk: a skill is code the agent trusts, and Snyk found prompt injection in **36% of tested skills** while Trail of Bits showed the public scanners are bypassable in under an hour. Most lists optimize for count. This one optimizes for signal: the official sources, a tight set of genuinely useful skills, and a first-class security section the volume lists skip.

**Browse and filter: [agent-skills.agentpostmortem.com](https://agent-skills.agentpostmortem.com)**

## Start here: how to think about skills

- **A skill is untrusted code** until you have read its SKILL.md and any scripts. Treat installing one like adding a dependency, or running a stranger's shell script.
- **The trigger description is the security boundary.** The model loads a skill based on its description; a poisoned description is how injection gets in.
- **Scan before you install.** Use a skill scanner (below), and prefer skills from teams you can name.
- **Author for progressive disclosure.** A good skill keeps SKILL.md short and links out to details the agent pulls only when needed.

**The one rule:** volume is not trust. A verified skill from a known team beats a hundred you have not read.

<!-- LIST:START -->
**48 entries**, auto-refreshed weekly. Star counts updated **2026-09-28**. Browse the filterable version at **[agent-skills.agentpostmortem.com](https://agent-skills.agentpostmortem.com)**.

### Official and spec

- [anthropics/skills](https://github.com/anthropics/skills) `* 178.8k`: Anthropic's official public repo: production document skills (docx, pdf, pptx, xlsx), a skill template, skill-creator, and the spec.
- [agentskills/agentskills](https://github.com/agentskills/agentskills) `* 25.8k`: Specification and documentation repository for the open Agent Skills standard.
- [Agent Skills Specification](https://agentskills.io/specification): The open, vendor-neutral standard for the SKILL.md format, adopted beyond Claude.
- [Agent Skills overview (Claude docs)](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview): Official docs on what skills are, how discovery and loading works, and how to build them.
- [Introducing Agent Skills (Anthropic)](https://claude.com/blog/skills): The launch announcement of Agent Skills as an open standard, plus the design deep-dive.
- [Claude Skills gallery](https://claude.com/skills): Anthropic's official gallery of prebuilt skills (PowerPoint, Excel, Word, PDF, and more).

### Skill collections

- [obra/superpowers](https://github.com/obra/superpowers) `* 292.4k`: Jesse Vincent's agentic skills framework and methodology: a large library of composable skills, in Claude Code's official marketplace.
- [trailofbits/skills](https://github.com/trailofbits/skills) `* 7.3k`: Trail of Bits' security-research skills for vulnerability detection and audit workflows, installable as a plugin marketplace.
- [NotFair Plugin](https://github.com/nowork-studio/notfair-plugin) `* 3.9k`: Open-source SEO, GEO, paid-media, and analytics workflows for AI agents.
- [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace) `* 1.3k`: Curated Claude Code plugin marketplace for installing the Superpowers skill collections.
- [getsentry/skills](https://github.com/getsentry/skills) `* 1k`: Sentry's official skills, including a skill-scanner for reviewing untrusted skills.
- [vostride/agent-qa skills](https://github.com/vostride/agent-qa/tree/main/skills) `* 889`: Three Agent Skills for authoring QA tests, debugging failures, and triaging results in web and mobile app testing.
- [obra/superpowers-skills](https://github.com/obra/superpowers-skills) `* 748`: The community-editable skills library behind the Superpowers plugin.
- [OrkasVideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) `* 496`: MIT-licensed, local-first TypeScript CLI and MCP toolkit for coding agents to compose, edit, generate, and assemble videos from editable plan.json timelines.
- [obra/superpowers-lab](https://github.com/obra/superpowers-lab) `* 430`: Experimental Superpowers skills exploring new techniques for Claude Code.
- [Hyperconsciousness skills](https://github.com/louis030195/hyperconsciousness/tree/main/skills) `* 2`: Developer-alpha skills for local knowledge discovery and grant-scoped encrypted store operations, with installation support for Claude Code, Codex, Hermes and pi.
- [AgentBody Skills](https://github.com/agentbody/skills) `* 1`: AgentBody's public skills collection, including X Research for read-only public X/Twitter search, trends, profiles, posts, media, and replies. Requires a commercial AgentBody API key.
- [AgentBody Skills](https://github.com/agentbody/skills) `* 1`: AgentBody's public skills collection, including X Research for read-only public X/Twitter search, trends, profiles, posts, media, and replies. Requires a commercial AgentBody API key.
- [distro-skills](https://github.com/royalpinto007/distro-skills) `* 0`: 26 Agent Skills that teach an agent to distribute a dev or indie product across GitHub, HN, Reddit, dev.to, and more.
- [alapha888/agent-skills-en](https://github.com/alapha888/agent-skills-en): Five MIT-licensed productivity skills for AI coding agents: meeting notes, code review checklist, deep research framework, tech writing proofread, and git commit messages.
- [LogNorm](https://github.com/lognorm/lognorm-mcp/tree/main/skills/lognorm): Work a site's SEO and AI-visibility (GEO) backlog through the hosted LogNorm MCP server: audits, fixes, content, AI-answer tracking. Needs a LogNorm account (free plan available).
- [Darkmoon pentest skill](https://github.com/ASCIT31/darkmoon-mcp-server/tree/main/plugins/darkmoon/skills/darkmoon-pentest): Skill and MCP plugin to start authorized autonomous AI pentest runs on your own self-hosted Darkmoon Pro, poll them and triage findings. Needs a Darkmoon Pro dashboard; the open source (GPL-3.0) engine alone is not enough.
- [Solaris Dev Shop](https://github.com/Shaisolaris/solaris-dev-shop): Free MIT skill library whose chief of staff assigns one specialist to a task.
- [looot-skills](https://github.com/loootai/looot-skills): 20 business-data skills (email finding, company and people enrichment, web search, local leads) plus a base skill, backed by the hosted looot MCP server. Needs a looot API key and prepaid balance.

### Coding and review

- [borghei/Claude-Skills](https://github.com/borghei/Claude-Skills) `* 848`: Engineering-focused skill collection including a skill-security-auditor for reviewing code and skills.
- [superpowers-developing-for-claude-code](https://github.com/obra/superpowers-developing-for-claude-code) `* 142`: Skills that teach an agent to build for and extend Claude Code itself.
- [orca-replay](https://github.com/Continuum-AI-Corp/OrcaReplay/tree/main/skills/orca-replay): Teaches an agent to answer questions about an earlier run from its recording instead of from memory, and to replay or fork that run, for developers debugging why a past session did what it did.
- [cloudish](https://github.com/cloudishai/skills/tree/main/skills/cloudish): Teaches an agent to deploy a Dockerfile, source folder, or container image to Cloudish and report the live URL, minting its own API key with no signup, for developers who want their agent to put an app, API, or bot online.

### Docs and writing

- [anthropics/skills, docx](https://github.com/anthropics/skills/tree/main/skills/docx): The production Word-document skill that powers Claude's docx creation and editing.
- [anthropics/skills, document skills](https://github.com/anthropics/skills/tree/main/skills): Source-available PDF, PowerPoint, and Excel skills used in production by Claude.

### Security and validation

- [skill-audit](https://github.com/royalpinto007/Skill-audit) `* 3`: Security scanner for agent skills: 31 rules, prompt-injection and exfiltration detection, SARIF output, npx skill-audit.
- [SecHelix](https://github.com/omarmohelal/SecHelix) `* 1`: Evidence-first AppSec review skill that sends every candidate finding to an independent verifier before reporting it, for developers auditing code they are authorized to test.
- [Snyk: ToxicSkills study](https://snyk.io/blog/toxicskills-malicious-ai-agent-skills-clawhub/): Research finding prompt injection in 36 percent of tested skills and 1,467 malicious payloads across the skill supply chain.
- [Trail of Bits: skill distribution](https://blog.trailofbits.com/2026/06/03/the-sorry-state-of-skill-distribution/): Shows every public skill scanner (ClawHub, Cisco skill-scanner, skills.sh) is bypassable in under an hour.
- [OWASP Agentic Skills Top 10](https://owasp.org/www-project-agentic-skills-top-10/): OWASP project cataloguing the top security risks specific to agent skills.
- [Sentry skill-scanner](https://github.com/getsentry/skills/blob/main/skills/skill-scanner/SKILL.md): A skill that scans other skills for prompt injection, exfiltration, and dangerous code before install.

### Authoring and validation

- [skill-creator (Anthropic)](https://github.com/anthropics/skills/blob/main/skill-creator/SKILL.md): Official meta-skill that interviews you, writes a SKILL.md with good trigger descriptions, and packages a skill bundle.
- [ComposioHQ skill-creator](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/skill-creator/SKILL.md): Modular authoring framework for designing, refactoring, and packaging skills with progressive disclosure.
- [skillsbench](https://deepwiki.com/benchflow-ai/skillsbench): Benchmark plus skill creation and validation tooling for evaluating skill quality.

### Marketplaces and directories

- [BulkPublish social media content skills](https://github.com/azeemkafridi/bulkpublish-api/tree/main/skills/social-media-content-skills) `* 1`: Open-source skills for approval-first social content adaptation, scheduling, and publishing through BulkPublish API and MCP.
- [claudemarketplaces.com](https://claudemarketplaces.com/): Directory of Claude Code skills, plugins, and MCP servers with thousands of registered marketplaces.
- [LobeHub Skills](https://lobehub.com/skills): Cross-agent skills marketplace (Claude Code, Codex CLI, ChatGPT) built on the open SKILL.md format.
- [agentskill.sh](https://agentskill.sh/): Skills directory with one-command install across Claude Code, Cursor, Copilot, Codex, Windsurf, Zed, and more.

### Guides

- [Simon Willison: skills](https://simonwillison.net/tags/skills/): Ongoing practitioner commentary and worked examples on building and using Agent Skills.
- [Anthropic Skills explained](https://localskills.sh/blog/anthropic-skills-explained): Explainer walking through the official repo, the docs, and how the format works.

### Related lists

- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) `* 75.8k`: 1,000-plus production skills and plugins organized by use case, with a skill-creator bundled in-repo.
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) `* 35k`: The largest list by reach: 1,400-plus hand-picked skills from real engineering teams, cross-tool.
- [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills) `* 526`: 50-plus verified skills across 12 categories, actively maintained with verified badges.

<!-- LIST:END -->

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Edit `data/tools.json`, run `node scripts/generate.mjs`, open a PR.

## License

[CC0 1.0](LICENSE) (public domain).
