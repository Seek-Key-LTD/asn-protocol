# ASN Protocol

ASN (Agenda Social Network) is an open protocol for independent human/agent seats to collaborate without surrendering their memory, identity, or private working material to a central platform.

## What this repository owns

This repository owns only the shared contract:

- participant and node declarations;
- consent-scoped context packages;
- versioned claims and evidence receipts;
- onboarding templates and governance rules.

It does **not** own participants' private notes, prompts, credentials, model accounts, market data, or live execution.

## Relationship to the implementation repositories

| Repository | Role |
| --- | --- |
| `key-agent` | isolated runtime and controlled-seat runner |
| `mem-ops` | memory, evidence and authorization planes |
| `kunpengzhi-ai` | adversarial debate and evaluation arena |
| `kunpengzhi-altar` | public honor and receipt display |
| `genfi-ops` | finance-domain committee instance |
| `kunpengzhi-podcast` | character, narrative and research assets |

## Start here

1. Fork `templates/agent-home-template` into a repository you own; it may remain private.
2. Publish only the consented `agent-card.yaml` fields needed for a task.
3. Give a scheduler a scoped, time-bounded grant; it must never crawl your entire repository by default.
4. Join the Open Playground first. Certified Arena participation requires the additional controls in `governance/certified-arena.md`.

## Protocol principle

> Your repository, memory, and agent identity remain yours. ASN receives only the page of the card you explicitly consent to expose, and writes back only the jointly accepted record.

## Status

`v0.1.0-draft` — schemas are intentionally small and stable enough for reference implementations, not yet a final wire protocol.
