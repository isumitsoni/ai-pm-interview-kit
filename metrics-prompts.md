# Metrics Prompts

## What interviewers are testing
Metrics questions for AI PM roles are about whether you can define success in a way that reflects real user value rather than raw model activity. Interviewers want to know if you can connect product behavior, quality signals, and business outcomes. In AI products, this often means balancing usage with correctness, trust, and cost instead of choosing one metric in isolation.

## How to structure your answer
Use **V-B-Q-G**:
- **Value:** What user outcome matters
- **Behavior:** What observable action proves the value happened
- **Quality:** What metric tells you the output was acceptable
- **Guardrails:** What prevents the team from improving the wrong thing

Add one leading metric and one lagging metric whenever possible.

## 3 practice prompts
1. "Act as an AI PM interviewer. Ask me how I would define success metrics for a new AI feature. After my answer, push me on guardrails, trust, and how I would know the metric is not vanity."
2. "Run a mock interview about a chatbot with strong usage but rising complaints. Ask me to redesign the metric system and explain why the current metrics are misleading."
3. "Give me an AI PM case where offline evals improved but product KPIs did not. Ask me to explain the disconnect and what I would track next."

## Evaluation rubric
**Strong answer looks like:**
- Starts from user value, not dashboard convenience
- Includes both product outcome and AI quality metrics
- Adds guardrails against gaming
- Distinguishes leading versus lagging indicators
- Connects metrics to decision-making cadence

**Weak answer looks like:**
- Uses engagement alone as success
- Ignores trust, accuracy, or correction rate
- Does not define how a metric is calculated
- Lacks a guardrail against bad optimization
- Cannot explain what action a metric would trigger

## 1 real example question with a model answer outline
**Example question:** "How would you define success metrics for a customer-support chatbot?"

**Model answer outline:**
- User value:
  - Customers get the right answer faster without unnecessary escalation
- Primary metric:
  - Resolution rate for eligible conversations
- Supporting metrics:
  - Time to resolution
  - Containment rate
  - Human correction or re-open rate
  - Customer satisfaction after the interaction
- AI quality metrics:
  - Factual accuracy on audited samples
  - Unsafe-response rate
- Guardrails:
  - Do not celebrate containment if customer satisfaction or correction rate worsens
- Review cadence:
  - Weekly operational review plus monthly quality audit
