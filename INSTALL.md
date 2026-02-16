# forge-google — Installation

> **For AI agents**: This module is a scaffold — Google Workspace integration is not yet implemented.

## As part of forge-core (submodule)

Already included in `defaults.yaml`. No build step required.

```yaml
modules:
  - forge-google    # Platform — Google Workspace (placeholder)
```

## Planned capabilities

| Service | Status |
|---------|--------|
| Gmail | Not implemented |
| Google Calendar | Not implemented |
| Google Tasks | Not implemented |
| Google Drive | Not implemented |

## Dependencies (when implemented)

Will likely require Google Cloud project with OAuth 2.0 credentials and a CLI tool (e.g., `gcloud` or a custom client).

## Verify

See [VERIFY.md](VERIFY.md) for the post-installation checklist.
