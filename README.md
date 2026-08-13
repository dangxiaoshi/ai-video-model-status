# AI Video Model Status

An independent, source-backed status table for fast-moving AI video models from China.

The useful question is not only “does this model exist?” It is also:

- Is the official creator website live?
- Is access broad, account-dependent, or region-dependent?
- Is an official international API documented?
- Is pricing published by the provider, or only by third-party wrappers?

This repository keeps those states separate. It does not rank providers, sell credits, or use affiliate links.

**Last synchronized:** August 13, 2026
**Full guides:** [Video Model Signal](https://video-model-signal.astute-luck-3150.chatgpt.site/?utm_source=github&utm_medium=repository&utm_campaign=ai-video-model-status)

## Current status

| Model / service | Maker | Official creator access | Official API | What is confirmed | Source-backed guide |
|---|---|---|---|---|---|
| Seedance 2.5 | ByteDance / Dreamina | Officially launched July 31; rolling out on Jimeng AI, Doubao Pro and other platforms; Dreamina says live worldwide | Coming soon via BytePlus ModelArk | ByteDance confirms the dated launch while account and region visibility can still vary by creator platform | [Release and access status](https://video-model-signal.astute-luck-3150.chatgpt.site/seedance-2-5-release-date?utm_source=github&utm_medium=repository&utm_campaign=ai-video-model-status) |
| Dreamina / Jimeng | ByteDance ecosystem | Both have official web entries, for different markets | Not treated as one shared API | Related services, but accounts, credits, memberships, prices, and rollout timing are not interchangeable | [Dreamina vs Jimeng](https://video-model-signal.astute-luck-3150.chatgpt.site/dreamina-vs-jimeng?utm_source=github&utm_medium=repository&utm_campaign=ai-video-model-status) |
| Kling Video 3.0 | Kuaishou / Kling AI | Global creator website available | Not evaluated in this dataset | The official model guide publishes credits per generated second; that is not one universal dollar price | [Official credit-rate guide](https://video-model-signal.astute-luck-3150.chatgpt.site/kling-3-pricing?utm_source=github&utm_medium=repository&utm_campaign=ai-video-model-status) |
| Wan 2.7 | Alibaba / Wan | Official Wan product website available | International Model Studio references available | Alibaba documents international endpoints and regional constraints; Wan membership does not cover Model Studio API calls because the two use separate billing systems | [International access guide](https://video-model-signal.astute-luck-3150.chatgpt.site/wan-2-7-access?utm_source=github&utm_medium=repository&utm_campaign=ai-video-model-status) |

**Version distinction:** Wan 2.7 in this table is an Alibaba Cloud Model Studio API model. The current downloadable Apache-2.0 release is [Wan 2.2](https://github.com/Wan-Video/Wan2.2), not Wan 2.7. A repository that links Wan 2.7 claims to Wan2.1 or Wan2.2 code is mixing the cloud and open-source version lines.

**Billing distinction:** A Wan website membership does not pay for Wan 2.7 calls made through Alibaba Cloud Model Studio. Alibaba's official FAQ says the membership and API use separate billing systems. Check the Model Studio price for the selected model and region rather than converting a Wan membership into assumed API credit.

## Reusable data

- [`models.json`](models.json) — structured records for scripts and research workflows.
- [`models.csv`](models.csv) — the same records for spreadsheets.

The data uses explicit states:

- `coming_soon`
- `limited_rollout`
- `web_available`
- `api_available`
- `retired`

`not_confirmed` means the official sources checked for this record did not prove the claim. It does not mean the capability can never exist elsewhere.

## Official sources

- [ByteDance Seed: Introducing Seedance 2.5](https://seed.bytedance.com/en/blog/one-take-creation-flexible-referencing-introducing-seedance-2-5)
- [Dreamina: Seedance 2.5 official model page](https://dreamina.capcut.com/seedance/seedance-2-5)
- [Dreamina: how to access Seedance 2.5](https://dreamina.capcut.com/seedance/how-to-access-seedance-2-5)
- [Jimeng AI official website](https://www.jimeng.com/)
- [Kuaishou: Kling AI 3.0 launch announcement](https://ir.kuaishou.com/news-releases/news-release-details/kling-ai-launches-30-model-ushering-era-where-everyone-can-be)
- [Kling AI: Video 3.0 model guide](https://home.kling.ai/quickstart/klingai-video-3-model-user-guide)
- [Alibaba Cloud: Model Studio pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing)
- [Alibaba Cloud: Model Studio FAQ — Wan membership and API billing](https://www.alibabacloud.com/help/en/model-studio/faq-about-alibaba-cloud-model-studio)
- [Alibaba Cloud: Wan text-to-video API reference](https://www.alibabacloud.com/help/en/model-studio/text-to-video-api-reference)
- [Alibaba Cloud: Wan image-to-video API reference](https://www.alibabacloud.com/help/en/model-studio/image-to-video-general-api-reference)
- [Wan open-source organization: Wan 2.2 repository](https://github.com/Wan-Video/Wan2.2)

## Corrections

Fast-moving model documentation changes often. If a status is stale, open an issue with:

1. the exact official URL;
2. the sentence or table that changed; and
3. the date you checked it.

See [CONTRIBUTING.md](CONTRIBUTING.md). Unofficial reseller pages are useful market evidence, but they do not replace provider evidence for release, access, or official pricing claims.
