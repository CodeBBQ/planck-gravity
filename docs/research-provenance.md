# Scientific methodology and provenance

This guide explains the scientific constraints and artifact structure for
readers evaluating the project. The normative sources remain
[PROJECT_RULES.md](../PROJECT_RULES.md),
[LITERATURE_RULES.md](../LITERATURE_RULES.md) and
[PROVENANCE_WORKFLOW.md](../PROVENANCE_WORKFLOW.md).

## The research question

> What is the closest physically realizable experiment, using established
> physics and current demonstrated technology, to probing gravitational
> physics associated with the Planck scale?

The research is **not** a claim to have detected quantum gravity or found a
working Planck-scale experiment. Its intended result may be a rigorously
quantified **negative** assessment of currently feasible approaches.

Two distinctions prevent misleading conclusions:

1. Measuring a displacement or parameter *numerically smaller than the Planck
   length* is not necessarily probing gravitational processes at that scale.
2. Using quantum precision/sensitivity is not, by itself, measuring quantum
   effects of gravity.

Each route must specify its observable, governing equations, comparison
metric, experiment demonstrated today, signal, noise/systematics, scaling,
and the **quantified orders-of-magnitude gap** to the relevant target.
Amplification claims (coherence, integration time, repetitions, resonance,
ensembles or baseline) require stated quantitative scaling and conditions.

## Source classification is separate from project verification

| Evidence code | Meaning | Role in a decisive final design |
| --- | --- | --- |
| **E1** | Directly demonstrated experimental result | Eligible **only when project-verified** |
| **E2** | Established physical theory or derivation | Eligible **only when project-verified** |
| **E3** | Proposed, not yet demonstrated technique or performance | Investigation; cannot underwrite a final design |
| **E4** | Speculative or model-dependent physics | Context only; cannot underwrite a final design |

Independently, a claim has a project status:
`unverified`, `verified`, `challenged`, `superseded` or `rejected`.
An E1 label alone is not verification; a published or arXiv paper is not proof
that a reported device capability is demonstrated. Decisive quantitative
claims require a **legally accessible full text**, precise source location,
units, conditions, verification history and downstream references.

## Scientific traceability

```text
  accessible primary source
    -> sourced claim
    -> reproducible calculation
    -> experimental approach or candidate
    -> independent check and critical review
    -> evidence-bounded synthesis
```

Scientific evidence must remain distinct from any process or coordination metadata. Disagreement, negative findings and unresolved uncertainty should remain traceable without relying on conversation history.

## Repository map

| Location | Contents / purpose |
| --- | --- |
| `definitions/` | Shared quantities and definitions |
| `literature/` | Open bibliography, reading queue, assessed `CLM-*` evidence |
| `calculations/` | Reproducible `CAL-*` calculations and checks |
| `approaches/` | Scoped experimental-route evaluations |
| `candidates/` | Developed surviving `CAN-*` proposals |
| `reviews/` | Adversarial reviews, `REV-*` disputes and verification concerns |
| `synthesis/` | Cross-approach comparison after relevant gates |
| `agents/` | Six scientific responsibility descriptions |
| `orchestration/` | Non-operational coordination architecture overview |
| `prompts/` | Link to published research-role descriptions |
| `papers/` | Local, Git-ignored full-text cache; not a Git history of PDFs |

Canonical branches distinguish exploratory work (`research/*`,
`literature/*`), independent review (`review/*`) and synthesis
(`synthesis/*`). `main` is the conservative accepted shared state.

## Limits and readiness

The architecture has been documented but **not** accepted as a live, independently validated research system. See [RESEARCH_READINESS.md](../RESEARCH_READINESS.md): **NO-GO**. No substantive Planck-scale research outcome is claimed.
