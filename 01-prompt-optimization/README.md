# Project 01 — Prompt Optimization & Evaluation

## Overview

This project investigates how prompt design affects the quality, structure, reliability, and transparency of Large Language Model (LLM) responses.

A Junior AI Support Specialist job description was analysed using three progressively improved prompt versions.

The experiment was designed to demonstrate practical prompt-engineering techniques rather than simply producing a single AI response.

## Objective

The objective was to determine whether increasing prompt structure, constraints, evidence requirements, and evaluation criteria could improve the quality and reliability of an LLM response.

## Experimental Method

The same job description was provided to three prompt versions.

The prompts were tested using Claude.

### V1 — Basic Prompt

A simple instruction with minimal context and no defined output structure.

### V2 — Structured Prompt

Added:

* Role definition
* Context
* Explicit tasks
* Constraints
* Output format
* Prioritisation
* Instructions to avoid unsupported assumptions

### V3 — Advanced Prompt

Added:

* Evidence grounding
* Uncertainty handling
* Separation of evidence and recommendations
* Quality-control rules
* Structured extraction
* Output scoring

## Results

The experiment showed a progression from a general AI response toward a more structured and transparent analysis.

### V1

Produced a useful baseline response but provided limited control over structure and assumptions.

### V2

Improved organisation and consistency through explicit tasks, constraints, and output formatting.

### V3

Added stronger evidence controls, uncertainty detection, separation of evidence from recommendations, and an evaluation framework.

## Key Finding

Prompt engineering is not simply about writing a clever instruction.

Effective prompt design can involve:

* Defining the role
* Providing context
* Breaking tasks into clear instructions
* Setting constraints
* Controlling output structure
* Grounding responses in evidence
* Handling uncertainty
* Evaluating output quality

## Project Files

| File                      | Purpose                                        |
| ------------------------- | ---------------------------------------------- |
| `test-data.md`            | Experimental job description and test scenario |
| `prompt-v1-basic.md`      | Baseline prompt                                |
| `results-v1.md`           | V1 experiment results                          |
| `prompt-v2-structured.md` | Structured prompt                              |
| `results-v2.md`           | V2 experiment results                          |
| `prompt-v3-advanced.md`   | Advanced prompt                                |
| `results-v3.md`           | V3 experiment results                          |
| `comparison.md`           | V1 vs V2 vs V3 comparison                      |

## Skills Demonstrated

* Prompt Engineering
* Prompt Optimization
* Structured Prompting
* LLM Evaluation
* Evidence Grounding
* Output Design
* Uncertainty Handling
* Critical Thinking
* AI-Assisted Problem Solving

## Limitations

This experiment used one job description and primarily one LLM environment.

Additional testing across multiple job descriptions and different LLMs would be required to determine whether the observed improvements generalise to other use cases.

## Status

✅ Completed
