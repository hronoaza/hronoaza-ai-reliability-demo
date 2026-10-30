# Demonstration Scope & Evidence Semantics

**Version:** public standalone demonstration v0.1 — 2026-10-30

## Design

The demo intentionally uses entirely fictional records with three fields: an operation, a **claim**, and a separate **illustrative observation**. It applies straightforward comparison logic to display statuses; it does not import production code or consume external systems.

| Status | Meaning in this demonstration |
| --- | --- |
| VERIFIED | The illustrative observation exists and matches the claim; no external truth is proven |
| CONTRADICTED | The illustrative observation exists and disagrees with the claim |
| UNSUPPORTED | No illustrative authoritative observation is supplied |

The third sample depicts a success claim with no observation, to show why uncertainty must be retained. The fourth depicts a fictional lost acknowledgement (caller status UNKNOWN) while an illustrative observation says SUCCEEDED; the simplistic demo marks this mismatch CONTRADICTED without establishing that a real failure occurred.

## Exclusions

There is no authenticated witness, independently established source of truth, database access, hardware-backed key management, operation authorization, external effect, exactly-once guarantee, crash simulation, incident capture, customer infrastructure, or production acceptance.

This is a **sales conversation aid**, not a research reproduction or legal/security attestation. It is not based on copied private fixtures or hidden proprietary algorithms.

## Run

Download the authorized repository snapshot to a local directory using a method allowed by GitHub and [LICENSE.md](LICENSE.md). Open `demo.html` in a recent browser. No server, installation, tracking script, external CDN, or network connection is required.

For the visible examples, outputs are derived in-browser, are deterministic and use fixed invented data. The printed counts and statuses are not metrics of customer operations.

## Security notes

The demo contains no credential inputs, no user data collection, and no links to protected repositories. Its files should not be used as an authoritative verifier in any operational environment.
