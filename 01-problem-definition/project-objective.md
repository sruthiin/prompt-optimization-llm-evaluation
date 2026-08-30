# Project Objective

## Primary Objective

Design, test, and optimize multiple prompt versions for converting raw work-experience notes into concise professional resume bullet points while preserving factual accuracy.

## Specific Objectives

1. Establish a **V1 baseline** using a simple transformation instruction.
2. Introduce explicit factual-grounding and anti-hallucination constraints in **V2**.
3. Add structured constraints, ambiguity handling, and verification guidance in **V3**.
4. Use the same synthetic inputs across all prompt versions.
5. Capture actual model outputs exactly as generated.
6. Evaluate outputs using predefined quality dimensions.
7. Log meaningful failures as defects and investigate likely root causes.
8. Compare prompt versions based on recorded evidence.
9. Document limitations and trade-offs rather than overgeneralizing results.

## Success Criteria

The optimized prompt should demonstrate evidence of:

- preservation of supplied facts;
- reduced unsupported additions;
- clear and concise resume language;
- compliance with requested output constraints;
- useful professional wording;
- safer handling of vague input.

## Evidence Rule

No score, pass/fail result, defect, or improvement claim should be entered until the corresponding test has actually been run and reviewed.
