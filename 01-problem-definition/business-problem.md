# Business Problem

## Background

Job seekers often start with raw notes about their work rather than polished resume language. These notes may be short, informal, incomplete, or ambiguous.

An LLM can transform those notes into professional resume bullet points quickly. The risk is that a model may optimize for persuasive writing instead of factual preservation.

## Quality Risk

A weak prompt may lead to unsupported additions such as:

- invented metrics or percentages;
- invented tools, technologies, or frameworks;
- responsibilities that were not provided;
- stronger ownership or leadership claims than the input supports;
- business impact that cannot be evidenced;
- unnecessary repetition or generic wording.

For a resume use case, a polished hallucination is still a factual defect.

## Business Question

**How do prompt changes affect the quality and factual reliability of AI-generated resume bullet points?**

## Why This Matters

The project treats prompt engineering as a measurable AI quality activity: establish a baseline, expose failure modes, add targeted controls, retest using the same input, and measure or explain whether behavior improved.

## Portfolio Perspective

This scenario demonstrates practical AI quality thinking around grounding, test design, hallucination control, prompt iteration, output evaluation, and evidence-based decision making.
