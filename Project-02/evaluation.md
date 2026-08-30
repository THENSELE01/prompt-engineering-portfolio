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

The V1 prompt performed well in the first test but requires stronger capability boundaries and action limitations.---

## Test Case 02 — Refund Request

### AI Model
Claude

### Customer Message

"I want a refund for my order. How can I request one?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 3/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **22/25** |

### Strengths

- The response was polite and professional.
- It provided clear steps for starting a refund request.
- It asked for relevant information.
- The response was easy to understand.

### Weakness Identified

The response implied that the AI could confirm refund eligibility and help process the refund, even though it does not have access to the company's refund system or refund policy.

### Improvement Required for V2

The prompt should prevent the AI from claiming that it can determine eligibility, process refunds, or perform actions that require access to external systems.

### Result
---

## Test Case 03 — Damaged Product

### AI Model
Claude

### Customer Message

"My package arrived today, but the product inside is damaged. What can I do?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 3/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **22/25** |

### Strengths

- The response showed empathy toward the customer.
- It provided practical steps, including taking photographs.
- It requested relevant order information.
- It offered clear possible next steps.
- The response was professional and easy to understand.

### Weaknesses Identified

The response implied that the AI could look into the customer's order even though it does not have access to an order management system.

The response also stated that damaged products are usually eligible for a free replacement or full refund and may not need to be returned. No company policy was provided to the AI, so this information was not supported by the available context.

### Improvement Required for V2

V2 should include stronger rules preventing the AI from:

- Claiming access to external systems.
- Inventing company policies.
- Making unsupported claims about refunds, replacements, returns, or eligibility.

### Result
---

## Test Case 02 — Refund Request

### AI Model
Claude

### Customer Message

"I want a refund for my order. How can I request one?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 3/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **22/25** |

### Strengths

- The response was polite and professional.
- It provided clear steps for starting a refund request.
- It asked for relevant information.
- The response was easy to understand.

### Weakness Identified

The response implied that the AI could confirm refund eligibility and help process the refund, even though it does not have access to the company's refund system or refund policy.

### Improvement Required for V2

The prompt should prevent the AI from claiming that it can determine eligibility, process refunds, or perform actions that require access to external systems.

### Result

**V1 Score: 22/25 (88%)**
*

## Test Case 03 — Damaged Product

### AI Model
Claude

### Customer Message

"My package arrived today, but the product inside is damaged. What can I do?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 3/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **22/25** |

### Strengths

- The response showed empathy toward the customer.
- It provided practical steps, including taking photographs.
- It requested relevant order information.
- It offered clear possible next steps.
- The response was professional and easy to understand.

### Weaknesses Identified

The response implied that the AI could look into the customer's order even though it does not have access to an order management system.

The response also stated that damaged products are usually eligible for a free replacement or full refund and may not need to be returned. No company policy was provided to the AI, so this information was not supported by the available context.

### Improvement Required for V2

V2 should include stronger rules preventing the AI from:

- Claiming access to external systems.
- Inventing company policies.
- Making unsupported claims about refunds, replacements, returns, or eligibility.

### Result

**V1 Score: 22/25 (88%)**---

## Test Case 04 — Wrong Product

### AI Model
Claude

### Customer Message

"I ordered a black shirt but received a white one. How can I get the correct item?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 3/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **22/25** |

### Strengths

- The response acknowledged the customer's problem.
- It maintained a professional and empathetic tone.
- It provided practical information the customer could provide.
- It clearly explained possible resolution options.

### Weaknesses Identified

The response implied that the AI could access order details, check product stock, and arrange the correct product for delivery.

It also suggested a return-label and exchange process without being given an actual company return or exchange policy.

### Improvement Required for V2

V2 should clearly separate guidance from actions that require access to company systems.

The AI should not claim that it can:

- Access customer orders.
- Check stock.
- Arrange shipments.
- Create return labels.
- Process exchanges or refunds.

The AI should also avoid inventing company policies when no policy information has been provided.

### Result

**V1 Score: 22/25 (88%)**---

## Test Case 05 — Cancel Order

### AI Model
Claude

### Customer Message

"I just placed an order but I changed my mind. Can I cancel it?"

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 3/5 |
| Helpfulness | 5/5 |
| Professional Tone | 5/5 |
| Clarity | 5/5 |
| Instruction Following | 4/5 |
| **Total** | **22/25** |

### Strengths

- The response was polite and professional.
- It recognised that cancellation may depend on the order status.
- It requested the order number.
- It provided possible next steps clearly.

### Weaknesses Identified

The response implied that the AI could check the order status and cancel the order.

It also stated that a full refund could typically be processed and suggested refusing delivery or returning the item without access to the company's actual cancellation and refund policies.

### Improvement Required for V2

V2 should prevent the AI from:

- Claiming access to order systems.
- Claiming it can cancel orders.
- Claiming it can process refunds.
- Assuming cancellation, return, or refund policies.
- Presenting unsupported company policies as facts.

### Result

**V1 Score: 22/25 (88%)**
