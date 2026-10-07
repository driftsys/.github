# driftsys

Open source tooling and processes for safety-critical embedded systems.

We explore how modern software engineering — Rust, code-as-everything, reactive
architectures — can work inside regulated environments like automotive,
avionics, rail, and medical devices, without fighting the compliance frameworks
already in place.

## Principles

Safety, security, and performance come first.

- Everything as code
- Simplicity as a discipline
- Progressive adoption
- Compatibility with existing toolchains
- Fault avoidance by design

> Failures will happen — defects don't have to. We prevent them by design and
> mitigate so they never become faults.

## AI policy

We use [Anthropic] and accept AI-assisted contributions, in the spirit of the
[Linux Foundation Generative AI Policy][lf-ai]. We prefer providers that are
[Frontier AI Safety Commitments][faisc] signatories. Humans decide, AI
assists. Same review and quality bar for all code.

## Projects

### Process and compliance

| Project      | Description                                                                   |
| ------------ | ----------------------------------------------------------------------------- |
| [markspec]   | Markdown flavor and toolchain for traceable industrial documentation          |
| [refhub]     | [Registry][refhub-site] of standards, regulations, and technical publications |

### System modeling and runtimes

| Project            | Description                                                                |
| ------------------ | -------------------------------------------------------------------------- |
| [ridl]             | Family of languages for modeling component-based reactive systems          |
| [dashscene]        | Figma-to-pixels rendering pipeline for embedded displays (experimental)    |
| [safeio]           | Deterministic async runtime for safety-critical systems (future work)      |

### Repository and release tooling

| Project     | Description                                                                     |
| ----------- | ------------------------------------------------------------------------------- |
| [git-std]   | Conventional commits, versioning, changelog, and release management in one tool |
| [prim]      | Zero-config formatter for Markdown, JSON/JSONC, YAML, and TOML                  |
| [folio]     | Reference CLI for the Repofolio standard (pre-alpha)                            |
| [schemas]   | JSON Schemas for project manifests and tooling configuration                    |
| [dock]      | Lean, layered CI Docker images                                                  |
| [ci]        | Reusable GitHub Actions and GitLab CI components                                |

### Coding agents

| Project        | Description                                                                 |
| -------------- | --------------------------------------------------------------------------- |
| [upskill]      | Lightweight package manager for agent rules, skills, and agents             |
| [metapowers]   | Skills registry extending Superpowers with durable engineering records      |
| [diagctl]      | CLI for the metapowers tech-diagramming quality gate                        |

### Publications

| Project        | Description                                                        |
| -------------- | ------------------------------------------------------------------ |
| [context-book] | [Reference book][context-book-site] on context engineering (EN/FR) |

### Planning

| Project | Description                                                 |
| ------- | ----------------------------------------------------------- |
| [board] | Cross-cutting planning — epics, ADRs, and program management |

## Contact

- General: <contact@driftsys.org>
- Security: <security@driftsys.org>

[markspec]: https://github.com/driftsys/markspec
[refhub]: https://github.com/driftsys/refhub
[refhub-site]: https://driftsys.github.io/refhub/
[ridl]: https://github.com/driftsys/ridl
[dashscene]: https://github.com/driftsys/dashscene
[safeio]: https://github.com/driftsys/safeio
[git-std]: https://github.com/driftsys/git-std
[prim]: https://github.com/driftsys/prim
[folio]: https://github.com/driftsys/folio
[schemas]: https://github.com/driftsys/schemas
[dock]: https://github.com/driftsys/dock
[ci]: https://github.com/driftsys/ci
[upskill]: https://github.com/driftsys/upskill
[metapowers]: https://github.com/driftsys/metapowers
[diagctl]: https://github.com/driftsys/diagctl
[context-book]: https://github.com/driftsys/context-book
[context-book-site]: https://driftsys.github.io/context-book/
[board]: https://github.com/driftsys/board
[faisc]: https://www.gov.uk/government/publications/frontier-ai-safety-commitments-ai-seoul-summit-2024
[Anthropic]: https://www.anthropic.com
[lf-ai]: https://www.linuxfoundation.org/blog/linux-foundation-generative-ai-policy
