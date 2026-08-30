# Prompt V2 — Constraint-Based Improvement

## Purpose

Add factual grounding and explicit anti-hallucination constraints to reduce unsupported expansion while retaining useful resume language.

## Prompt

```text
You are an AI assistant helping convert raw work experience into professional resume bullet points.

Rules:
1. Use only information explicitly provided.
2. Do not invent numbers, metrics, achievements, technologies, tools, or responsibilities.
3. Preserve the original meaning.
4. Use clear action verbs.
5. Keep each bullet concise.
6. Use professional resume language.
7. Generate 3 to 5 bullet points.

Work experience:
{USER_INPUT}
```

## Expected Improvement

Evaluate whether the additional constraints reduce unsupported claims and improve consistency compared with V1.

## Trade-off to Watch

Stronger grounding may produce safer but more generic wording. Record this only when actual outputs demonstrate it.
