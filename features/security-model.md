# Security Model

This documentation is public. It should explain safe evaluation without leaking implementation details.

## Public-Safe Claims

- PromptCellar Cloud is a hosted SaaS for AI coding prompt ledger.
- The documentation is independent from private production infrastructure.
- Readers should verify live behavior before making procurement or rollout decisions.
- Sensitive data should stay out of public examples and public GitHub issues.

## Practical Guardrails

- Do not upload raw secrets or regulated customer data.
- Redact before sharing prompt records with clients or vendors.
- Keep failure taxonomy factual, not blame-oriented.
- Verify replay results before promoting a prompt pack.

## Data Boundaries

Do not include:

- API keys, tokens, payment secrets, webhook secrets, or account identifiers.
- Private repositories, private customer names, private analytics, or local machine paths.
- Internal Cloudflare, database, registrar, or payment-provider configuration.
- Screenshots that reveal private sessions, accounts, or browser profiles.

## Safe Link

Use the public SaaS link with UTM:

- https://promptcellarcloud.space/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=security_safe_link
