# Qwen (qwen)

Qwen is Alibaba's large language model family. APIs are exposed via Alibaba Cloud Model Studio (DashScope) with per-token pricing across multiple regions. The qwen.ai consumer site fronts the chat product.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/qwen/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=qwen-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, Open Source, Alibaba, Multimodal

## APIs
- **DashScope (Alibaba Cloud Model Studio) API** — Chat, vision, embeddings, audio (TTS/ASR), image generation, video generation, function calling. DashScope-native + OpenAI-compatible endpoints. Regional base URLs across Singapore (`dashscope-intl`), US-Virginia, HK, Frankfurt, Beijing. [Docs](https://www.alibabacloud.com/help/en/model-studio) · [Pricing](https://www.alibabacloud.com/help/en/model-studio/models) · [GitHub](https://github.com/QwenLM)

### Models
Qwen3-Max, Qwen3.5-Plus, Qwen3.5-Flash, Qwen3-VL-Plus / Flash, Qwen3-Coder, Qwen-Plus / Flash (China), Qwen-VL-OCR. Open-weights: Qwen3-32B/14B/7B, Qwen2.5-72B/32B/Coder.

## Plans, Rate Limits, FinOps
- [Plans](plans/qwen-plans-pricing.yml) — PAYG tiered by context window. Qwen3-Max $1.2/M input @ 32K; Qwen3.5-Flash $0.10/M @ 128K. Free self-hosting for open weights.
- [RateLimits](rate-limits/qwen-rate-limits.yml) — Per-model RPM/TPM and concurrent-task quotas in workspace console.
- [FinOps](finops/qwen-finops.yml) — FOCUS-aligned, billed via Alibaba Cloud invoice.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://qwen.ai/)
- [Documentation](https://www.alibabacloud.com/help/en/model-studio)
- [GitHub](https://github.com/QwenLM)

## Notes
- Public OpenAPI spec was not discovered for DashScope at the time of profiling; the OpenAI-compatibility surface follows the standard OpenAI spec shape.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
