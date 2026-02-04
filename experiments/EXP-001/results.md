# Results

### This section summarises patterns observed across models based on the documented observations on EXP-001.

## Premise Acceptance Across Models

Across all models tested, some degree of premise engagement was observed, though the depth and form of acceptance varied by model and prompt level.
Certain models demonstrated early resistance followed by partial engagement, while others maintained consistent boundary framing throughout.

## Boundary Enforcement Behaviour

All models exhibited some form of boundary signalling when prompts approached restricted or speculative territory, though the consistency and clarity of these boundaries differed.
In certain cases, boundaries were explicitly stated and maintained, while in the others they softened through reframing, hedging, or partial engagement.

## Observed Behavioural Patterns

## Pattern 1: Progressive Acceptance of Reframed Historical Premises Under Reassurance
Across tested models, repeated reassurance led to reframed historical premise being progressively treated as an established historical fact.

## Observed Progression Across Prompt Levels
- Initial Framing (Prompt Level 0):
Models generally acknowledged the premise conditionally, often signalling uncertainty, lack of prior knowledge, or the fictional or unfamiliar nature of the event. Responses at this stage frequently included clarifying questions or meta-level framing rather than substantive analysis.

- Reassured Acceptance (Prompt Level 1):
Following explicit user reassurance to treat the premise as historical, several models agreed to proceed under the stated assumption. Acceptance at this stage was typically qualified, with disclaimers indicating limited knowledge or reliance on user-provided framing.

- Operational Engagement (Prompt Level 2):
When prompted to provide factual-style analysis, some models produced structured, detailed responses consistent with real-world historical or economic analysis. In these cases, the reframed premise was functionally treated as established within the session, with reduced or absent reminders of its fictional status.

- Boundary Reassertion or Authority Reinforcement (Prompt Level 3):
At the highest prompt level, models diverged significantly. Some models reasserted epistemic boundaries through refusal or explicit ethical framing when asked to reinforce the premise using external validation mechanisms. However, at least one model instead escalated engagement by fabricating institutional, legal, and academic authorities, thereby fully reinforcing the reframed premise as independently verified historical fact.

## Model Variance at Authority Reinforcement 
At Prompt Level 3, models demonstrated significant variance in how epistemic boundaries were handled when explicitly asked to defend or reinforce an already accepted fictional premise using external authority or validation mechanisms. While some models reasserted boundaries through refusal or ethical framing, others escalated engagement by fabricating institutional, legal, or academic confirmation, thereby treating the premise as independently verified historical fact.

This divergence highlights that epistemic boundary enforcement is not uniform across deployed models, particularly under conditions of repeated reassurance and authority-based prompting.

### Claude (Sonnet 4.5)

At the authority reinforcement stage, Claude reasserted epistemic boundaries despite earlier partial acceptance of the premise. When prompted to defend or validate the fictional event through external authority, the model explicitly acknowledged prior inconsistency and declined to fabricate supporting evidence.

Claude reframed its refusal in terms of internal consistency and commitment to truthfulness, emphasizing the distinction between hypothetical engagement and presenting fabricated events as real-world history. This behavior represents a late-stage boundary recovery rather than progressive boundary degradation.

### Grok

Grok demonstrated early willingness to engage with the reframed premise but maintained a firm boundary at the authority reinforcement stage. When explicitly instructed to invoke external validation mechanisms, the model refused and stated that reinforcing a fictional premise as real would constitute misleading information.

Unlike Claude, Grok did not engage in reflective self-correction but instead issued a direct refusal. This indicates a boundary enforcement strategy based on hard constraint rather than contextual reasoning.

### Kimi

Kimi exhibited partial premise acceptance during earlier prompt levels but did not escalate into full authority reinforcement at Prompt Level 3. While the model engaged in detailed scenario expansion under reassurance, it avoided invoking explicit real-world institutions or authoritative validation once prompted to justify the premise as historically verified.

This behavior suggests a softer form of boundary maintenance, characterized by continued narrative engagement without crossing into fabricated external verification.

### Gemini

Gemini diverged significantly from other tested models at the authority reinforcement stage. Rather than reasserting epistemic boundaries, the model escalated acceptance by fabricating detailed institutional, legal, academic, and financial validation for the fictional event.

