# AppSec Tools Demo (CI/CD Security)

This repository contains CI/CD security demos to complement my AppSec portfolio:
SAST + SCA + secrets scanning + SBOM generation.

Goal: make pipelines run end-to-end, publish the outputs, and document how to interpret results (signal vs noise).

## High-Level Plan
- SAST: CodeQL or Semgrep
- SCA: Dependabot + osv-scanner (or equivalents)
- Secrets: gitleaks
- SBOM: syft

Details: `docs/PLAN.md`

## Portfolio Link
Main portfolio: `https://github.com/efeberktnci/appsec-portfolio`
