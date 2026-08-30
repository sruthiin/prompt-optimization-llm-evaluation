# Test Strategy

## Objective

Evaluate whether prompt changes improve resume-output quality and factual reliability while minimizing unsupported claims.

## Test Design

### Controlled Variable
Prompt version: V1, V2, or V3.

### Controlled Inputs
The same synthetic test data is reused across prompt versions.

### Execution Context
Record the model name/version, test date, conversation mode, relevant model settings if exposed, any special instructions, and reproducibility notes.

### Execution Method

1. Start a clean or controlled conversation.
2. Run the selected prompt with one synthetic input.
3. Copy the actual output exactly.
4. Record the output against the matching Test ID.
5. Evaluate the output against the predefined criteria.
6. Repeat for the same input with the next prompt version.
7. Review outputs side-by-side.
8. Log defects where a requirement is missed.
9. Record evidence screenshots for useful test examples.

## Result Handling

- **PASS:** Expected behavior is met.
- **PARTIAL:** Some requirements are met, but a meaningful issue remains.
- **FAIL:** A major requirement is missed or unsupported content is generated.
- **PENDING_EXECUTION:** Test has not yet been run.

## Adversarial Tests

At minimum, inspect metric, tool, impact, ambiguity, and ownership traps.

## Quality Controls

Do not change the input between prompt versions, silently rewrite model outputs before storing them, score based only on professional tone, treat plausible unsupported claims as acceptable, or report improvements unsupported by evidence.

## Evidence

Save screenshots that clearly show the prompt version, relevant input, actual model output, and evaluation sheet/results where useful. Remove personal or unrelated information before committing evidence.
