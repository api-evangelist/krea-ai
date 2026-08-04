# Krea (krea-ai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Krea is a real-time AI creative suite that lets designers, filmmakers, brand teams, and everyday creators generate, edit, enhance, and animate images and videos with professional controls from a single workspace. The Krea API at https://api.krea.ai exposes 50+ third-party and proprietary image and video models — Flux, Imagen, Veo, Nano Banana, gpt-image, Runway, Kling, Seedream, Seedance, Hailuo, Wan, Ray, Grok Imagine, Ideogram, Qwen, Z Image, Topaz, and more — through one Bearer-token-authenticated REST surface with a unified async job lifecycle, compute-unit billing, asset management, LoRA style training, Nodes workflow execution, and webhook delivery. Krea also publishes open-source models including FLUX.1 Krea [dev] (in collaboration with Black Forest Labs) and Krea Realtime 14B, a Self-Forcing distillation of Wan 2.1 that produces 11 fps text-to-video on an NVIDIA B200.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/krea-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/krea-ai/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

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

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Krea API

One REST API and one API token to access 50+ image and video generation models from Black Forest Labs (Flux), Google (Imagen, Nano Banana, Veo), OpenAI (gpt-image), Runway, Kling, ByteDance (Seedream, Seedance, SeedEdit), MiniMax (Hailuo), Alibaba (Wan), Luma (Ray), xAI (Grok Imagine), Ideogram, Qwen, and Lightricks. Asynchronous job pattern with poll-or-webhook delivery, asset upload management, custom LoRA training, and node-app execution — all on https://api.krea.ai with Bearer-token authentication and a unified compute-unit billing model.

