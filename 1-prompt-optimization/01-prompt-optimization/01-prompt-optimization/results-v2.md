# V2 Results — Structured Prompt

## Prompt Used

The V2 structured prompt was used to analyse the same Junior AI Support Specialist job description used in V1.

The prompt introduced:

* Role definition
* Context
* Explicit tasks
* Constraints
* Output requirements
* Prioritisation
* Instructions to avoid unsupported assumptions

## AI Output

The prompt was tested using Claude.

The complete raw response is preserved below.

> Paste the complete Claude V2 response here.

## Observations

### Improvements Over V1

1. The output followed a clearly defined seven-section structure.
2. The prompt required the model to rank the five most important keywords.
3. The model clearly separated required skills from advantageous skills.
4. The model avoided performing an unsupported skill-gap analysis because applicant information had not been provided.
5. The response was easier to evaluate because the expected output format was defined in advance.

### Remaining Limitations

1. The prompt still depends on the quality and completeness of the input information.
2. The prompt does not provide a numerical scoring system for evaluating the output.
3. Different models may still interpret some job requirements differently.
4. The prompt does not automatically verify whether extracted keywords are actually present in the job description.

## Evaluation

V2 produced a more structured and controlled response than V1.

The addition of explicit constraints reduced unsupported assumptions and made the output easier to compare and evaluate.

## Conclusion

The experiment demonstrates that adding role definition, context, explicit tasks, constraints, and output formatting can improve the usefulness and consistency of an LLM response.

V2 will be used as the baseline for developing the more advanced V3 prompt.
