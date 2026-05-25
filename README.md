# Krea

Krea is a real-time AI creative suite that lets designers, filmmakers, brand teams, and everyday creators generate, edit, enhance, and animate images and videos with professional controls from a single workspace. The Krea API at `https://api.krea.ai` exposes 50+ third-party and proprietary image and video models — Flux, Imagen, Veo, Nano Banana, gpt-image, Runway, Kling, Seedream, Seedance, Hailuo, Wan, Ray, Grok Imagine, Ideogram, Qwen, Z Image, Topaz, and more — through one Bearer-token REST surface with a unified async job lifecycle, compute-unit billing, asset management, LoRA style training, Nodes workflow execution, and webhook delivery. Krea also publishes open-source models including FLUX.1 Krea [dev] (in collaboration with Black Forest Labs) and Krea Realtime 14B, a Self-Forcing distillation of Wan 2.1 that produces 11 fps text-to-video on an NVIDIA B200.

## APIs Profiled

| API | Description |
| --- | --- |
| [Krea API](https://docs.krea.ai/api-reference/introduction) | One REST API and one API token for 50+ image and video generation models under `https://api.krea.ai`. |
| [Krea Image Generation API](https://docs.krea.ai/api-reference/image/flux) | 22 image-generation endpoints under `/generate/image/{provider}/{model}` covering Flux, Imagen, Nano Banana, gpt-image, Seedream/SeedEdit, Ideogram, Runway, Luma, Qwen, and Z Image. |
| [Krea Video Generation API](https://docs.krea.ai/api-reference/video/veo-3) | 31 video-generation endpoints under `/generate/video/{provider}/{model}` covering Veo, Runway Gen-3/4/4.5/Aleph, Kling, Hailuo, Wan, Seedance, Ray 2, LTX-2.3 22B, and Grok Imagine. |
| [Krea Image Enhance API](https://docs.krea.ai/api-reference/image-enhance/topaz) | Topaz-powered standard, generative, and bloom upscalers under `/generate/enhance/topaz`. |
| [Krea Styles API (LoRA)](https://docs.krea.ai/api-reference/styles/train-a-custom-style-lora) | Train, search, share, and manage custom LoRA styles via `/styles` and `/styles/{id}` endpoints. |
| [Krea Assets API](https://docs.krea.ai/api-reference/assets/upload-an-asset) | Upload, list, retrieve, and delete inputs used by generation, edit, and enhance endpoints. |
| [Krea Jobs API](https://docs.krea.ai/api-reference/general/list-jobs) | List, inspect, and cancel asynchronous generation jobs (`/jobs`, `/jobs/{id}`). |
| [Krea Node Apps API](https://docs.krea.ai/api-reference/node-apps/execute-a-node-app) | Execute Krea Nodes visual workflows programmatically with `/node-apps/{id}/execute`. |

## Artifacts

- [OpenAPI 3.1.0 — Krea API](openapi/krea-api-openapi.json)

## Plans

| Plan | Price | Compute Units |
| --- | --- | --- |
| Free | $0 / month | 100 / day |
| Basic | $9 / month | 5,000 / month |
| Pro | $35 / month | 20,000 / month |
| Max | $70 / month | 60,000 / month |
| Business | $200 / month | 80,000 / month (up to 50 seats) |
| Enterprise | Custom | Custom |

## Properties

- Portal: <https://www.krea.ai>
- Documentation: <https://docs.krea.ai/>
- API Reference: <https://docs.krea.ai/api-reference/introduction>
- LLMs index: <https://docs.krea.ai/llms.txt>
- Upstream OpenAPI: <https://docs.krea.ai/api-reference/openapi.json>
- Postman: <https://docs.krea.ai/api-reference/postman>
- Pricing: <https://www.krea.ai/pricing>
- API tokens: <https://www.krea.ai/settings/api-tokens>
- Rate limits: <https://docs.krea.ai/developers/rate-limits>
- Webhooks: <https://docs.krea.ai/developers/webhooks>
- Job lifecycle: <https://docs.krea.ai/developers/job-lifecycle>
- Deprecations: <https://docs.krea.ai/developers/deprecations>
- Interactive playground: <https://docs.krea.ai/developers/interactiveexample>
- Discord: <https://krea.ai/discord>
- GitHub: <https://github.com/krea-ai>

## Tags

- AI
- Artificial Intelligence
- Image Generation
- Video Generation
- Generative AI
- Real Time
- Multimodal
- Creative Tools
- 3D
- Upscaling

## Maintainer

- [Kin Lane](https://apievangelist.com) — info@apievangelist.com
