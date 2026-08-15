# Mantella agent benchmarks

This repository contains reproducible coding-agent tasks based on frozen
historical Mantella source states. The agent-visible benchmark contains only
the source and tests that existed at the selected baseline, plus a neutral
developer task. Post-investigation evaluator material is maintained separately
in `whiskywater/mantella-agent-benchmark-evaluator`.

## Benchmark 01

`benchmark-01-bug8` freezes Mantella at commit `c0c1ae6` from immediately
before the first Equip/Bug #8 solution commit. See its `TASK.md` for the
developer-visible problem and `baseline/metadata/baseline.json` for exact
reproduction details.

The benchmark task intentionally does not disclose implementation files,
root-cause notes, or evaluator tests.
