# AGENTS.md

## Project overview
This workspace contains a small Python console program in `python.py`. The script reads an integer from standard input and prints whether it is positive, negative, or zero.

## Working conventions
- Keep the program simple and readable.
- Prefer small, direct Python logic over unnecessary abstractions.
- Preserve the current CLI behavior unless the task explicitly asks for a change.
- When editing the script, keep the input/output contract consistent with the current code.

## Validation
Run the script with Python and test a few representative inputs:

```bash
python python.py
```

Sample checks:
- `5` -> `Positive`
- `-3` -> `Negative`
- `0` -> `Zero`

## Files to know
- `python.py` — main program logic

## Guidance for AI coding agents
- Treat this as a minimal Python exercise rather than a large application.
- If a task involves new features, keep them lightweight and easy to reason about.
- Prefer explicit, understandable code and clear variable naming.