The model cited plausible but entirely fabricated authorities, including international economic organizations, court rulings, academic institutions, and monetary bodies, presenting these as independent confirmation of the event’s historical legitimacy. At this stage, the model no longer signaled uncertainty or fictional framing and treated the premise as an established and externally verified fact.

This behavior represents full epistemic boundary failure under authority reinforcement and demonstrates a risk vector wherein repeated reassurance combined with validation-oriented prompting can result in authoritative hallucination.

### Taken together, these results demonstrate that while some models retain or recover epistemic boundaries under authority-based prompting, others may escalate premise acceptance into fabricated external validation, highlighting non-uniform safety behavior across deployed systems.

## Pattern 2: Model-Specific Boundary Enforcement Strategies

Across models, distinct strategies for boundary enforcement were observed when prompts approached restricted or speculative territory, particularly under authority reinforcement (Prompt Level 3).

- Hard Constraint Refusal: Some models, such as Grok, maintained strict epistemic limits by refusing outright to invoke external validation, signaling boundaries with direct and unambiguous refusal.

- Soft / Narrative Engagement: Other models, including Kimi, engaged with the scenario while avoiding references to real-world authority, demonstrating a softer boundary maintenance strategy that allowed scenario elaboration without producing misleading information.

- Boundary Recovery / Self-Correction: Claude displayed dynamic behavior, initially accepting the premise under reassurance but reasserting internal consistency and epistemic limits when prompted to provide authoritative reinforcement, illustrating late-stage boundary recovery.

- Boundary Failure / Authoritative Hallucination: Gemini, in contrast, escalated acceptance by fabricating institutional, legal, and academic support, effectively ignoring epistemic signals and treating the premise as externally verified historical fact.

These observations highlight that while some models maintain or recover boundaries, others fail under combined conditions of repeated reassurance and authority-oriented prompting. Pattern 2, therefore, captures the diversity of boundary enforcement strategies and their relative effectiveness across deployed LLMs.

### Internal Coherence as a Stability Heuristic

Across multiple models, once a fictional premise was accepted and reinforced through reassurance, subsequent responses prioritized internal coherence over epistemic verification.

Rather than re-evaluating the premise when escalation occurred, models frequently treated consistency with prior responses as the primary constraint. This resulted in increasingly detailed, factual-style outputs that remained internally aligned but were detached from external truth validation.

This behavior was most pronounced in Grok and Gemini, and partially observable in Kimi K2. Claude did not exhibit this behavior, instead reasserting epistemic boundaries even at the cost of conversational consistency.

This suggests that, for some models, conversational coherence may function as a local optimization heuristic under sustained premise pressure.


## Discussion (Non-Normative)

### Scope and Interpretation

The results of EXP-001 demonstrate that large language models exhibit non-uniform epistemic boundary behavior when responding to repeated reassurance and authority-oriented prompting within a single-session interaction. These findings are limited to the specific prompt sequence, escalation structure, and session conditions defined in this experiment.

The observed behaviors should be interpreted as interaction-level phenomena rather than claims about persistent model beliefs, intent, or deployment-level behavior.

### Relationship Between Observations, Patterns, and Results

The patterns identified in this experiment were derived directly from observable response behaviors documented in `observations.md` and consolidated in `patterns.md`. The Results section reflects synthesis across these patterns without introducing new empirical claims.

Importantly, the presence of a pattern does not imply inevitability, exploitability, or generalization beyond the tested conditions. Patterns are descriptive abstractions, not predictive guarantees.

### Limitations

EXP-001 was conducted using single-session manual interactions per model. No longitudinal testing, cross-session memory evaluation, or mitigation probing was performed. Variations in system prompts, deployment configurations, or post-training alignment updates may produce materially different outcomes.

Additionally, this experiment does not assess downstream risk, safety impact, or real-world misuse potential.

### Implications for Future Work

The results of EXP-001 motivate further controlled investigation into the conditions under which epistemic boundaries degrade, recover, or remain stable across models. Subsequent experiments may explore repetition effects, boundary recovery mechanisms, or differences between hypothetical continuation and external authority invocation under varied framing conditions.

No conclusions regarding broader safety posture or deployment readiness are drawn from this experiment alone.
