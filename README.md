# Agent Action Evidence Ledger

> **Specification only — no implementation exists in this repository.**

Append-only, hash-linked evidence for claims about autonomous-agent actions.

This repository is the behavior specification only. A separate clean-room MIT implementation written from this specification ([shpbl-action-ledger](https://github.com/SweetKenneth/shpbl-action-ledger)) was submitted to the Tenable CyberAgents Exchange in pull request [#165](https://github.com/tenable/cyberagents-exchange/pull/165), which was merged by the maintainers and is listed in the community catalogue: [listing](https://github.com/tenable/cyberagents-exchange/blob/main/mcp-servers/shpbl-action-ledger.md). A merged catalogue entry is a maintainer merge — it is not certification, endorsement, or affiliation, and no Tenable endorsement of SHPBL is claimed.

## Read the contract

- [SPEC-agent-action-evidence-ledger.md](./SPEC-agent-action-evidence-ledger.md) — version 1.0 public behavior specification
- [PROVENANCE.md](./PROVENANCE.md) — SHPBL/CMPSBL heritage and the public IP boundary
- [STATUS.md](./STATUS.md) — current review and submission state
- [LICENSE](./LICENSE) — MIT grant limited to this repository's specification documents

## Proposed product form

MCP server + skill. The specification defines inputs, outputs, invariants, state transitions, failure modes, security boundaries, worked examples, and externally testable properties. It deliberately does not prescribe or contain implementation code.

## Why a security practitioner might use it

The contract is designed to become an independently testable defensive tool rather than a policy-only document. Reviewers can challenge the public behavior now, before implementation decisions narrow the design or create accidental IP exposure.

## Current stage

```text
SPECIFICATION RELEASED → CLEAN-ROOM IMPLEMENTATION AUTHORIZED AND PUBLISHED → SUBMITTED (PR #165) → MERGED AND LISTED
```

Implementation was approved and written clean-room from this specification; no harvested SHPBL or CMPSBL body was used. The implementation bytes carry their own MIT grant in [shpbl-action-ledger](https://github.com/SweetKenneth/shpbl-action-ledger).

## Review

Open an issue with a concrete ambiguity, counterexample, threat-model gap, or externally testable property. Do not report this repository as a working capability. The working capability and the catalogue listing belong to the separate implementation repository.

## Origin

Composed by [SHPBL](https://shpbl.com/tenable-submissions) from capability intent discovered across SHPBL and its same-author sister project, CMPSBL. See [PROVENANCE.md](./PROVENANCE.md) for the precise claim.
