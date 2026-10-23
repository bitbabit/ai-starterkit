# AI Hackathon Starter Kit

A lightweight, challenge-agnostic starter kit for a 24-hour AI hackathon.

**Operating principle:** Strong foundations now. Working MVP first. Enhancements only after verification.

## Start here

1. Read the event rules and confirm the permitted AI tools, credentials, repositories, data, and spending limits.
2. At kickoff, fill in `docs/requirements.md` and `docs/acceptance-criteria.md`.
3. Agree on the smallest end-to-end workflow that demonstrates the solution's value.
4. Assign owners, create a short task board, and integrate code frequently.
5. Get the application running early; test the core journey before adding enhancements.
6. Reserve time for a clean run, demo rehearsal, and final submission.

## Repository map

- `docs/`: challenge, architecture, decisions, API contracts, and demo notes.
- `prompts/`: reusable prompts for planning, implementation, review, testing, and debugging.
- `tests/`: smoke tests, edge cases, and AI evaluation examples.
- `scripts/`: optional generic helper scripts.
- `.github/`: optional pull request template and CI workflow.

This kit intentionally does **not** prescribe a framework, model provider, database, vector store, or deployment platform. Choose them after the challenge is announced.

## Guardrails

- Follow event rules over this template.
- Use only approved AI accounts, tools, keys, and quotas.
- Never commit secrets, personal data, or unapproved challenge material.
- Do not implement the challenge before kickoff if the event prohibits it.
- Commit small, coherent changes and keep the main branch runnable.
- Do not add a cache, RAG pipeline, agent framework, local LLM, or extra database unless the MVP needs it.
- Do not modify the solution during an official scoring window if the rules prohibit it.

## Quick setup

Copy this folder into the team repository, then tailor the scripts and CI to the chosen stack. Review every dependency's license and security posture before adding it.

The shell scripts are examples; adapt them to your environment before running.
