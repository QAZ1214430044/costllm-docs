# CostLLM

OpenAI-compatible API gateway â virtual keys, budgets, rate limits, and usage tracking.

ð [costllm.ai](https://costllm.ai) Â· ð [Docs](https://costllm.ai/docs) Â· ð **BETA20** for $15 free credits

## What is CostLLM?

CostLLM helps developers and small teams route AI API calls through a single OpenAI-compatible endpoint while tracking usage, setting budgets, and managing virtual API keys.

## Quick Start

```bash
curl https://api.costllm.ai/v1/chat/completions   -H "Content-Type: application/json"   -H "Authorization: Bearer YOUR_COSTLLM_KEY"   -d '{
    "model": "deepseek-v4-flash",
    "messages": [
      {"role": "user", "content": "Hello!"}
    ]
  }'
```

## Free Credits

New users get $10 free credits.
Use promo code **BETA20** to get $15 total free credits.
No credit card required.

## Links

- Website: https://costllm.ai
- Docs: https://costllm.ai/docs
