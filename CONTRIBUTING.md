# Contributing

Contributions are welcome if they improve safety, clarity, source discipline, test coverage, or reliability.

## Good contributions

- Better emergency escalation language.
- Better medication-safety checks.
- Better special-population coverage.
- Cleaner module structure.
- New smoke tests with expected behavior.
- Source-refresh updates from FDA, CDC/ACIP, USPSTF, NIH/NLM, AHRQ, or major U.S. specialty societies.

## Avoid

- Adding fake certainty.
- Turning the skill into a doctor persona.
- Adding dosing instructions that require clinician oversight.
- Adding condition-specific pathways without source review.
- Bloated language that makes urgent instructions harder to see.

## Pull request checklist

- [ ] Does the change preserve triage-first behavior?
- [ ] Does it avoid diagnosis/prescribing claims?
- [ ] Does it improve clarity or safety?
- [ ] Are new high-risk claims source-backed?
- [ ] Do the smoke tests still pass?
- [ ] Did you avoid unnecessary private health information in examples?
