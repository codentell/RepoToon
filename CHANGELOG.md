# Changelog

Release notes here are drawn from real Guild.ai platform capabilities
(https://docs.guild.ai/) — each release dramatizes a slice of the sponsor's
infrastructure that RepoToon itself runs on.

## v0.2.0 — The Guild Awakens

- feat: webhook triggers — agents now fire autonomously when GitHub events occur (https://docs.guild.ai/platform/triggers)
- feat: GitHub integration toolset — agents can read repos and commit files directly (https://docs.guild.ai/integrations/github)
- feat: Agent Hub — publish validated agent versions for the whole organization (https://docs.guild.ai/platform/publish-to-agent-hub)
- feat: sessions — watch every agent run live, tool call by tool call (https://docs.guild.ai/platform/sessions)
- fix: credentials — third-party auth is now centralized, slaying the scattered-API-key hydra (https://docs.guild.ai/platform/credentials)
- BREAKING CHANGE: manual release-note reading is deprecated; all changelogs must now be consumed as webtoon episodes
- chore: bump dependencies

## v0.1.0 — First Panel

- feat: skills — reusable domain knowledge agents activate on demand (https://docs.guild.ai/platform/skills)
- feat: workspaces — shared environments where teams and agents collaborate (https://docs.guild.ai/platform/workspaces)
- fix: context — workspace background knowledge no longer has to be re-explained to every agent (https://docs.guild.ai/platform/context)
- chore: initial CI setup
