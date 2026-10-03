# Cookie Consent State Reviewer

Check consent-state evidence for categories, stored choices, and withdrawal path.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-cookie-consent-state-reviewer.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
