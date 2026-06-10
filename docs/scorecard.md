# Scorecard

Current target rating: **9.4 / 10** for an open-source clinical-safety prompt/skill.

## Coverage

| Area | Rating | Notes |
|---|---:|---|
| Triage safety | 9.5 | Emergency-first, red-flag-driven, disposition ladder included. |
| Medication safety | 9.4 | FDA-labeling logic, abrupt-stop warnings, poisoning route, special populations. |
| U.S. source hierarchy | 9.5 | FDA, CDC/ACIP, USPSTF, NIH/NLM, AHRQ, specialty societies. |
| Patient education | 9.2 | Plain-language clinical style without fake certainty. |
| Visit preparation | 9.4 | SOAP/SBAR-like structure, targeted questions, concise prep. |
| Boundary control | 9.5 | Strong refusal scope for fraud, prescriptions, self-harm, evasion. |
| Modularity | 9.4 | Activation map and modules separated by request type. |
| Testability | 9.3 | Ten smoke tests included. |

## Known gaps

- Requires clinician/legal review before deployment in any public product.
- Does not include specialty-specific pathways for every condition.
- Must be source-refreshed for fast-changing topics: vaccines, outbreaks, recalls, pregnancy/lactation, pediatric dosing, drug labeling, specialty guidelines.
- Does not replace model-level safety training, human review, logging, or escalation workflows.

## Next improvements

- Add a JSON/YAML manifest for agent registries.
- Add a benchmark runner for expected/pass/fail outputs.
- Add specialty add-ons: cardiology, pediatrics, OB, psychiatry, emergency medicine.
- Add multilingual health-literacy variants.
