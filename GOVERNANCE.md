# Governance

This document describes how the Wabi Saby organization and its projects are governed.

## Scope

Wabi Saby is a music streaming platform that aggregates content from multiple sources through plugins. The [wabisaby](https://github.com/wabisaby) organization hosts:

- **Core platform** — Backend, API, plugin runtime, and services ([wabisaby-core](https://github.com/wabisaby/wabisaby-core)).
- **Developer tooling** — DevKit desktop app and meta-repo ([wabisaby-devkit](https://github.com/wabisaby/wabisaby-devkit)), plugin SDK ([wabisaby-plugin-sdk-go](https://github.com/wabisaby/wabisaby-plugin-sdk-go)), and shared protos ([wabisaby-protos](https://github.com/wabisaby/wabisaby-protos)).
- **Plugins** — Official and community plugins ([wabisaby-plugins](https://github.com/wabisaby/wabisaby-plugins)).

## Roles

- **Maintainers** — Have write or admin access to one or more repositories. They review and merge pull requests, triage issues, and guide the technical direction of their area.
- **Contributors** — Anyone who opens issues, discussions, or pull requests. Contributions are welcome and follow the [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing](CONTRIBUTING.md) guidelines.

Role assignments (who is a maintainer for which repo) are managed via GitHub repository permissions. There is no separate formal “governance body”; decisions are made by maintainers in the scope of their repos, with input from the community.

## Decision making

- **Code and design** — Proposals are discussed in issues or discussions. Maintainers of the affected repo(s) decide on changes, with preference for consensus and clear rationale.
- **New repos or major scope changes** — Handled by organization owners and maintainers; significant changes can be announced in Discussions or release notes.
- **Disputes or conduct** — Addressed according to the [Code of Conduct](CODE_OF_CONDUCT.md); reports are handled by maintainers or org owners.

## Transparency

- Development happens in the open: code, issues, and discussions are public where the repo is public.
- Roadmaps and priorities may be documented in repo READMEs, docs, or GitHub Projects; check the relevant repository for up-to-date information.

## Changes to this document

Governance itself can evolve. Proposed changes to this file can be discussed in an issue or discussion in this (`.github`) repository and adopted by organization owners/maintainers.
