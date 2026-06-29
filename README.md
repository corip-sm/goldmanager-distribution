# GoldManager Distribution

This repository stores only GoldManager release metadata and the packaged launcher binary.

Expected contents:

- `release.json`
- GitHub Release assets named `GoldManager.exe`

`release.json` currently uses the single-file update format:

```json
{
  "version": "0.1.21",
  "url": "https://github.com/corip-sm/goldmanager-distribution/releases/download/v0.1.21/GoldManager.exe",
  "sha256": "<sha256>"
}
```

Source code does not belong in this repository.
