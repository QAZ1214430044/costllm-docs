# CostLLM

**OpenAI-Compatible API Gateway** — virtual keys, budgets, rate limits, and usage tracking. 

[https://costllm.ai](https://costllm.ai)

## What is CostLLM?

CostLLM is a drop-in API gateway that's fully compatible with the OpenAI API format. Route all your AI API calls through CostLLM and get:

- **Virtual Keys** — Create multiple API keys with different providers and models under a single endpoint
- **Budgets & Rate Limits** — Set spending caps and request rate limits per key or per user
- **Usage Tracking** — Monitor token usage and costs across all your keys in one dashboard
- **Multi-Provider** — Switch between OpenAI, Anthropic, Google, Groq, DeepSeek, and more without changing your code

## Quick Start

`ash
# Just change the base URL
curl https://api.costllm.ai/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_COSTLLM_KEY" \
  -d '{"model": "gpt-4o", "messages": [{"role": "user", "content": "Hello!"}]}'
`

One line change — replace pi.openai.com with pi.costllm.ai and you're done.

## Free Tier

New users get **\ in free credits** with promo code **BETA20**. No credit card required.

Try it at [costllm.ai](https://costllm.ai)
