# wopr-plugin-provider-codex

Codex agent SDK provider for WOPR. Uses the OpenAI Codex/Assistants API.

## Commands

```bash
npm run build     # tsc
npm run check     # biome check + tsc --noEmit (run before committing)
npm run format    # biome format --write src/
npm test          # vitest run
```

## Key Details

- Implements `ProviderPlugin` from `@wopr-network/plugin-types`
- Uses `@anthropic-ai/claude-agent-sdk` at v2+ — check SDK docs before making API changes
- Configured via plugin config schema

## Plugin Contract

Imports only from `@wopr-network/plugin-types`. Never import from `@wopr-network/wopr` core.

## Issue Tracking

All issues in **Linear** (team: WOPR). Issue descriptions start with `**Repo:** wopr-network/wopr-plugin-provider-codex`.
