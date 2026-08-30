# Prompt Change Log

| Version | Change | Reason | Quality Risk Addressed |
|---|---|---|---|
| V1 | Simple task instruction | Establish baseline behavior | Unknown baseline failure patterns |
| V2 | Added factual grounding and explicit anti-hallucination rules | Reduce unsupported additions | Metrics, tools, achievements, responsibilities |
| V3 | Added structure, ambiguity handling, output constraints, and verification | Improve consistency and reliability | Ambiguity, verbosity, first-person use, unsupported claims |

## Change Rationale

### V1 → V2

The baseline gives the model broad freedom. V2 introduces explicit rules that define what the model must not add and requires preservation of the original meaning.

### V2 → V3

V3 adds controls for common residual risks: vague inputs, inconsistent output length, repetition, first-person phrasing, and the absence of a final verification step.

## Evaluation Principle

A prompt change is useful only when actual test evidence shows that it addressed the intended quality risk. More instructions do not automatically mean better performance.
