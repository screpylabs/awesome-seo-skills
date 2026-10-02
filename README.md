# Awesome SEO Skills

> A curated list of high-quality **SEO skills** for AI agents: technical SEO audits, keyword research, content optimisation, programmatic SEO, schema markup, and GEO/AEO.

AI agent skills are reusable instructions, workflows, and tools that help agents perform focused work reliably. This list helps SEO teams find skills worth reviewing before they install or adapt them.

## Contents

- [What makes an SEO skill useful?](#what-makes-an-seo-skill-useful)
- [Technical SEO and audits](#technical-seo-and-audits)
- [Content, keywords, and programmatic SEO](#content-keywords-and-programmatic-seo)
- [GEO and answer engine optimisation](#geo-and-answer-engine-optimisation)
- [Schema and structured data](#schema-and-structured-data)
- [Use skills safely](#use-skills-safely)
- [Contributing](#contributing)

## What makes an SEO skill useful?

The best SEO skills are specific about their inputs, evidence, and outputs. They should help an agent inspect real pages or data, separate facts from assumptions, prioritise work by impact, and return actionable fixes rather than generic SEO advice.

This list favours skills that have a public source, a clear `SKILL.md`-style workflow, and a defined SEO use case. Inclusion is not an endorsement or a security guarantee.

## Technical SEO and audits

| Skill | Best for | Notes |
| --- | --- | --- |
| [SEO Audit](https://www.skills.sh/coreyhaines31/marketingskills/seo-audit) | Crawlability, indexation, speed, on-page SEO, content quality, and authority checks | A structured general-purpose audit framework with prioritised remediation. |
| [Codex SEO](https://github.com/AgriciDaniel/codex-seo) | Codex-first technical SEO, Core Web Vitals, schema, backlinks, local SEO, maps, and reporting | A full suite with specialist workflows, agents, scripts, tests, and optional data integrations. |
| [Agentic SEO Skill](https://github.com/Bhanunamikaze/Agentic-SEO-Skill) | Technical audits, JavaScript rendering, sitemaps, performance, visual analysis, and GitHub SEO | Broad multi-skill package; review its Python and optional Playwright requirements first. |
| [Claude SEO](https://github.com/AgriciDaniel/claude-seo) | Claude-oriented audit and research workflows | The Claude counterpart to a larger SEO workflow ecosystem. |
| [NotFair SEO Drift](https://github.com/nowork-studio/NotFair/tree/main/seo/seo-drift) | Baseline-and-compare monitoring for rankings, indexation, metadata, canonical/noindex directives, schema, and on-page elements | Optional connected Google Search Console data is available through a hosted NotFair MCP connection; live-page inputs work without it. |

## Content, keywords, and programmatic SEO

| Skill | Best for | Notes |
| --- | --- | --- |
| [Programmatic SEO](https://www.skills.sh/coreyhaines31/marketingskills/programmatic-seo) | Templates, directories, comparison pages, locations, integrations, and glossaries | Focuses on quality controls, search intent, internal linking, and avoiding thin pages. |
| [SEO Blog Post Optimizer](https://github.com/WesleySmits/agent-skills/tree/main/.agent/skills/seo-blog-post-optimizer) | Improving an existing article | Useful as a compact workflow for content refreshes and on-page improvements. |
| [SEO Keyword Research](https://github.com/WesleySmits/agent-skills/tree/main/.agent/skills/seo-keyword-research) | Keyword expansion and intent analysis | A small, inspectable skill for planning content around demand and intent. |
| [SEO Metadata Generator](https://github.com/WesleySmits/agent-skills/tree/main/.agent/skills/seo-metadata-generator) | Titles, descriptions, Open Graph metadata, and JSON-LD | Use with page-level review; generated metadata should not replace intent research. |

## GEO and answer engine optimisation

GEO, AEO, and AI search optimisation complement traditional SEO. The goal is to make accurate, well-structured pages easier for answer engines to retrieve, summarise, and cite; it is not a substitute for crawlability, useful content, or search demand.

| Skill | Best for | Notes |
| --- | --- | --- |
| [SEO/GEO](https://www.skills.sh/resciencelab/opc-skills/seo-geo) | Traditional search plus AI search engines | Covers technical checks, content structure, AI bot access, and schema-related work. |
| [Generative Engine Optimization](https://www.skills.sh/kostja94/marketing-skills/generative-engine-optimization) | GEO/AEO strategy | A narrower playbook for citation visibility in AI-generated answers. |
| [GEO Audit](https://www.skills.sh/zubair-trabzada/geo-seo-claude/geo-audit) | A website-level GEO readiness audit | Useful for turning AI-search findings into a prioritised improvement plan. |
| [LogNorm](https://github.com/lognorm/lognorm-mcp/tree/main/skills/lognorm) | Working a site's SEO and AI-visibility (GEO) backlog from an agent: audits, fixes, content, and AI-answer tracking | Uses the hosted LogNorm MCP server (OAuth, no API key); needs a LogNorm account (free plan available). Reads site audit and Search Console data; fixes are made in your repo. |

## Schema and structured data

| Skill | Best for | Notes |
| --- | --- | --- |
| [Schema Markup Generator](https://www.skills.sh/openclaw/skills/schema-markup-generator) | Drafting structured data | Validate generated markup against the appropriate search-engine tooling before publishing. |

## Use skills safely

1. Read the full skill and its scripts before installation.
2. Prefer direct vendor or repository sources over mirrors.
3. Test on a staging site or a small, non-critical project first.
4. Keep API keys and Search Console credentials outside the repository.
5. Verify SEO recommendations against current search-engine documentation and real crawl, performance, and search data.

## Related resources

- [Awesome SEO Tools](https://screpy.com/awesome-seo-tools/) — a directory of SEO tools by workflow.
- [Screpy](https://screpy.com/) — website audit, rank tracking, monitoring, and SEO reporting.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md), then open a pull request that explains the skill's source, SEO use case, dependencies, and why it belongs in this list.

## License

[MIT](LICENSE)
