# Prompt V1 Evaluation

## Test Case 01 — Late Delivery

### AI Model
Claude

### Customer Message

"My order was supposed to arrive yesterday, but I still haven't received it. What should I do?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 4/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **23/25** |

### Strengths

- The response was polite and empathetic.
- It provided practical next steps.
- It requested relevant customer information.
- It avoided inventing a specific delivery policy.
- The response was easy to understand.

### Weakness Identified

The response stated that it would "check the shipping status and tracking history", even though the AI does not have access to an actual order management or tracking system.

This creates a risk of the AI implying that it has performed an action that it cannot actually perform.

### Improvement Required for V2

V2 should include a clear rule that the AI must not claim to access systems, check orders, verify information, issue refunds, or perform other actions unless those capabilities are explicitly available.

### Result

**V1 Score: 23/25 (92%)**

The V1 prompt performed well in the first test but requires stronger capability boundaries and action limitations.
