# Copilot Instructions for DAT5501

This repository is for the DAT5501 module, focused on data analysis and coding skill development. AI coding agents should follow these guidelines to be productive:

## Project Overview
- The codebase is currently minimal, with only a `README.md` describing the purpose.
- Expect future additions related to data analysis workflows, scripts, and possibly notebooks.

## Key Conventions
- Place all module-related code, scripts, and documentation in the root directory unless a more structured layout is introduced.
- Use clear, descriptive filenames for scripts and notebooks (e.g., `data_cleaning.py`, `analysis.ipynb`).
- Document any non-obvious workflow steps in the `README.md` or create a new `docs/` directory if complexity increases.

## Developer Workflows
- No build or test automation is currently present. Add instructions to the `README.md` if you introduce custom commands or dependencies.
- For Python scripts, follow standard practices: use virtual environments, requirements files, and clear function/class docstrings.

## Patterns & Integration
- No external dependencies or integration points are defined yet. If you add them, document installation and usage in the `README.md`.
- If you introduce data files, place them in a dedicated `data/` directory and document their format and usage.

## Example: Adding a Data Analysis Script
- Save your script as `analysis.py` in the root directory.
- Add a short usage example to the `README.md`:
  ```bash
  python analysis.py --input data/dataset.csv --output results.csv
  ```
- List any required packages in `requirements.txt`.

## Evolving Instructions
- Update this file as the project grows to reflect new workflows, conventions, and integration points.
- Reference key files and directories as they are added.

---
For questions or unclear conventions, review the `README.md` or ask the repository owner for clarification.
