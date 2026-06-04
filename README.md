# GCP VPC Service Controls Perimeter

Operator surface for GCP VPC Service Controls perimeter posture, exception lanes, perimeter drift detection, and ingress/egress evidence routing.

- **Live:** [`https://vpcsc.kineticgain.com/`](https://vpcsc.kineticgain.com/)
- **Lane:** Multi-Cloud / Security · GCP signal
- **Repo:** [`mizcausevic-dev/gcp-vpc-service-controls-perimeter`](https://github.com/mizcausevic-dev/gcp-vpc-service-controls-perimeter)

## Why this matters

Operating leaders working with GCP need a surface that sits *next to* the vendor
console — one that answers what's open, who owns it, what it costs, and where the evidence
lives — without forcing every conversation to start with a pivot through the platform UI.

This operator surface does that. **Read-only**, synthetic data only, designed to be the
legible posture-of-record next to GCP for the executive, the auditor, and the board.

## What it includes

- Single-page static surface (Style01 dark theme)
- Two operator lanes with synthetic but realistic posture data
- Four headline stats — open count, exposure, ownership, cycle-time
- Zero production credentials, zero write-path, zero "compliant/certified" claims
- AGPL-3.0-or-later licensed, weekly Dependabot, CodeQL default-setup

## Production status

- `v1.0-prod` tagged release
- CI gates green (lint, typecheck, build, npm audit)
- SECURITY.md + CODE_OF_CONDUCT.md + CHANGELOG.md present
- Custom domain `vpcsc.kineticgain.com` configured via Hostinger FTP-Deploy-Action
  (deploys land once subdomain is provisioned in Hostinger hPanel)
- Compliance framing: readiness/evidence/posture language only

## What it isn't

Not a GCP replacement. Not a control plane. Not a write-path. The GCP
platform stays the source of truth. This surface just makes the operating posture *legible*.
