# AFT – Global Customizations

This repository contains Terraform that applies **across multiple or all
accounts** managed by AFT.

It is used for organisation-wide standards.

## When this runs

- Triggered by AFT global customization workflows
- Not tied to a single account request

## What belongs here

- Org-wide IAM roles
- Shared guardrails
- Cross-account resources
- Centralised standards

Do not place account-specific logic here.

## Repository structure

Terraform must live in a top-level `terraform/` directory:
