# Learning Notes

## What is a prompt?
A prompt is the instruction and context provided to an LLM to guide the requested behavior.

## What is zero-shot prompting?
Zero-shot prompting asks the model to perform a task without worked examples of the desired answer. V1 is intentionally simple and serves as the baseline.

## What is prompt iteration?
Prompt iteration means changing the prompt deliberately, testing the changed version, and comparing resulting behavior.

## What is hallucination?
In this project, hallucination refers to unsupported content added by the model, such as invented metrics, tools, technologies, responsibilities, achievements, ownership, or impact.

## Why use the same input across prompt versions?
Using the same input helps isolate the effect of the prompt. If both prompt and data changed, it would be harder to explain why output changed.

## What is an evaluation criterion?
An evaluation criterion is a defined rule used to judge an output consistently.

## Why is a baseline important?
Without a baseline, there is no clear reference point for judging whether later prompt changes improved behavior.

## What trade-offs can prompt optimization create?
More constraints can improve reliability but may also make outputs more generic or less flexible. Evidence should determine whether the trade-off is acceptable.

## How do constraints improve reliability?
Explicit grounding and anti-hallucination rules reduce the model's freedom to fill missing information with plausible but unsupported details.
