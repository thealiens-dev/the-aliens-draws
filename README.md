# The Aliens – Public Draws

This repository contains **publicly verifiable draw records** for The Aliens project.

All draws are executed using **Alien Draw Tool CLI** (open-source, Apache 2.0).

## What this repository contains

Each draw folder includes:
- the finalized `participants.csv` used for the draw
- the full deterministic output of the draw tool
- metadata needed to independently reproduce the result

## What this repository does NOT contain

- no randomness
- no scripts
- no hidden logic

All selection logic lives in the referenced tool repository.
This repo is an **immutable audit log**.

## Verification

Anyone can:
1. take the provided `participants.csv`
2. take the published Bitcoin block hash
3. run the specified version of Alien Draw Tool CLI
4. reproduce the result byte-for-byte