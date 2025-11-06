# Pull Request Guidelines – CountyStat Team

These guidelines help ensure high-quality, consistent, and collaborative code contributions across our GitHub repositories.

## 1. Clear and Descriptive Titles
- Use concise titles that summarize the purpose of the PR (e.g., `Add data cleaning script for jail booking data`).
- Include a brief summary of:
  - What the PR does  
  - Why the change is needed  
  - Any relevant context (e.g., data sources, docker container name, DAG file)

## 2. Data Sensitivity Check
- Confirm that no personally identifiable information (PII) or sensitive data is exposed in code, or documentation.

## 3. Reproducibility
- Ensure scripts are clean (e.g., restart enviornment, run all lines or re-render output).
- Document dependencies if a new package or library is being used from previous iterations.

## 4. Testing and Validation
- Describe how the code was tested (e.g., local/manual validation, dev environment, visual code inspection).
- Include test data or mock data if applicable.

## 5. Repository-Wide Consistency
- Ensure related changes are made across all relevant files (e.g., scripts, notebooks, configs, documentation).
- Avoid leaving outdated or inconsistent logic in other parts of the repo or script. (e.g. commented out code, abandoned/irrelevant scripts).

## 6. Mindful of Team Context
- Be aware of the scheduled run times of impacted code. If a DAG is set to run in a week, wait a day or two before submitting a PR to ensure you have considered all possibilities.
- Avoid submitting multiple small PRs and have an extensive well-scoped PR when possible, rather than multiple rapid fire PRs or additional commits submitted in quick succession.

## 7. Review Ready
- Tag the data-engineering group or a team member for review.
- Be open to feedback and iterate as needed.
- Update relevant README files or data dictionaries if the PR introduces new functionality or dataset outputs.

## 8. Compliance and Standards
- Follow internal coding standards (e.g., naming conventions, newlines & spacing, folder structure).
- Use consistent formatting (e.g., snake_case, camelCase).
