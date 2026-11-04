[README.md](https://github.com/user-attachments/files/34398917/README.md)
# ModelWatch

**RAG quality monitoring and human-review workflow | Georgetown applied AI project**

## The problem

An AI assistant can produce a fluent answer even when retrieval fails, citations mismatch supporting evidence, or operational quality is deteriorating. An operations team needs measurable signals and a clear route from an observed issue to a human decision.

## What I designed and tested

- A monitoring approach for a support-oriented retrieval-augmented assistant using retrieval success, citation mismatch, CSAT, and p95 latency.
- Notebook-based evaluation logic and testing scenarios using synthetic or illustrative inputs.
- Human-review and escalation concepts that require evidence before a quality signal is converted into an incident or action.
- An interface concept that connects performance signals to reviewer ownership, incident history, and resolution steps.

## Explore the work

The source repository contains three development-stage Jupyter notebooks:

- `MSB_ModelWatch_Week5_FINAL.ipynb`
- `ModelWatch_Week5_MVP_v3_tests.ipynb`
- `ModelWatch_Week5_MVP_v4_dashboard.ipynb`

These notebook versions document the development of the project. Read them in GitHub's notebook viewer or open them in Jupyter or Google Colab to inspect the code and demonstrations.

## Evaluation questions

1. Did the retrieval step return relevant evidence?
2. Does the response's citation actually support its claim?
3. Do aggregate quality scores conceal severe individual cases?
4. When should a human investigate, hold, or roll back an AI change?

## Scope and limits

This is a graduate applied AI project and simulation using synthetic or illustrative data. It does not claim production integration, a deployed model-service API, or clinical validation. Metrics and scenarios demonstrate a monitoring design, not measured outcomes from a real customer system.

## Future work

- Consolidate notebooks into a single documented demonstration.
- Add a small, reproducible synthetic evaluation dataset and explicit expected results.
- Add screenshots showing healthy and degraded conditions.
- Expand automated checks for invalid inputs and missing source evidence.

**Designed by Maya Kalantari | M.S. Artificial Intelligence Management, Georgetown University**
