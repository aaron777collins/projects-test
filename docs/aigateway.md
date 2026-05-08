# aigateway

## 🔗 Quick Links

- [View on GitHub](https://github.com/aaron777collins/aigateway)

## 📊 Project Details

- **Primary Language:** HTML
- **Languages Used:** HTML, JavaScript, Dockerfile
- **License:** None
- **Created:** May 07, 2026
- **Last Updated:** May 08, 2026

## 📝 About

# AI Gateway - 3-Tier LiteLLM Proxy

A self-hosted LiteLLM proxy that exposes a single OpenAI-compatible API endpoint (`localhost:4000`) backed by three named model tiers — `smart`, `normal`, and `fast` — each with an ordered fallback chain spanning Ollama Cloud, OpenRouter free models, and local Ollama models. The gateway is bound to `127.0.0.1` only and is never exposed to the public internet.

## Quick Start

```bash
# 1. Copy the example config and fill in your keys
cp litellm_config.exa

