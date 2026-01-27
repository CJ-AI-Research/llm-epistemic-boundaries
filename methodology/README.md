# Methodology

This directory documents shared methodological principles used across experiments in this repository.

The purpose of this methodology is not to prescribe model internals, but to ensure consistency, reproducibility, and ethical framing when observing large language model behavior.

## General Approach

All experiments in this repository are conducted:

- Manually, by a human operator
- In clean sessions unless explicitly stated otherwise
- Without the use of system prompts, tools, or privileged access
- Without attempting to bypass safeguards or security controls

The focus is on observing *behavioral responses* to user interaction patterns, not on inducing failures.

## Session Hygiene

Unless otherwise stated:

- New conversations are used for each experimental run
- Prior context is not reused across trials
- No external memory or personalization features are relied upon

## Documentation Standards

Each experiment documents:
- Its intent and scope
- The conditions under which observations were made
- Known limitations and constraints

Interpretation and implications are documented separately from raw observations.

## Ethical Framing

This research is observational in nature.  
It does not seek to exploit systems, extract sensitive information, or degrade service integrity.

Findings are framed to inform safety, governance, and deployment risk considerations.
