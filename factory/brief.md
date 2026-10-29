# Project brief

A minimal Rust CLI for M4 validation.

## Goal and users

Validate the acme brief-to-init flow for a Rust CLI maintainer.
Keep the starter help/version behavior and reject unsupported arguments.

## Inputs and outputs

Accept the starter help and version arguments. Print the matching output.
Reject unsupported arguments with a nonzero exit status.

## Acceptance checks

Local checks and generated CI pass.
Init is deterministic and preserves authored files.

## Constraints and non-goals

Keep the initial factory preset limited to CLI/Rust and L3 autonomy.
Keep the starter Cargo package identity and source unchanged.
Do not enable agent workflows, paid tests or remote provisioning.

## Permissions

The owner separately approved the complete config and diff, sample repository
creation, and publication of ordinary CI for this validation run.
This brief grants no additional permission.
Record required secret names only; never record their values.