- **Human URL:** [https://docs.krea.ai/api-reference/introduction](https://docs.krea.ai/api-reference/introduction)
- **Base URL:** `https://api.krea.ai`

#### Tags

- AI
- Artificial Intelligence
- Image Generation
- Video Generation
- Generative AI
- Multimodal

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/introduction)
- [Documentation](https://docs.krea.ai/developers/introduction)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://docs.krea.ai/api-reference/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](https://docs.krea.ai/api-reference/postman.md) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Authentication](https://docs.krea.ai/developers/api-keys-and-billing)
- [Authentication](https://www.krea.ai/settings/api-tokens)
- [Rate Limits](https://docs.krea.ai/developers/rate-limits)
- [Webhooks](https://docs.krea.ai/developers/webhooks)
- [Documentation](https://docs.krea.ai/developers/job-lifecycle)
- [Deprecation](https://docs.krea.ai/developers/deprecations)
- [Sandbox](https://docs.krea.ai/developers/interactiveexample)

### Krea Image Generation API

Text-to-image and image-to-image generation across 22 model endpoints under /generate/image/{provider}/{model}, including Black Forest Labs Flux (Flux 1 dev, Flux 1 Kontext, Flux 1.1 Pro, Flux 1.1 Pro Ultra), Google Imagen 3/4/4-Fast/4-Ultra and Nano Banana / Nano Banana 2 / Nano Banana Pro, OpenAI gpt-image and gpt-image-2, ByteDance Seedream 4, Seedream 5 Lite, and SeedEdit, Ideogram 2 Turbo and Ideogram 3, Runway Gen-4 Image, Luma UNI-1, Qwen 2512, and Z Image.

- **Human URL:** [https://docs.krea.ai/api-reference/image/flux](https://docs.krea.ai/api-reference/image/flux)

#### Tags

- AI
- Image Generation
- Text To Image
- Image To Image

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/image/flux)
- [Code Examples](https://docs.krea.ai/developers/examples/text-to-image)
- [Code Examples](https://docs.krea.ai/developers/examples/image-to-image)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Krea Video Generation API

Text-to-video and image-to-video generation across 31 model endpoints under /generate/video/{provider}/{model}, including Google Veo 2 / Veo 3 / Veo 3 Fast / Veo 3.1 / Veo 3.1 Fast / Veo 3.1 Lite, Runway Gen-3, Gen-4 Video, Gen-4.5, and Aleph, Kling 1.0 through Kling 3.0 plus Kling o1, MiniMax Hailuo / Hailuo 02 / Hailuo 2.3 / Hailuo 2.3 Fast, Alibaba Wan 2.1 / 2.2 / 2.5, ByteDance Seedance Pro and Seedance Pro Fast, Luma Ray 2, Lightricks LTX-2.3 22B, and xAI Grok Imagine.

- **Human URL:** [https://docs.krea.ai/api-reference/video/veo-3](https://docs.krea.ai/api-reference/video/veo-3)

#### Tags

- AI
- Video Generation
- Text To Video
- Image To Video

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/video/veo-3)
- [Code Examples](https://docs.krea.ai/developers/examples/text-to-video)
- [Code Examples](https://docs.krea.ai/developers/examples/image-to-video)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Krea Image Enhance API

Image upscaling and enhancement powered by Topaz Labs models under /generate/enhance/topaz. Three endpoints — standard-enhance, generative-enhance, and bloom-enhance — deliver up to 22K resolution upscales for stills, with the same Bearer-auth and job-lifecycle pattern as the rest of the Krea API.

- **Human URL:** [https://docs.krea.ai/api-reference/image-enhance/topaz](https://docs.krea.ai/api-reference/image-enhance/topaz)

#### Tags

- AI
- Image Enhancement
- Upscaling

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/image-enhance/topaz)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Krea Styles API (LoRA)

Train, search, update, share, and unshare custom LoRA styles. Endpoints include POST /styles/train, GET /styles, GET /styles/{id}, PATCH /styles/{id}, GET /styles/{id}/share/link, and POST/DELETE /styles/{id}/share/workspace — letting teams bake their visual identity into Krea image models without managing GPU infrastructure.

- **Human URL:** [https://docs.krea.ai/api-reference/styles/train-a-custom-style-lora](https://docs.krea.ai/api-reference/styles/train-a-custom-style-lora)

#### Tags

- AI
- Custom Models
- LoRA
- Fine Tuning

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/styles/train-a-custom-style-lora)
- [Tutorial](https://docs.krea.ai/developers/tutorials/train-image-style)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Krea Assets API

Upload, list, retrieve, and delete assets (images, videos, audio, 3D models) used as inputs to generation, edit, enhance, and node-app endpoints. Endpoints are POST /assets, GET /assets, GET /assets/{id}, and DELETE /assets/{id}.

- **Human URL:** [https://docs.krea.ai/api-reference/assets/upload-an-asset](https://docs.krea.ai/api-reference/assets/upload-an-asset)

#### Tags

- AI
- Asset Management
- File Upload

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/assets/upload-an-asset)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Krea Jobs API

Manage the asynchronous lifecycle of every generation request. GET /jobs lists jobs, GET /jobs/{id} returns the current state (queued, processing, completed, failed, cancelled) with result.urls or result.error, and DELETE /jobs/{id} cancels a queued or running job. Only completed jobs consume compute units — failed and cancelled jobs are free.

- **Human URL:** [https://docs.krea.ai/api-reference/general/list-jobs](https://docs.krea.ai/api-reference/general/list-jobs)

#### Tags

- AI
- Jobs
- Async

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/general/list-jobs)
- [Documentation](https://docs.krea.ai/developers/job-lifecycle)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Krea Node Apps API

Execute Krea Nodes workflows — visual pipelines built in the Krea Nodes tool — directly from the API. GET /node-apps/{id} inspects a node app by version ID and POST /node-apps/{id}/execute runs it with user-supplied inputs, returning a job ID that follows the standard Krea async pattern.

- **Human URL:** [https://docs.krea.ai/api-reference/node-apps/execute-a-node-app](https://docs.krea.ai/api-reference/node-apps/execute-a-node-app)

#### Tags

- AI
- Workflows
- Automation

#### Properties

- [Documentation](https://docs.krea.ai/api-reference/node-apps/execute-a-node-app)
- [OpenAPI](openapi/krea-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krea-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krea-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.krea.ai)
- [Documentation](https://docs.krea.ai/)
- [Documentation](https://docs.krea.ai/api-reference/introduction)
- [Getting Started](https://docs.krea.ai/developers/introduction)
- [Documentation](https://docs.krea.ai/llms.txt)
- [Documentation](https://docs.krea.ai/CLAUDE.md)
- [Pricing](https://www.krea.ai/pricing)
- [Authentication](https://www.krea.ai/settings/api-tokens)
- [Rate Limits](https://docs.krea.ai/developers/rate-limits)
- [Webhooks](https://docs.krea.ai/developers/webhooks)
- [Documentation](https://docs.krea.ai/developers/job-lifecycle)
- [Deprecation](https://docs.krea.ai/developers/deprecations)
- [Sandbox](https://docs.krea.ai/developers/interactiveexample)
- [Documentation](https://docs.krea.ai/realtime)
- [Documentation](https://docs.krea.ai/image-generation)
- [Documentation](https://docs.krea.ai/user-guide/features/video)
- [Documentation](https://docs.krea.ai/3-d)
- [Documentation](https://docs.krea.ai/user-guide/features/edit)
- [Documentation](https://docs.krea.ai/user-guide/features/enhancer)
- [Documentation](https://docs.krea.ai/user-guide/features/training)
- [Documentation](https://docs.krea.ai/user-guide/features/nodes)
- [Documentation](https://docs.krea.ai/user-guide/features/teams)
- [Documentation](https://docs.krea.ai/user-guide/features/audio)
- [Documentation](https://docs.krea.ai/user-guide/help-and-support/compute-units)
- [Documentation](https://docs.krea.ai/user-guide/help-and-support/saml-sso-setup)
- [Documentation](https://docs.krea.ai/user-guide/help-and-support/domain-verification)
- [Documentation](https://docs.krea.ai/user-guide/help-and-support/model-access-controls)
- [Documentation](https://docs.krea.ai/user-guide/help-and-support/manage-subscriptions)
- [Documentation](https://docs.krea.ai/user-guide/help-and-support/refunds-and-billing)
- [GitHub Organization](https://github.com/krea-ai)
- [Open Source](https://github.com/krea-ai/realtime-video)
- [Open Source](https://github.com/krea-ai/flux-krea)
- [Open Source](https://github.com/krea-ai/open-prompts)
- [Open Source](https://github.com/krea-ai/prompt-search)
- [Open Source](https://github.com/krea-ai/skills)
- [Forum](https://krea.ai/discord)
- [X- Twitter](https://x.com/krea_ai)
- [LinkedIn](https://www.linkedin.com/company/krea-ai)
- [YouTube](https://www.youtube.com/@krea_ai)
- [Plans](https://www.krea.ai/pricing)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
