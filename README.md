# GitHub Actions Matrix CI for Python

This project demonstrates how to build a CI pipeline using GitHub Actions with a matrix strategy.

The workflow runs automated tests across multiple Python versions and demonstrates how to structure reusable workflows for Python projects.

## Features

- GitHub Actions CI pipeline
- Matrix builds for multiple Python versions
- Reusable workflows
- Automated testing using pytest
- End-to-end (E2E) test execution

## Workflow Structure

### Reusable Build Workflow
`python-build.yml`

Responsible for:
- Checking out the repository
- Setting up Python
- Installing dependencies
- Running unit tests

### CI Workflow
`ci.yml`

- Triggered on push and pull requests
- Runs builds for multiple Python versions using a matrix strategy
- Executes E2E tests after successful builds

## Technologies

- GitHub Actions
- Python
- Pytest
- CI/CD Automation
