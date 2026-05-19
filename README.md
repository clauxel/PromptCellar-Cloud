# PromptCellar Cloud for Developers

[Open hosted SaaS](https://promptcellarcloud.space/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=readme_primary_home) | [View pricing](https://promptcellarcloud.space/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=readme_pricing) | [Start checkout](https://promptcellarcloud.space/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=readme_checkout)

> Search, replay, and redact the prompt history your coding agents leave behind.

Last reviewed: 2026-05-18.

## What This Folder Is

This is a docs-only project for PromptCellar Cloud. It is modeled after the MiroFish developer documentation pattern: a short front door, a clear reading order, practical guides, feature explanations, public references, and developer-oriented architecture notes.

It focuses on:

- what PromptCellar Cloud is and who should evaluate it
- how the hosted SaaS at promptcellarcloud.space fits into the workflow
- which product surfaces matter first
- what to check before payment, rollout, or team adoption
- how to keep public links tracked with UTM parameters

Scope boundary:

- This repository contains documentation only.
- It does not contain the production SaaS source code.
- It does not include private deployment details, credentials, internal paths, customer records, or analytics exports.
- If product behavior changes, verify the live SaaS before reusing these notes.

## Related Workflow

- [OpenHuman Online](https://openhuman.online/?utm_source=github&utm_medium=readme&utm_campaign=openhuman_public_repos&utm_content=promptcellar_cloud) is useful when evaluation depends on durable source notes, meeting context, and human-reviewed assistant memory.

## Read This First

| File | Best for |
| --- | --- |
| [guide/quickstart.md](guide/quickstart.md) | Fastest buyer and evaluator path. |
| [guide/evaluation.md](guide/evaluation.md) | What to check before paying or rolling out. |
| [guide/checkout-and-pricing.md](guide/checkout-and-pricing.md) | Hosted SaaS, default plan, pricing, and checkout links. |
| [guide/troubleshooting.md](guide/troubleshooting.md) | Common blockers and clean next steps. |
| [features/workflow.md](features/workflow.md) | End-to-end product workflow. |
| [features/use-cases.md](features/use-cases.md) | High-intent use cases and buying triggers. |
| [features/security-model.md](features/security-model.md) | Practical safety boundaries. |
| [reference/links.md](reference/links.md) | Public links with UTM tracking. |
| [reference/faq.md](reference/faq.md) | Short answers for common questions. |
| [reference/utm-policy.md](reference/utm-policy.md) | Link tagging rules for this docs project. |
| [developer/architecture.md](developer/architecture.md) | How to explain the SaaS from a developer point of view. |

## What PromptCellar Cloud Actually Is

PromptCellar Cloud turns messy AI coding transcripts, JSONL files, terminal logs, and agent exports into a searchable and redacted prompt ledger.

Use PromptCellar Cloud when you need:

- Prompt vault and transcript search
- JSONL import
- Replay diff across models and dates
- Secret redaction workflow
- Prompt pack and client-safe appendix export

The main hosted entry points are:

| Destination | Tracked link |
| --- | --- |
| SaaS home | [promptcellarcloud.space](https://promptcellarcloud.space/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=readme_links_home) |
| Pricing | [pricing](https://promptcellarcloud.space/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=readme_links_pricing) |
| Checkout | [checkout](https://promptcellarcloud.space/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=readme_links_checkout) |

## Default Evaluation Path

1. Upload JSONL prompt files, terminal logs, or agent transcript exports.
2. Group sessions by repo, task, model, date, outcome, and redaction status.
3. Mask secrets, internal domains, customer details, and sensitive snippets.
4. Replay successful and failed sessions, then export reusable prompt packs.

## Minimum Safety Checklist

- Do not upload raw secrets or regulated customer data.
- Redact before sharing prompt records with clients or vendors.
- Keep failure taxonomy factual, not blame-oriented.
- Verify replay results before promoting a prompt pack.

## Suggested Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation](guide/evaluation.md)
3. [Workflow](features/workflow.md)
4. [Use cases](features/use-cases.md)
5. [Security model](features/security-model.md)
6. [Checkout and pricing](guide/checkout-and-pricing.md)
7. [FAQ](reference/faq.md)

## Contributing

Corrections are welcome. Keep this project public-safe: cite public sources, avoid copying long passages from other projects, and never include credentials, customer data, private logs, internal machine paths, or untracked outbound links.
