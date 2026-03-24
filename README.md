# ibmi-ci-templates
Starter CI/CD workflow templates for IBM i projects using GitHub Actions.

## What this repo is for
This repository collects reusable CI/CD examples that IBM i teams can copy into their own projects.
The first version focuses on a simple GitHub Actions workflow that runs on every push.

## GitHub Actions template: ibmi-basic-ci.yml

This workflow shows a simple CI setup:

- It runs on every push or pull request to the `main` branch.
- It checks out the repository code.
- It runs a placeholder step where IBM i build or test commands can be added later.

To use it in another project:

1. Copy `.github/workflows/ibmi-basic-ci.yml` into that project.
2. Replace the placeholder step with your own build or test script.
