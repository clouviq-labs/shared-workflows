# shared-workflows

Shared CI for clouviq-labs repositories.

- `.github/workflows/python-lint.yml`: reusable workflow (`workflow_call`) that lints with Ruff.
- `setup-app/action.yml`: composite action that installs Python, the pip cache and requirements.

Pin a release tag (`@v1`) or a full commit SHA.
