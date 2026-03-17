# AI Tradeoffs Prompts

## What interviewers are testing
AI PM tradeoff questions test whether you can reason across product value, technical constraints, and business realities at the same time. Interviewers want to see if you understand model quality, latency, cost, safety, architecture, and vendor choices well enough to make product decisions without pretending to be the deepest technical expert in the room.

## How to structure your answer
Use **Q-L-C-T-R**:
- **Quality:** What level of output quality is required for the user job
- **Latency:** How fast the workflow must feel
- **Cost:** What usage economics can support
- **Trust:** What failure risk is acceptable
- **Reversibility:** How hard it is to change the decision later

Then state the recommendation and the conditions under which you would revisit it.

## 3 practice prompts
1. "Act as an AI PM interviewer and ask me whether I would use a frontier model, a cheaper model, or a hybrid setup for a product workflow. After my answer, challenge me on latency, cost, and trust."
2. "Run a mock interview where I must decide between building on OpenAI, Anthropic, or an internal workflow layer. Score me on decision structure, user focus, and technical fluency."
3. "Give me a senior AI PM case where the model is accurate but slow and expensive. Ask how I would redesign the experience and pricing rather than only changing the model."

## Evaluation rubric
**Strong answer looks like:**
- Anchors the tradeoff in a specific user workflow
- Defines the minimum acceptable quality bar
- Talks about cost, latency, and trust together
- Recognizes reversibility and staged rollout options
- Knows when product design can solve a model problem

**Weak answer looks like:**
- Treats best-model quality as automatically correct
- Ignores economics
- Assumes latency only matters to engineering
- Avoids safety or trust concerns
- Makes architectural claims without product reasoning

## 1 real example question with a model answer outline
**Example question:** "Would you use OpenAI or Anthropic for this workflow, and how would you decide?"

**Model answer outline:**
- Start with the workflow:
  - What is the user trying to do
  - How costly is a bad answer
  - How much latency can the user tolerate
- Decision criteria:
  - Output quality on the target task
  - Cost per successful task
  - Latency at expected load
  - Safety or compliance needs
  - Integration and fallback options
- Recommendation:
  - Pick one provider for the pilot based on the most important constraint
- Risk management:
  - Keep an abstraction layer where possible
  - Preserve eval set to compare providers later
- Revisit trigger:
  - Switch or hybridize if margin, quality drift, or reliability changes materially
