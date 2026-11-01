# Skill marketplace (aamu-skills)

`.claude-plugin/marketplace.json` turns the skills in these repositories into Claude Code plugins:

| Plugin | Repository | Skills |
|---|---|---|
| ultra-prompt | Ultra-Prompt | 1 |
| huashu-design | huashu-design | 1 |
| logo-design | logo-design-skill | 1 |
| orca | orca | 11 |
| awesome-llm-apps | awesome-llm-apps | 9 |
| awesome-python | awesome-python | 4 |
| rea | rea | 5 |
| mattpocock-skills | skills | the repo's own promoted set |
| awesome-claude-skills-core | awesome-claude-skills | 31 (Composio `*-automation` skills left out) |
| mirofish | MiroFish | 1 |
| awesome-lists | awesome | 1 |
| saasify | saasify | 1 |

Claude-Code-Game-Studios is not included: its skills need that repo's agents and hooks, so they work when Claude Code is opened inside that repo.

## Install (Claude Code)

```
/plugin marketplace add aamutakaliman-gif/Ultra-Prompt
/plugin install ultra-prompt@aamu-skills
```

Repeat `/plugin install <plugin>@aamu-skills` for each plugin you want, or browse them with `/plugin`.
Update later with `/plugin marketplace update aamu-skills`.

## claude.ai app

The claude.ai app does not read plugin marketplaces. Upload each skill as a ZIP in Settings > Capabilities > Skills.
