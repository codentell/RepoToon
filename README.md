# 📖 RepoToon

**Nobody reads release notes. Everybody reads webtoons.**

RepoToon is an autonomous studio agent on [Guild.ai](https://guild.ai) that
turns every GitHub release into a webtoon episode — automatically, with no
human in the loop.

**Read the saga:** https://codentell.github.io/RepoToon/

## The loop

1. A maintainer publishes a GitHub release
2. Guild's GitHub `release` trigger fires the **release-arc** agent
3. The agent dramatizes the changelog into panels — bug fixes become defeated
   monsters, features become new allies, breaking changes become boss battles
4. It draws each panel and commits the episode to `docs/episodes/`
5. GitHub Pages publishes the new episode seconds later

Every panel cites the changelog entry it was drawn from — so the comic is
not just charming, it's *accurate*. Breaking changes can't blindside you if
they're a full-width boss battle.

## Meta

This repo is its own demo: RepoToon is subscribed to **this repository's**
releases. Publishing a release of RepoToon generates a new episode of
RepoToon, by RepoToon.

## The cast

- **Rune, the patch-knight** — our hero, wielder of the Semicolon Blade
- **Bugs** — the monsters of the Repo Realm
- **Features** — allies who join the party
- **Breaking changes** — bosses, announced with a full-width battle panel

## Stack

- [Guild.ai](https://guild.ai) — agent runtime, GitHub integration, webhook trigger
- GitHub Releases — the source material
- GitHub Pages — the publishing house
