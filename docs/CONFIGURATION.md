# OpenAI Configuration

## Required Settings

| Option | Type | Required | Description |
|--------|------|----------|-------------|
| `apiKey` | string | **Yes** | OpenAI API key |

## Optional Settings

| Option | Type | Default | Description |
|--------|------|---------|-------------|
| `defaultModel` | string | `"gpt-4"` | Default GPT model |
| `maxTokens` | number | `4096` | Maximum tokens |
| `temperature` | number | `0.7` | Sampling temperature |
| `organization` | string | - | OpenAI organization ID |

## Available Models

| Model | Context | Speed | Best For |
|-------|---------|-------|----------|
| `gpt-4` | 8K | Medium | Complex reasoning |
| `gpt-4-turbo` | 128K | Medium | Large context |
| `gpt-3.5-turbo` | 16K | Fast | Simple tasks |

## Configuration Example

```json
{
  "apiKey": "sk-...",
  "defaultModel": "gpt-4",
  "maxTokens": 4096,
  "temperature": 0.7
}
```

## Environment Variable

```bash
export OPENAI_API_KEY="sk-..."
```

## Troubleshooting

**"Incorrect API key"**
- Get key from https://platform.openai.com/api-keys
- Check for typos or extra spaces
- Verify key is not expired

**"Quota exceeded"**
- Check billing at https://platform.openai.com/account/billing
- Add payment method if needed
- Review usage limits
