# Test of CI/CD GitHub with GitHub Workflows

A demonstration project to set up a CI/CD pipeline using GitHub Actions for running a simple Node.js script. This project is created for study purposes.

---

## CI/CD Status

[![Node.js CI/CD Pipeline](https://github.com/p4elkab35t/CICD_github_default_test/actions/workflows/ci.yml/badge.svg)](https://github.com/p4elkab35t/CICD_github_default_test/actions/workflows/ci.yml)

---

## Description of the Process

This project showcases a basic Continuous Integration/Continuous Deployment (CI/CD) pipeline using GitHub Actions. The pipeline performs the following tasks:

1. **Checks out the repository code.**
2. **Sets up a Node.js environment** with a specified version (currently Node.js v20).
3. **Installs dependencies** (if any are listed in the `package.json` file).
4. **Executes a Node.js script** (`index.js`) that logs a messages to the console according to timeouts.
5. **Outputs a completion message** to indicate successful execution.

---

## Requirements

### Prerequisites
To work with or modify this project, ensure you have the following:
- **Git**: For cloning the repository and pushing changes.
- **Node.js (v20 or later)**: To run the script locally.
- **npm**: Comes bundled with Node.js, used for managing dependencies.

### Workflow Requirements
The CI/CD workflow assumes:
- The repository is hosted on **GitHub**.
- The `ci.yml` workflow file is located at `.github/workflows/ci.yml`.

