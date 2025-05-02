# GitHub Actions Workflow Templates

This repository serves as the **central hub for reusable GitHub Actions workflows across all my GitHub projects**.

It provides pre-configured, modular workflows for tasks including:

- Building and testing frontend and backend applications
- Running linting, formatting, and static analysis
- Deploying to staging and production environments
- Automating dependency updates and security scans

By maintaining these workflows in one place, I ensure:

- Consistent automation pipelines across all projects
- Easier rollout of improvements and fixes across multiple repositories
- Reduced duplication and simplified workflow management

---

## 🔗 How to use

To consume a workflow from this repository, use the `uses:` directive in your project’s workflow file:

```yaml
jobs:
  build:
    uses: your-github-username/workflow-templates/.github/workflows/build.yml@main