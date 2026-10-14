# How to Update — VLLM

**Project:** `VLLM`
**Category:** FRONTIER_HARNESSES
**Domain:** frontier AI harnesses and inference
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
VLLM --version
VLLM check-update
```

### Applying Updates
```bash
pip install --upgrade VLLM
```

### Rolling Back
```bash
pip install VLLM==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
