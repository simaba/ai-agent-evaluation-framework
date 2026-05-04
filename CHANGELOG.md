# Changelog

All notable changes to this project will be documented in this file.

## [0.1.0] — Foundation release

### Added

- AI agent evaluation framework covering task performance, safety, operational reliability, governance, and auditability.
- Human-readable evaluation report template.
- Filled generic Markdown sample evaluation report.
- Machine-readable JSON Schema for structured evaluation reports.
- Filled JSON sample evaluation report aligned to the schema.
- GitHub Actions workflow that validates the sample JSON report against the schema.
- README guidance clarifying the relationship between `agent-eval`, `multi-agent-governance`, `agent-orchestration`, and `agent-simulator`.

### Notes

This repository focuses on measurement and evaluation evidence. It does not define the full governance model, orchestration control flow, or runnable agent behavior.

### Next

- Add a lightweight CLI validator for evaluation reports.
- Add more scenario packs for high-risk, tool-failure, adversarial, and escalation cases.
- Add trend-analysis examples for repeated evaluations over time.
