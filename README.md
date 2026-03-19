# MLOps_Assignment_4

## ML Model CI Pipeline

This repository contains a GitHub Actions pipeline for ML model validation.

### Pipeline Steps
- Checkout repository
- Set up Python 3.10
- Install dependencies
- Linter check (flake8)
- Model dry test (PyTorch)
- Upload project documentation as artifact

### Trigger
Runs on every push to all branches except `main`.
