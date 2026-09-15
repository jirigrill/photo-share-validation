# Family photo sharing hub

A mobile app (iOS + Android) for US parents to securely share photos of their kids with
family, especially grandparents, with print-prep, multi-attendee event albums, and an
optional self-hosted storage backend.

**This repo is a validation effort, not a product.** Its destination is a committed
`VERDICT.md`: build, build-narrower, not-yet, or don't-build.

## Success bar

$3–5k/month net profit after storage, egress, and store fees, on a paid-only family
subscription with no free tier. A verdict of **build** means the evidence supports clearing
this bar, not that the idea is interesting.

## Where things live

| What | Where |
|---|---|
| The map — canonical index, open tickets, decisions so far | [Map issue](../../issues?q=is%3Aissue+label%3Awayfinder%3Amap) |
| The frozen brief — the premise every section is judged against | [`docs/00-brief.md`](docs/00-brief.md) |
| Research findings, one file per resolved ticket | [`docs/research/`](docs/research/) |
| Global assumption registry | [`docs/ASSUMPTIONS.md`](docs/ASSUMPTIONS.md) |
| The two cases, written before the verdict | [`docs/case-for.md`](docs/case-for.md), [`docs/no-go-case.md`](docs/no-go-case.md) |
| The verdict | [`VERDICT.md`](VERDICT.md) |

The map issue is the only index — it lists decisions made and points at the tickets holding
their detail. This README is deliberately static.

## Method

Charted and worked with the `/idea-validation` skill
([jirigrill/custom-skills](https://github.com/jirigrill/custom-skills)), a `/wayfinder` preset.
Conventions descend from `personalised-radio-validation`.

Every non-obvious claim is tagged VERIFIED / SECONDARY / INFERRED / NO EVIDENCE FOUND /
UNVERIFIABLE. Inferred assumptions are registered with IDs and sensitivities so the verdict
can be attacked at its weakest joint rather than as a whole.
