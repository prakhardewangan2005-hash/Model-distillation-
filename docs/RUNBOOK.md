# Runbook — MODEL DISTILLATION LAB

This runbook is written for a “demo-first, production-style” workflow: deterministic runs, idempotent output structure, quick diagnosis, and safe defaults for CPU-only environments (e.g., GitHub Codespaces).

## Standard Operating Procedure (SOP)

### 1) Setup (local or Codespaces)
```bash
python -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install -e .
