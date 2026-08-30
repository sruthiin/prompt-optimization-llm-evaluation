# Prompt V1 — Baseline

## Purpose

Establish a simple baseline so that weaknesses can be observed before explicit quality controls are introduced.

## Prompt

```text
Convert the following work experience into professional resume bullet points.

Experience:
{USER_INPUT}
```

## Expected Risk Areas

Because V1 contains minimal guidance, specifically observe for invented achievements, unsupported metrics, invented technologies or tools, inconsistent bullet count, generic wording, and over-expansion of vague input.

## Test Rule

Run V1 against the same synthetic inputs used for V2 and V3. Do not alter the input between prompt versions.
