# skills

Open-source co-authoring and review skills for creating agent-ready documentation.

## Purpose

`skills` contains reusable skills that help teams elicit requirements, detect ambiguity, and iterate specs to pass explicit quality gates.

## Primary Platforms

- Claude Code
- Codex
- Other agent platforms where portability is practical

## What Belongs Here

- Co-authoring skills for structured elicitation
- Critic/reviewer skills tied to shared rubrics
- Compliance and readiness gate skills
- Platform adapters and compatibility notes

## Design Rules

- Keep behavior deterministic and rubric-bound.
- Separate author and critic responsibilities to reduce blind spots.
- Require concrete findings and patch guidance, not generic feedback.
- Version skill contracts when prompts, schema expectations, or outputs change.

## Typical Layout

When present, content is organized under:

- `claude-code/`
- `codex/`
- `shared/`
- `examples/`
- `docs/`

## Compatibility

Each skill should declare supported `spec-kit` versions and expected inputs/outputs.

## Public Content Policy

All content in this repository is public and intended for open collaboration.

- Do not include confidential, customer-specific, or non-public business information.
- Do not include personal data (PII), credentials, or secrets.

## License

Licensed under the Apache License, Version 2.0. See `LICENSE`.

## Contributing

Contributions are welcome. Read `CONTRIBUTING.md` before opening a PR.
By contributing, you agree your contributions are licensed under Apache-2.0.

## Content And Safety Notes

- Skills are designed to be deterministic and rubric-bound, but outputs may still require human review.
- Do not include proprietary, confidential, or customer-identifying material.
- Do not include personal data (PII), credentials, or secrets.
- Respect platform usage policies and your organization's security/compliance policies.

## Trademarks

"AgentReadyDocs" is a project name. This project is not affiliated with Anthropic, OpenAI, or other platform vendors.
