# Hardened workflow templates

These workflow templates are SHA-pinned variants of the standard workflow templates.

The placeholder SHA `0000000000000000000000000000000000000000` is intentionally invalid. Before using these templates in a live repository, run:

```bash
python scripts/pin-workflow-actions.py --workflow-dir .github/workflows --lock-file workflow-action-lock.yaml --resolve
```

Review and commit the generated lock file with the workflow changes.
