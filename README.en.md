# Elyne Lab Director (ELD)

**English · [Français](README.md)**

ELD coordinates laboratory qualification campaigns. It checks scope, initial state, evidence, and recovery gates; it starts approved stages, consolidates results, and produces a traceable report. Elyne Red selects and executes offensive actions within the authorized scenario; ELD directs the laboratory workflow. The catalogue lists ELD as **Laboratory**.

The engine can follow a **deterministic** workflow. A local model such as Bonsaï may help analyze results or propose stages without replacing scope checks or operator attestation.

| Key point | Observed status |
| --- | --- |
| Preflight, journal, and report | Functional in the laboratory kit. |
| Encrypted VMware snapshot | Created and restored by the operator, then attested and checked again. |
| Automatic continuation after restoration | Not established for trial H; ELD remained in `RESTORING` state. |

## Read more

- [Architecture and control gates](docs/architecture.en.md)
- [G/H demonstration kits and limits](docs/evidence.en.md)

ELD is distinct from EAS Defense and Elyne Red Unified. A launcher exit code of zero or an operator attestation alone does not establish a defense PASS. This documentation repository contains no campaign state, VM configuration, or raw receipts. [Contact Elyne Corp](mailto:admin@elynecorp.fr) · [Catalog](https://elynecorp.com/).
