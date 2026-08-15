# Complete baseline test corpus

This directory is an exact copy of the `tests/` tree at baseline commit
`c0c1ae6`. It contains all 55 baseline test files, not a Bug #8 subset. The
baseline collected 683 pytest cases.

Run from `baseline/source` with the project dependencies:

```bash
python -m pytest -q --disable-warnings
```

The recorded headless validation result was 434 passed, 4 failed, and 245
errors. The errors arose from unavailable Windows/UI/audio fixtures and are
preserved in the corpus rather than silently deleting tests. Use the metadata
file for the exact environment and commands.
