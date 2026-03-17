# Prioritization Prompts

## What interviewers are testing
Prioritization questions in AI PM interviews are about decision quality under uncertainty. Interviewers want to know whether you can compare bets with incomplete evidence, balance short-term delivery against long-term leverage, and make clear choices when quality, trust, cost, and market timing do not all point in the same direction. This is where seniority shows up fast.

## How to structure your answer
Use **R-A-I-D-E**:
- **Reach:** Who is affected and how often
- **AI leverage:** Where AI changes the user outcome materially
- **Impact:** User and business upside
- **Dependencies:** Data, model, legal, or engineering constraints
- **Evidence:** What is proven versus assumed

End with an explicit recommendation and what you would deprioritize.

## 3 practice prompts
1. "Act as an AI PM interviewer. Give me a prioritization case with three candidate AI initiatives and limited engineering capacity. After my answer, challenge my assumptions and ask what I would say no to."
2. "Run a mock interview where I must choose between quality improvements, a new AI workflow, and cost reduction. Score me on user impact reasoning, evidence quality, and tradeoff clarity."
3. "Give me a senior-level AI PM prioritization question where legal risk, model cost, and growth pressure conflict. Ask follow-up questions until I make a specific call."

## Evaluation rubric
**Strong answer looks like:**
- Defines the decision frame clearly
- Separates proven signals from assumptions
- Includes user impact, business impact, and execution risk
- Makes tradeoffs explicit
- States what is not being prioritized and why

**Weak answer looks like:**
- Uses only generic frameworks without context
- Treats all initiatives as equally important
- Ignores cost, data, or trust constraints
- Avoids making a hard recommendation
- Fails to explain what evidence would change the decision

## 1 real example question with a model answer outline
**Example question:** "You can fund only one initiative next quarter: improve model accuracy, launch a new AI workflow, or reduce inference cost. What do you do?"

**Model answer outline:**
- Clarify the current state:
  - Is adoption weak because value is missing or because quality is unreliable?
  - Are margins already under pressure?
  - Is there strong demand for the new workflow?
- Compare options:
  - Accuracy: best if current users do not trust outputs
  - New workflow: best if the core product is healthy and expansion demand is clear
  - Cost reduction: best if unit economics are blocking scale
- Recommendation:
  - Choose the one most strongly tied to the current bottleneck
- Tradeoff:
  - Explain what delayed option is being consciously deferred
- Evidence plan:
  - Name the metric or experiment that would validate the choice in one quarter
