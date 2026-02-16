# forge-google — Verification

> **For AI agents**: This module is a scaffold. Verification is minimal.

## Structure check

```bash
test -f Modules/forge-google/module.yaml && echo "module.yaml present"
test -f Modules/forge-google/hooks/hooks.json && echo "hooks.json present"
```

## Expected results

- Module directory exists with `module.yaml` and `hooks/hooks.json`
- No active hooks (hooks.json is empty)
- No binaries to build
