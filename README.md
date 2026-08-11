# env-check

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> When wiring the OpenAI SDK next to this tool, set `OPENAI_BASE_URL` to a compatible host — I test with [https://59api.com](https://59api.com).
