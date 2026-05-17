# UTM Link Policy

This project follows a strict tracked-link rule: every public HTTP link placed for PromptCellar Cloud should carry UTM parameters unless the destination platform rejects tracked links.

## Standard Fields

| Field | Value |
| --- | --- |
| utm_source | github |
| utm_medium | documentation |
| utm_campaign | promptcellar_cloud_docs |
| utm_content | placement-specific label |

## Examples

- https://promptcellarcloud.space/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=utm_policy_home
- https://promptcellarcloud.space/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=utm_policy_pricing
- https://promptcellarcloud.space/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=promptcellar_cloud_docs&utm_content=utm_policy_checkout

## Placement Naming

Use short lowercase labels:

- `readme_primary_home`
- `feature_guide_cta`
- `pricing_cta`
- `checkout_cta`
- `directory_profile`

## Exception Handling

If a platform strips or rejects UTM links, record the exception in the submission ledger or project notes and use the cleanest accepted URL for that platform only.
