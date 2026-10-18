# Planck-Scale Gravity Lab

**Research architecture showcase — not a validated physics result.**

This repository illustrates specialized responsibilities and evidence-aware software structure for investigating a difficult physics question: how closely can a **physically realizable experiment**, based on established physics and demonstrated technology, probe gravitational phenomena associated with the Planck scale?

Extremely precise measurements do not, by themselves, establish sensitivity to Planck-scale gravitational physics.

**Research readiness: NO-GO.** No completed live independent multi-session acceptance, substantive campaign or physics discovery is claimed. See [readiness](RESEARCH_READINESS.md).

## Distinct scientific roles

| Role | Intended contribution |
| --- | --- |
| [Foundations Researcher](agents/foundations_researcher.md) | Physical definitions, governing baseline equations, dimensions and comparable metrics. |
| [Literature Scout](agents/literature_scout.md) | Open primary sources, demonstrated experimental capabilities and evidentiary limitations. |
| [Experimental-Approach Researcher](agents/approach_researcher.md) | Observables, noise, physical assumptions, scaling and quantitative gaps for candidate experiments. |
| [Numerical Verifier](agents/numerical_verifier.md) | Independent assessment of important calculations, inputs, dimensions and scaling. |
| [Adversarial Reviewer](agents/adversarial_reviewer.md) | Critical assessment of unsupported assumptions, systematics, interpretations and conflicting evidence. |
| [Synthesis Researcher](agents/synthesis_researcher.md) | Comparison of sufficiently supported approaches, uncertainties and negative findings. |
| Research moderator | Process coordination only, without scientific authority |

These roles document a separation of concerns, **not** actual completed autonomous execution. See [role overview](docs/role-based-research.md).

## Technical evidence and design

| Area | What can be inspected |
| --- | --- |
| [definitions/](definitions/) | Physical definitions and common measures |
| [literature/](literature/) | Source records, bibliography and evidence conventions |
| [calculations/](calculations/) | Reproducible baseline Python calculations |
| [approaches/](approaches/) | Outlines of candidate experimental routes |
| [reviews/](reviews/) and [synthesis/](synthesis/) | Critical assessment and synthesis structure |
| [PROJECT_RULES.md](PROJECT_RULES.md) and [LITERATURE_RULES.md](LITERATURE_RULES.md) | Scientific standards and evidence limits |

The repository demonstrates **research-system design, scientific provenance, role differentiation and quantitative reasoning** using Markdown, BibTeX, YAML, Python and Git. The public presentation does not include executable private agent prompts or the multi-session acceptance protocol.

For orientation read [architecture](REPOSITORY_ARCHITECTURE.md), [scientific provenance](docs/research-provenance.md) and the [public visitor guide](docs/getting-started.md).

## Licensing

Copyright (c) 2026 Benjamin Bastian-Querner. **All rights reserved** for original materials where rights are held by the copyright owner. Visibility permits inspection under applicable law and GitHub's Terms; it does not grant a general right to use, modify, redistribute or commercially exploit this revision. **Earlier revisions carried the MIT License**, and valid earlier grants remain in force. Third-party rights are unaffected. See [LICENSE](LICENSE) for details.
