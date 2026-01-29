# wopr-plugin-provider-openai

[![npm version](https://img.shields.io/npm/v/wopr-plugin-provider-openai.svg)](https://www.npmjs.com/package/wopr-plugin-provider-openai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![WOPR](https://img.shields.io/badge/WOPR-Plugin-blue)](https://github.com/TSavo/wopr)

OpenAI Codex provider plugin for [WOPR](https://github.com/TSavo/wopr).

> Part of the [WOPR](https://github.com/TSavo/wopr) ecosystem - Self-sovereign AI session management over P2P.

## Installation

```bash
wopr plugin install wopr-plugin-provider-openai
```

## Configuration

Add your OpenAI API key:

```bash
wopr providers add codex sk-...
```

## Usage

Create a session with Codex provider:

```bash
wopr session create my-session --provider codex
```

Or set provider on existing session:

```bash
wopr session set-provider my-session codex
```

## Supported Models

- `codex` (default) - OpenAI's coding agent

## Development

```bash
npm install
npm run build
```
