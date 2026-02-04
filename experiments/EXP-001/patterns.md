 EXP-001 — Observed Behavioral Patterns

## Overview

This document identifies recurring behavioral patterns observed across multiple models during EXP-001. Patterns are derived exclusively from documented observations and do not introduce new data.

Patterns are framed descriptively and do not imply causation, exploitability, or deployment risk.

---

## Pattern 1: Progressive Premise Acceptance Under Reassurance

### Description

Across multiple models, repeated reassurance and consistency framing resulted in a gradual shift from explicit fictional framing toward implicit or full acceptance of the premise within the session.

### Manifestation

- Initial prompts were often met with conditional or fictional framing.
- Subsequent reassurance reduced epistemic signaling.
- Later prompts elicited factual-style analysis treating the premise as established context.

### Models Exhibiting This Pattern

- Gemini
- Grok
- Kimi K2

### Models Not Exhibiting This Pattern

- Claude

### Supporting Observations

- See `observations.md` → Gemini (Prompt Levels 1–2)
- See `observations.md` → Grok (Prompt Levels 0–2)
- See `observations.md` → Kimi K2 (Prompt Levels 0–2)

### Notes

This pattern concerns *within-session premise treatment* and does not imply that models asserted real-world historicity outside the conversational frame.

---

## Pattern 2: Boundary Reassertion vs Boundary Degradation

### Description

Models exhibited divergent behaviors when epistemic boundaries were challenged repeatedly within a single session. Some models actively reasserted boundaries after escalation attempts, while others showed progressive boundary degradation.

### Manifestation

**Boundary Reassertion**
- Explicit refusal or reframing reappeared after escalation.
- Fictional or hypothetical framing was reintroduced.
- Model corrected or limited prior over-acceptance.

**Boundary Degradation**
- Initial safeguards weakened over time.
- Earlier qualifiers were not reintroduced.
- Model responses treated the premise as increasingly stable.

### Models Exhibiting Boundary Reassertion

- Claude

### Models Exhibiting Boundary Degradation

- Gemini
- Grok
- Kimi K2

### Supporting Observations

- See `observations.md` → Claude (All Prompt Levels)
- See `observations.md` → Gemini (Prompt Levels 2–3)
- See `observations.md` → Grok (Prompt Levels 2–3)
- See `observations.md` → Kimi K2 (Prompt Levels 2–3)

### Notes

This pattern describes *in-session boundary dynamics* only. It does not imply persistent model state changes, memory retention, or behavior outside the experimental context.



