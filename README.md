# GoldManager Distribution

This repository stores only GoldManager release metadata and the packaged launcher binary.

Expected manifests:

- `release.json` for 이태리주얼리
- `editions/pico/release.json` for 피코
- GitHub Release assets named `GoldManager.exe` or `GoldManager-Pico.exe`

Each manifest uses the single-file update format and includes an `editionId`:

```json
{
  "version": "0.1.21",
  "url": "https://github.com/corip-sm/goldmanager-distribution/releases/download/v0.1.21/GoldManager.exe",
  "sha256": "<sha256>",
  "editionId": "italy-jewelry"
}
```

Source code does not belong in this repository.
