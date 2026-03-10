# git-test

Minimal Python sandbox project for validating a basic Codex workflow.

## Project Purpose
This repository is intentionally small and is useful for practicing:

1. Read project files
2. Plan a change
3. Edit code
4. Review updates
5. Commit changes

## Structure
- `src/main.py` - simple entry-point script
- `tests/test_main.py` - test module placeholder
- `requirements.txt` - Python dependencies

## Quick Start
### 1) Create and activate a virtual environment
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 2) Install dependencies
```powershell
pip install -r requirements.txt
```

### 3) Run the app
```powershell
python src/main.py
```

### 4) Run tests
```powershell
pytest -q
```

## Suggested Improvements
1. Replace placeholder test with a real behavior test for `src/main.py`.
2. Add `pytest` to `requirements.txt` (or create `requirements-dev.txt`).
3. Introduce a callable function in `src/main.py` so logic can be tested cleanly.
4. Add formatting and linting (`black`, `ruff`) for consistent style.
5. Add CI (for example GitHub Actions) to run tests on each push.

## Notes
- Keep this repository intentionally lightweight for experimentation.
- If non-English text is needed, save files in UTF-8 to avoid encoding issues.
