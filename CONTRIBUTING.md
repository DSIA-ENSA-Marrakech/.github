# Contributing to DSIA

## Getting started

- Club members: coordinate with the project lead and Technical Advisory Board before starting a substantial change. External contributors: open an issue to discuss scope first.
- Read the project README, data licensing terms and setup instructions.
- Use a dedicated branch (`feature/name`, `fix/name`, `docs/name`). Never commit credentials or confidential data.
- Keep changes focused, document assumptions, and include tests or reproducible validation steps. For ML changes, record the dataset version, split, baseline and evaluation metrics; check for leakage.
- Open a pull request linked to an issue where applicable. Explain what changed and provide evidence of validation.
- Request a review, address feedback and merge only after approval according to the repository rules.

## Commit examples

`feat: add data validation` · `fix: prevent train-test leakage` · `docs: explain setup`

## Project publication

Confirm that data, code, images and model weights can be shared legally. Provide setup, evaluation results, limitations and a demo when possible. Use a project-specific license; public visibility alone is not an open-source license.
