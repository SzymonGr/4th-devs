# AI_devs 4: Builders

## Setup

Copy `env.example` to `.env` and set one key:

```
OPENAI_API_KEY=your_api_key_here
```

or

```
OPENROUTER_API_KEY=your_api_key_here
```

If both keys are present, provider defaults to OpenAI. Override with `AI_PROVIDER=openrouter`.

## Lesson 01

| Example | Run | Description |
|---------|-----|-------------|
| `01_01_interaction` | `npm run lesson1:interaction` | Multi-turn conversation via input history |
| `01_01_structured` | `npm run lesson1:structured` | Structured JSON output with schema validation |
| `01_01_grounding` | `npm run lesson1:grounding` | Fact-checked HTML from markdown notes |

Install dependencies (only needed for `01_01_grounding`):

```bash
npm run lesson1:install
```

